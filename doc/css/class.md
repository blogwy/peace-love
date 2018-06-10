# 辅助类

## 边距

为了快速添加 **margin** 和 **padding** ，所添加的值都是8的倍数;

### 类名格式

{属性简写}{方向简写}{值}

### 简写对照表

* m -- margin
* p -- padding
* l -- left
* t -- top
* r -- right
* b -- bottom
* 0 -- 0px
* 8 -- 8px
* 16 -- 16px
* 24 -- 24px
* 32 -- 32px

### 部分源码

```css
.ml8{
  margin-left: 8px!important;
}
.pl8{
  padding-left: 8px!important;
}
```

## 清除浮动

一个类名解决清除浮动的问题

### 类名格式

clearfix

### 源码

```css
.clearfix:after {
	content: ' ';
	display: block;
	clear: both;
	visibility: hidden;
	line-height: 0;
	height: 0;
}
```

## 快速浮动

分为左浮动和右浮动

### 类名格式

左浮动：fl

右浮动：fr

### 源码

```css
.fr {
	float: right!important;
}

.fl {
	float: left!important;
}
```

## 一像素问题

解决ios 1px边框显示较宽的问题

### 类名格式

border

### 源码

```css
.border:after {
	content: "";
	position: absolute;
	top: 0;
	left: 0;
	border-top: 1px solid #DCDCDC;
	-webkit-box-sizing: border-box;
	width: 200%;
	height: 200%;
	-webkit-transform: scale(.5);
	-webkit-transform-origin: left top;
}
```

## 文本对齐方式

分为左对齐、右对齐、居中三种选项

### 类名格式

左对齐：text-left

右对齐：text-right

居中对齐：text-center

### 源码

```css
.text-left{
  text-align: left;
}
.text-center{
  text-align: center;
}
.text-right{
  text-align: right;
}
```

## 移动端滚动回弹效果

开启移动端网页y轴滚动回弹效果

### 类名格式

overtouch

### 源码

```css
.overtouch {
	overflow-y: auto;
	-webkit-overflow-scrolling: touch;
}
```

## 文本超出部分显示省略号

文本超出部分显示省略号（...），分为三种。一行超出省略、两行超出省略、三行超出省略

### 类名格式

一行：ellipsis

两行：ellipsis-2

三行：ellipsis-3

### 源码

```css
/* 一行 */
.ellipsis {
	overflow: hidden;
	text-overflow: ellipsis;
	white-space: nowrap;
}
/* 两行 */
.ellipsis-2 {
	display: -webkit-box;
	overflow: hidden;
	text-overflow: ellipsis;
	white-space: normal!important;
	-webkit-line-clamp: 2;
	-webkit-box-orient: vertical;
}
/* 三行 */
.ellipsis-3 {
	display: -webkit-box;
	overflow: hidden;
	text-overflow: ellipsis;
	white-space: normal!important;
	-webkit-line-clamp: 3;
	-webkit-box-orient: vertical;
}
```


