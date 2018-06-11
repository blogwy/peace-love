# 布局

**peace&love.css** 采用了当下流行的12列栅格化系统和列偏移进行不布局

## 栅格化系统

### 类名格式

在外层元素添加 **\.flex** 的类名，内层元素添加 **\.flex-{1~12}** 可实现基本栅格化布局。(可以在外层元素添加 **\.center-center** 实现内层元素水平垂直居中)

### Example

```html
<!-- 部分代码 -->
<div class="flex center-center">
  <div class="flex-1">flex-1</div>
  <div class="flex-1">flex-1</div>
  <div class="flex-1">flex-1</div>
  <div class="flex-1">flex-1</div>
  <div class="flex-1">flex-1</div>
  <div class="flex-1">flex-1</div>
  <div class="flex-1">flex-1</div>
  <div class="flex-1">flex-1</div>
  <div class="flex-1">flex-1</div>
  <div class="flex-1">flex-1</div>
  <div class="flex-1">flex-1</div>
  <div class="flex-1">flex-1</div>
</div>
```

![img](http://ww1.sinaimg.cn/large/005LOKa8gy1fs65ly1rurj311l0go74j.jpg)

## 列偏移

### 类名格式

在内元素添加 **\.offset-{1~12}** 可以实现列偏移

### Example

```html
<!-- 部分代码 -->
<div class="flex center-center">
  <div class="flex-1">flex-1</div>
  <div class="flex-2 offset-1">flex-2 offset-1</div>
</div>
```

![img](http://ww1.sinaimg.cn/large/005LOKa8gy1fs667lur16j311l0a93yn.jpg)

