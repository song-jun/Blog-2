---
title: HTML5中的API
---

## 获取页面元素

- `document.querySelector("选择器");`
  - 选择器可以是css中的任意一种选择器
  - 通过该选择器只能选中第一个元素

- `document.querySelectorAll("选择器");`  
	- querySelectorAll会返回所有符合选择器规则的元素列表
	- querySelector返回的只是单独的一个元素

## 类名操作

```js
🎈 Dom.classList.add("类名"): 给当前dom元素添加类样式

🎈 Dom.classList.remove("类名"); 给当前dom元素移除类样式

🎈 classList.contains("类名"); 检测是否包含类样式

🎈 classList.toggle("active");  切换类样式（有就删除，没有就添加）
```

## 自定义属性