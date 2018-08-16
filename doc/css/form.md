# 表单

**表单元素目前包括 input textarea select checkbox radio**

## input

**input 样式分为四种 颜色、大小、是否带图标、禁止样式**

### 颜色

总共有五种颜色，分别是 **#fff(默认)**、**#00d1b2**、**#23d160**、**#ffdd57**、**#ff3860**

#### 类名格式

* **is-primary : #00d1b2**

* **is-success : #23d160**

* **is-warning : #ffdd57**

* **is-danger : #ff3860**

#### Example

```html
<input type="text" class="input" placeholder="默认颜色">
<input type="text" class="input is-primary" placeholder="primary">
<input type="text" class="input is-success" placeholder="success">
<input type="text" class="input is-warning" placeholder="warning">
<input type="text" class="input is-danger" placeholder="danger">
```

![img](http://ww1.sinaimg.cn/large/005LOKa8gy1fs7mljuk9yj30en0803yf.jpg)

### 大小

分为四种大小的input，分别是小、默认、中、大

#### 类名格式

* **is-small : 小**

* **is-medium : 中**

* **is-large : 大**

#### Example

```html
<input type="text" class="input is-small" placeholder="小">
<input type="text" class="input" placeholder="默认">
<input type="text" class="input is-medium" placeholder="中">
<input type="text" class="input is-large" placeholder="大">
```

![img](http://ww1.sinaimg.cn/large/005LOKa8gy1fs7mljukxgj30eo06st8j.jpg)

### 带有图标

分为图标在左、图标在右、左右都有三种情况

#### Example

```html
<!--左右都有图标-->
<div class="icon-input-item icon-input-left icon-input-right">
  <input type="text" class="input">
  <span class="icon icon-is-left">
    <i class="fas fa-envelope"></i>
  </span>
  <span class="icon icon-is-right">
    <i class="fas fa-check"></i>
  </span>
</div>

<!--图标在左-->
<div class="icon-input-item icon-input-left">
  <input type="text" class="input">
  <span class="icon icon-is-left">
    <i class="fas fa-envelope"></i>
  </span>
</div>

<!--图标在右-->
<div class="icon-input-item icon-input-right">
  <input type="text" class="input">
  <span class="icon icon-is-right">
    <i class="fas fa-check"></i>
  </span>
</div>
```

![img](http://ww1.sinaimg.cn/large/005LOKa8gy1fs7mljuvt3j30ek05xjr6.jpg)

### 禁止样式

禁止样式无须css类，加入disable属性后即可;

![img](http://ww1.sinaimg.cn/large/005LOKa8gy1fs7n2lib7vj30eg01qdfl.jpg)

## textarea

textarea(文本域),目前只有颜色和禁止样式

### 颜色

#### 类名格式

* **is-primary : #00d1b2**

* **is-success : #23d160**

* **is-warning : #ffdd57**

* **is-danger : #ff3860**

#### Example

```html
<textarea class="textarea"></textarea>
<textarea class="textarea is-primary"></textarea>
<textarea class="textarea is-success"></textarea>
<textarea class="textarea is-warning"></textarea>
<textarea class="textarea is-danger"></textarea>
```

### 禁止样式

禁止样式无须css类，加入disable属性后即可;

![img](http://ww1.sinaimg.cn/large/005LOKa8gy1fs7na6jadsj30ei03wgld.jpg)

## select

select 目前有三种样式，分别是大小、颜色、是否有左侧图标；

### 大小

分为四种大小的input，分别是小、默认、中、大

#### 类名格式

* **is-small : 小**

* **is-medium : 中**

* **is-large : 大**

#### Example

```html
<div class="select is-small">
  <select>
    <option>Select dropdown</option>
    <option>With options</option>
  </select>
</div>
<div class="select">
  <select>
    <option>Select dropdown</option>
    <option>With options</option>
  </select>
</div>
<div class="select is-medium">
  <select>
    <option>Select dropdown</option>
    <option>With options</option>
  </select>
</div>
<div class="select is-large">
  <select>
    <option>Select dropdown</option>
    <option>With options</option>
  </select>
</div>
```

![img](http://ww1.sinaimg.cn/large/005LOKa8gy1fs7nzy9x4oj30d906uaa2.jpg)

### 颜色

总共有五种颜色，分别是 **#fff(默认)**、**#00d1b2**、**#23d160**、**#ffdd57**、**#ff3860**

#### 类名格式

* **is-primary : #00d1b2**

* **is-success : #23d160**

* **is-warning : #ffdd57**

* **is-danger : #ff3860**

#### Example

```html
<div class="select">
  <select>
    <option>Select dropdown</option>
    <option>With options</option>
  </select>
</div>

<div class="select is-primary">
  <select>
    <option>Select dropdown</option>
    <option>With options</option>
  </select>
</div>

<div class="select is-warning">
  <select>
    <option>Select dropdown</option>
    <option>With options</option>
  </select>
</div>

<div class="select is-success">
  <select>
    <option>Select dropdown</option>
    <option>With options</option>
  </select>
</div>

<div class="select is-danger">
  <select>
    <option>Select dropdown</option>
    <option>With options</option>
  </select>
</div>
```

![img](http://ww1.sinaimg.cn/large/005LOKa8gy1fs7nzyl4nwj305g083aa1.jpg)

### 是否有左侧图标

#### Example

```html
<div class="icon-select-item icon-select-left">
  <div class="select is-danger is-small">
    <select>
      <option>Select dropdown</option>
      <option>With options</option>
    </select>
  </div>
  <span class="icon icon-is-left">
    <i class="fas fa-envelope"></i>
  </span>
</div>
```

![img](http://ww1.sinaimg.cn/large/005LOKa8gy1fs7nzyraizj30b608xmx7.jpg)

## radio

### 颜色

总共有五种颜色，分别是 **#209cee(默认)**、**#00d1b2**、**#23d160**、**#ffdd57**、**#ff3860**

#### 类名格式

* **filling-primary : #00d1b2**

* **filling-success : #23d160**

* **filling-warning : #ffdd57**

* **filling-danger : #ff3860**

#### Example

```html
<div class="mt8">
  <label class="radio-lab">
    <input type="radio" class="radio" name="radio-grounp1">
    <span class="radio-icon-rounded"></span>
  </label>
  <label class="radio-lab">
    <input type="radio" class="radio" name="radio-grounp1">
    <span class="radio-icon-rounded"></span>
  </label>
</div>

<div class="mt8">
  <label class="radio-lab">
    <input type="radio" class="radio filling-primary" name="radio-grounp2">
    <span class="radio-icon-rounded"></span>
  </label>
  <label class="radio-lab">
    <input type="radio" class="radio filling-primary" name="radio-grounp2">
    <span class="radio-icon-rounded"></span>
  </label>
</div>

<div class="mt8">
  <label class="radio-lab">
    <input type="radio" class="radio filling-warning" name="radio-grounp3">
    <span class="radio-icon-rounded"></span>
  </label>
  <label class="radio-lab">
    <input type="radio" class="radio filling-warning" name="radio-grounp3">
    <span class="radio-icon-rounded"></span>
  </label>
</div>

<div class="mt8">
  <label class="radio-lab">
    <input type="radio" class="radio filling-success" name="radio-grounp4">
    <span class="radio-icon-rounded"></span>
  </label>
  <label class="radio-lab">
    <input type="radio" class="radio filling-success" name="radio-grounp4">
    <span class="radio-icon-rounded"></span>
  </label>
</div>

<div class="mt8">
  <label class="radio-lab">
    <input type="radio" class="radio filling-danger" name="radio-grounp5">
    <span class="radio-icon-rounded"></span>
  </label>
  <label class="radio-lab">
    <input type="radio" class="radio filling-danger" name="radio-grounp5">
    <span class="radio-icon-rounded"></span>
  </label>
</div>
```

![img](http://ww1.sinaimg.cn/large/005LOKa8ly1fubw7omrpvj302d047q2p.jpg)

### 形状

**分为圆形和方形两种**

#### 类名格式

* **radio-icon-rounded : 圆形**
* **radio-icon-square : 方形**

#### Example

```html
<div class="mt8">
  <label class="radio-lab">
    <input type="radio" class="radio filling-danger" name="radio-grounp8">
    <span class="radio-icon-rounded"></span>
  </label>
  <label class="radio-lab">
    <input type="radio" class="radio filling-danger" name="radio-grounp8">
    <span class="radio-icon-rounded"></span>
  </label>
</div>

<div class="mt8">
  <label class="radio-lab">
    <input type="radio" class="radio filling-danger" name="radio-grounp9">
    <span class="radio-icon-square"></span>
  </label>
  <label class="radio-lab">
    <input type="radio" class="radio filling-danger" name="radio-grounp9">
    <span class="radio-icon-square"></span>
  </label>
</div>
```

![img](http://ww1.sinaimg.cn/large/005LOKa8ly1fubw7ondfrj302e08idfm.jpg)

## checkbox

### 颜色

总共有五种颜色，分别是 **#209cee(默认)**、**#00d1b2**、**#23d160**、**#ffdd57**、**#ff3860**

#### 类名格式

* **filling-primary : #00d1b2**

* **filling-success : #23d160**

* **filling-warning : #ffdd57**

* **filling-danger : #ff3860**

#### Example

```html
<label class="checkbox-lab">
  <input type="checkbox" class="checkbox filling-success" name="checkbox-grounp1">
  <span class="checkbox-icon-square"></span>
</label>
<label class="checkbox-lab">
  <input type="checkbox" class="checkbox filling-warning" name="checkbox-grounp2">
  <span class="checkbox-icon-square"></span>
</label>
<label class="checkbox-lab">
  <input type="checkbox" class="checkbox filling-danger" name="checkbox-grounp3">
  <span class="checkbox-icon-square"></span>
</label>
<label class="checkbox-lab">
  <input type="checkbox" class="checkbox filling-primary" name="checkbox-grounp4">
  <span class="checkbox-icon-square"></span>
</label>
```

### 形状

**分为圆形和方形两种**

#### 类名格式

* **checkbox-icon-rounded : 圆形**
* **checkbox-icon-square : 方形**

#### Example

```html
<div class="mt8">
  <label class="checkbox-lab">
    <input type="checkbox" class="checkbox filling-success" name="checkbox-grounp1">
    <span class="checkbox-icon-rounded"></span>
  </label>
  <label class="checkbox-lab">
    <input type="checkbox" class="checkbox filling-warning" name="checkbox-grounp2">
    <span class="checkbox-icon-square"></span>
  </label>
  <label class="checkbox-lab">
    <input type="checkbox" class="checkbox filling-danger" name="checkbox-grounp3">
    <span class="checkbox-icon-rounded"></span>
  </label>
  <label class="checkbox-lab">
    <input type="checkbox" class="checkbox filling-primary" name="checkbox-grounp4">
    <span class="checkbox-icon-square"></span>
  </label>
</div>
```

![img](http://ww1.sinaimg.cn/large/005LOKa8ly1fubwjh1sr1j304201qmwx.jpg)