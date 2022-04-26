HTML标签

```html
<head></head>
	<title></title>
<body></body>	
	<p>这是一个段落</p>
	<p>另一个段落</p>
	<a href="https://www.runoob.com">这是一个链接</a>  链接 在href属性中指定链接的地址。
<img src="" alt="" title="" width="" height="">  图片标签
src为图片的路径
alt属性必须加，用来对图片的简单介绍有利于SEO的优化。
title属性为鼠标悬停时显示的文本。
width和height为宽度和高度，如果只设置了其中一个，另一个没设置的会自动等比例缩放。如果同时设置了两个，若设置不当此时图片可能会变形
```

```html
<p>这是一个段落。</p>
<hr>
<p>这是一个段落。</p>
<hr>
<p>这是一个段落。</p>
<hr>元素可以用于分隔内容
```

```html
<br>换行标签
<hr>水平分割线 
```

添加注释快捷键

```html
ctrl + /
```

```html
<strong></strong> 加粗 <b></b>
<ins></ins>下划线 <u></u>
<em></em>倾斜 <i></i>
<del></del>删除线 <s></s>
```

```html
同级相对路径
文件名+后缀 或者 ./文件名+后缀
下级目录
文件夹名/+文件名+后缀
上级目录
返回上一级：../文件夹/文件名+后缀
```

```html
音频标签 MP3 Wav
<audio src="路径"></audio>
controls 显示播放的控件
autoplay 自动播放（部分浏览器不支持）
loop 循环播放
```

```html
视频标签 MP4 WebM Ogg
<video></video>
<video src="路径"></video>
controls 显示播放的控件
autoplay 自动播放（谷歌浏览器中配合muted实现静音播放）
loop 循环播放
```

```html
<a href="跳转地址">文字</a>
target属性 _self 默认值，在当前窗口中跳转（覆盖原网页）
           _blank 在新窗口中跳转（保留原网页）
```

```html
列表标签
没有顺序：无序列表
有顺序：有序列表
标题+内容：自定义列表
```

```html
无序标签
<ul>
    <li></li>
</ul>
ul标签中只允许包含li标签
li标签可以包含任何内容
显示特点：列表每一项前默认显示圆点标识
```

```html
有序列表
<ol>
    <li></li>
</ol>
ol标签中只允许包含li标签
li标签可以包含任何内容
显示特点：列表每一项前默认显示数字标识
```

```html
自定义列表标签
<dl>
    <dt></dt>
    <dd></dd>
</dl>
dl表示自定义列表的整体，用于包裹dt/dd标签，只允许包含dt/dd标签
dt表示自定义列表的主题
dd表示自定义列表的针对主题的每一项内容
dt/dd标签可以包含任意内容
```

```html
表格标签
<table>
    <tr>
        <td></td>
    </tr>
</table>
table表格整体，可用于包裹多个tr
tr表示表格每行，可用于包裹td
td表格单元格，可用于包裹内容
嵌套关系：table>tr>td
属性：
border边框宽度
width 表格宽度
height 表格高度
```

```html
表格标题和表头单元格标签
caption 表格大标题，整体大标题，顶部居中显示
th 表头单元格 通常表格第一行，默认加粗并且居中显示
caption标签写在table标签内部
th标签写在tr标签内部（用于替换td标签）
```



