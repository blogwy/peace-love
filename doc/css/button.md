# 按钮

按钮目前有五种样式，分为颜色、大小、胶囊按钮、删除按钮、带图标的按钮。图标资源引用 
**font-awesome**;

> **注：所有按钮都应添加 **.button** 公共类名**

## 颜色

分为五种颜色，**#fff**(默认)，**#00d1b2**，**#ffdb4a**，**#23d160**，**#ff3860**;

### 类名格式

* **is-primary : #00d1b2**

* **is-warning : #ffdb4a**

* **is-success : #23d160**

* **is-danger : #ff3860**

### Example

```html
<button class="button">按钮</button>
<button class="button is-primary">按钮</button>
<button class="button is-warning">按钮</button>
<button class="button is-success">按钮</button>
<button class="button is-danger">按钮</button>
```

![img](http://ww1.sinaimg.cn/large/005LOKa8gy1fs7d41d6mkj309r01nweb.jpg)

## 大小

分为五种 **size** ，小、默认、中等、大；

### 类名格式

* **is-small : 小**

* **is-medium : 中等**

* **is-large : 大**

### Example

```html
<button class="button is-small">按钮</button>
<button class="button">按钮</button>
<button class="button is-medium">按钮</button>
<button class="button is-large">按钮</button>
```

![img](http://ww1.sinaimg.cn/large/005LOKa8gy1fs7d41d2jzj308f022dfo.jpg)

## 图标

分为三种样式，图标在左文字在右，图标在右文字在左，没有文字；

### Example

```html
<!--图标在左-->
<button class="button">
  <span class="btn-icon">
    <i class="fas fa-envelope"></i>
  </span>
  <span>图标在左</span>
</button>

<!--图标在右-->
<button class="button">
  <span>图标在右</span>
  <span class="btn-icon">
    <i class="fas fa-envelope"></i>
  </span>
</button>

<!--没有文字-->
<button class="button">
  <span class="btn-icon">
    <i class="fas fa-envelope"></i>
  </span>
</button>
```

## 删除按钮

### 类名格式

* **button-delete**

### Example

```html
<button class="button-delete is-small"></button>
<button class="button-delete"></button>
<button class="button-delete is-medium"></button>
<button class="button-delete is-large"></button>
```

![img](http://ww1.sinaimg.cn/large/005LOKa8gy1fs7d41datqj303x01cjr5.jpg)

## 胶囊按钮

### 类名格式

* **is-rounded**

### Example

```html
<button class="button is-rounded">胶囊按钮</button>
```

![img](http://ww1.sinaimg.cn/large/005LOKa8gy1fs7d41ct5qj303901h0si.jpg)