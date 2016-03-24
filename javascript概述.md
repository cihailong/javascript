#javaScript概述

##程序语言

## 基础逻辑处理部分

  >变量 数据类型

  >分支和循环

  >函数（对语言的扩展）
```javascript
var a=1;                //Number
var a='1'              //String
var a=[1,2,3]         //Array
var a={a:1,b:2}      //object
var a=function(){}  //function
var a=true         //Boolean
var a=undefined
var a=null
```
### 运算符
```
+ - / * %
=== !== > < >= <= 
&&   ||    !
```
### 分支语句
```javascript
if()
if()else
if()else if()else if()
swith(x){
	case 1:
	break;
	case 2;
	break;
	default;
	break;
}
```
### 循环语句
```javascript
for(var i=0,k=12,i<10;i++){
	
}
whlie(){
	
}do{
	
}
while()```

### 函数
```
function xx(){
	
}

var fn=function(x1,x2){
	//arguments
}
fn(a,b)
```
### 函数的常用方法
### 字符串中的常用方法
### 函数对象中的方法
### 对象的增删改查 原型链
### 数字对象身上的方法 toFixed
### math对象身上的方法
```javascript
function A(c){
	this.x=c;
}
A.prototype.console=function(){
	console.log(this.x)
}
```
## 针对特定用途的部分
  >当js来浏览器运行的那一刻
  >浏览器会创建一个window对象
  >wondow对象中很多属性和方法
  >这些属性和方法不用加window就可以使用

dom对象  dom集合

###  选取元素  
* var el=document.getElementById()
* var el=document.getElementclassName
* var el=document.getElementTagName
* var el=document.getElementByName
### 筛选元素
  *el.parentNode
  *el.firstchilds
  *el.nextSiblng
  *el.previousSibling
  *el.lastchilds
  *el.cildNodes
### 操作样式
 *el.style.width  
 *el.style.height
### 获取位置信息
*document.documentElement.clientX;
*document.documentElement.clientY;
*document.documentElement.screenX;
*document.documentElement.screenY;
*document.documentElement.offsetX;
*document.documentElement.offsetY;
### 操作属性
  对象.属性
对象.属性=值 
### 节点操作
*el.removechild
*el.replacechild
*el.insertBefore
*el.setAttribute
*el.creatElement
*el.createTextNode
### 获取元素信息
 *el.offsetwidth
 *el.offsetheight

### 其他

```javaScript
var a=12;
var c=function(){
	console.log(1)
}
```
###
####
