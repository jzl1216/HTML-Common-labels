# HTML常用标签

## 英语小课堂
* hyber 超级
* target 目标
* reference 引用
* frame 边框、框架
* error 错误
* blank 空白
* parent 父母之一
* self 自己
* load 加载
* canvas 画布

## a标签的用法
### 属性
* href(超链接) = hyber reference
* target（作用：在哪一个窗口打开超链接）
* dowdload(了解就行)
* rel=noopener(了解就行)
#### a的href的取值
1. 网址
* https://google.com
* http://google.com
* //google.com
2. 路径
* /a/b/c以及a/b/c   （/a/b/c中的第一个/ ，不是硬盘根目录，httpfuwu的根目录）
* index.html以及./index.html
3. 伪协议
* javascript:代码
* mailto:邮箱
* tel:手机号
4. ID
href="#xxx"
#### a的target的取值
1. 内置名字
* _blank
* _top(顶级窗口，最上面的页面打开)
* _parent（当前所在iframe链接上一层打开）
* _self
2. 程序员命名
* window的name
* iframe的name
### 作用
* 跳转外部页面
* 跳转内部锚点
* 跳转到邮箱或电话

### 打开页面的两种方式   注意：不要用双击打开页面，要用HTTP打开，一定要养成习惯
运行yarn global add http-server  等待其安装好。
安装好之后运行http-server . -c-1   （c是缓存的意思，-1不要缓存）
然后会出现对应的IP地址，复制地址可以在浏览其中打开

## img标签的用法
### 作用：发出get请求，展示一张图片
### 属性
* alt(图片加载失败时用来提示用的)
* width，height  （只写width时，heigth会自适应）
### 事件
onload/onerror
### 响应式
max-widtn:100%

## table标签的用法
* 相关标签：table,thead,tbody,tfoot,tr,td,th
* 相关样式：table_layout,border-collapse(控制border是否合并),border-spacing（控制border之间的距离）

## form标签
* 作用：发get或post请求，然后刷新页面
* 属性:action/autocomplete(自动填充)/method/target
* 事件：submit

<input type="submit">和<button type="submit">的区别：input中不能再有内容，button中还可以有标签

## input标签
* 作用：让用户输入内容
* 属性：类型type：button/checkbox（多选）/Email/file/hidden/number/password/radio（单选）/serch/submit/tel/text;其他name/autofocus/checked/disabled/maxlength/pattern/value/placehoider
* 事件：onchange/onfocus/onblur
* 验证器:HTML5 新增功能

