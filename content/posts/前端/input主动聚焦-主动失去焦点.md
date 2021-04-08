---
title: "input主动聚焦-主动失去焦点"
date: 2021-04-08 23:05:12.774 +0800
categories: ['前端']
tags: ['input']
---



### 主动聚集

调用`Element`的`focus()`方法可以主动聚焦

```javascript
//html
<input  />
//js
document.querySelector('input').focus()
    
```

需要在浏览器获得焦点的情况下才有效果

### 主动失去焦点

调用`Element`的`blur()`方法可以主动失去焦点

```javascript
//html
<input  />
//js
document.querySelector('input').blur()
    
```

###  autofocus属性

HTML5的inpu加`autofocus`属性初始化后马上获得焦点