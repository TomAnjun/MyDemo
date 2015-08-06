<html>
<head>
  <title>Evernote Export</title>
  <basefont face="微软雅黑" size="2" />
  <meta http-equiv="Content-Type" content="text/html;charset=utf-8" />
  <meta name="exporter-version" content="Evernote Windows/276352; Windows/6.3.9600 (Win64);"/>
  <meta name="content-class" content="maxiang"/>
  <style>
    body, td {
      font-family: 微软雅黑;
      font-size: 10pt;
    }
  </style>
</head>
<body>
<a name="304"/>

<div><span lang="v2" style="color: #2c3f51; line-height: 1.6;"><del style="position:relative;display:block"><a href="http://www.maxiang.info/#/?provider=evernote&amp;guid=b6a239ba-dfe1-46d6-a815-3866f1cfc1ea&amp;notebook=%E6%88%91%E7%9A%84%E7%AC%AC%E4%B8%80%E4%B8%AA%E7%AC%94%E8%AE%B0%E6%9C%AC" style="position: absolute;color: #FFF;text-decoration: none;font-size: 12px;height: 25px;border-radius: 0;margin-top: -20px;right: 15px;background: rgba(0, 0, 0, 0);border-left: 10px solid #BB3A34;border-right: 10px solid #BB3A34;border-bottom: 5px solid rgba(0, 0, 0, 0);width: 0;text-indent:-100000px;">Edit</a></del><div style="color: #2c3f51; line-height: 1.6;">
                        <div style="line-height: 1.6;"></div>
                    <div style="line-height: 1.6;">

</div><div style="line-height: 1.6;">

<h3 style="font-family: inherit; font-weight: bold; color: inherit; margin-top: 21px; margin-bottom: 10.5px; font-size: 1.7em; margin: 1.2em 0 .6em 0; text-align: start; line-height: 1.6;">css笔记</h3>

</div><div style="line-height: 1.6;">

<h4 style="font-family: inherit; font-weight: bold; color: inherit; margin-top: 10.5px; margin-bottom: 10.5px; font-size: 1.25em; margin: 1.2em 0 .6em 0; text-align: start; line-height: 1.6;">css</h4>

</div><div style="line-height: 1.6;">

<h5 style="font-family: inherit; font-weight: bold; color: inherit; margin-top: 10.5px; margin-bottom: 10.5px; font-size: 1em; margin: 1.2em 0 .6em 0; text-align: start; line-height: 1.6;">1.  css简述 css的作用是用于网页的美化，它在html中有三种调用方式。</h5>

<p style="margin: 0 0 1.1em; line-height: 1.6;">分别是：（1）行内引用 （2）标签中引用 （3）外部引入方式 个人建议最好还是外部引入，这对于以后的管理和维护很有作用。 <br/>
行内方式引入 所谓行内引入，是指在具体的标签后面直接加上css样式。 <br/>
这样可能看起来比较直观，但是代码的美观性和可读性都大大降低。个人不建议使用。 <br/>
头部方式引入头部引入就是把所有的css代码放在<code style="font-family: 'Source Code Pro',monospace; font-size: .9em; padding: 2px 4px; color: #c7254e; background-color: #f9f2f4; white-space: normal; border-radius: 4px;">&lt;style&gt;</code>标签里面，这样可以增强代码的维护工作。</p>

</div><div style="line-height: 1.6;">

<h5 style="font-family: inherit; font-weight: bold; color: inherit; margin-top: 10.5px; margin-bottom: 10.5px; font-size: 1em; margin: 1.2em 0 .6em 0; text-align: start; line-height: 1.6;">以外部文件方式引入其实，这种方法跟第二种类似，只是该方式把css代码单独放在一个文件夹里，方便团队开发。</h5>

</div><div style="line-height: 1.6;">

<h5 style="font-family: inherit; font-weight: bold; color: inherit; margin-top: 10.5px; margin-bottom: 10.5px; font-size: 1em; margin: 1.2em 0 .6em 0; text-align: start; line-height: 1.6;">2. css改变字体的样式</h5>

<p style="margin: 0 0 1.1em; line-height: 1.6;">css可以改变字体的属性常用的有：字体类型，字体的大小 ，字体的风格。</p>

</div><div style="line-height: 1.6;">

<h5 style="font-family: inherit; font-weight: bold; color: inherit; margin-top: 10.5px; margin-bottom: 10.5px; font-size: 1em; margin: 1.2em 0 .6em 0; text-align: start; line-height: 1.6;">3. css改变文本的样式</h5>

<p style="margin: 0 0 1.1em; line-height: 1.6;">css对文本的颜色，字间距，对齐方式等等都可以进行设置。具体怎么去设置，别问我。</p>

</div><div style="line-height: 1.6;">

<h5 style="font-family: inherit; font-weight: bold; color: inherit; margin-top: 10.5px; margin-bottom: 10.5px; font-size: 1em; margin: 1.2em 0 .6em 0; text-align: start; line-height: 1.6;">4. css改变背景</h5>

<p style="margin: 0 0 1.1em; line-height: 1.6;">小伙伴们是不是觉得页面的颜色会很难看。没关系，css可以设置的。有了css可以改成我们自己想要的颜色或者自己喜欢的图片。</p>

</div><div style="line-height: 1.6;">

<h5 style="font-family: inherit; font-weight: bold; color: inherit; margin-top: 10.5px; margin-bottom: 10.5px; font-size: 1em; margin: 1.2em 0 .6em 0; text-align: start; line-height: 1.6;">5. css改变列表的样式</h5>

<p style="margin: 0 0 1.1em; line-height: 1.6;">什么叫列表，这你能不动啊。通过css我们可以去设置我们自己看不惯的列表，其中包括去改变列表的风格啊，列表的显示位置，或者你也可以设置为自己喜欢的图片。其中，常用的列表的风格有：circle（空心小圆点），disc（实心小圆点）等等。 <br/>
哥们儿，别忘了。列表包括有序列表和无序列表两种。css都可以对其进行设置的。</p>

</div><div style="line-height: 1.6;">

<h5 style="font-family: inherit; font-weight: bold; color: inherit; margin-top: 10.5px; margin-bottom: 10.5px; font-size: 1em; margin: 1.2em 0 .6em 0; text-align: start; line-height: 1.6;">6. css改变边框样式</h5>

<p style="margin: 0 0 1.1em; line-height: 1.6;">网页要做的很好看，必须有很好看的边框吧。css可以对边框进行设置，可以对边框的样式，边框的颜色，边框的宽度等等都可以设置。还有，可以把边框设置成圆角的哦，<code style="font-family: 'Source Code Pro',monospace; font-size: .9em; padding: 2px 4px; color: #c7254e; background-color: #f9f2f4; white-space: normal; border-radius: 4px;">border-radius</code>这个属性设置，让你的边框雨中不同。</p>

</div><div style="line-height: 1.6;">

<h5 style="font-family: inherit; font-weight: bold; color: inherit; margin-top: 10.5px; margin-bottom: 10.5px; font-size: 1em; margin: 1.2em 0 .6em 0; text-align: start; line-height: 1.6;">7. css对div的设置</h5>

<p style="margin: 0 0 1.1em; line-height: 1.6;">css对div设置，可以设置它的<code style="font-family: 'Source Code Pro',monospace; font-size: .9em; padding: 2px 4px; color: #c7254e; background-color: #f9f2f4; white-space: normal; border-radius: 4px;">width</code>（宽度），<code style="font-family: 'Source Code Pro',monospace; font-size: .9em; padding: 2px 4px; color: #c7254e; background-color: #f9f2f4; white-space: normal; border-radius: 4px;">height</code>（高度），background-color（背景色）等设置。 <br/>
对于div，可以设置浮动方式，包括左浮动和右浮动。可能有时候浮动会带来不便，想要清除浮动就用<code style="font-family: 'Source Code Pro',monospace; font-size: .9em; padding: 2px 4px; color: #c7254e; background-color: #f9f2f4; white-space: normal; border-radius: 4px;">clear</code>去清除相应的浮动。</p>

</div><div style="line-height: 1.6;">

<h5 style="font-family: inherit; font-weight: bold; color: inherit; margin-top: 10.5px; margin-bottom: 10.5px; font-size: 1em; margin: 1.2em 0 .6em 0; text-align: start; line-height: 1.6;">8. css对超链接的设置</h5>

<p style="margin: 0 0 1.1em; line-height: 1.6;">超链接就是网页的灵魂，所以学习一下css对超链接的设置，可以让你做出更好的网页。超链接的属性包括：a:link(没被点击)，a:visited（被点击过），a:hover(鼠标经过)，a：active（被点击的时候）。分别可以对这四种状态设置相应的属性值。</p>

</div><div style="line-height: 1.6;">

<h5 style="font-family: inherit; font-weight: bold; color: inherit; margin-top: 10.5px; margin-bottom: 10.5px; font-size: 1em; margin: 1.2em 0 .6em 0; text-align: start; line-height: 1.6;">9. css的选择器</h5>

<p style="margin: 0 0 1.1em; line-height: 1.6;">说了这么多，必须得选择一个相应的元素吧。css中的选择器包括 <br/>
（1）id选择器：css可以通过不同的id对标签进行相应的设置 <br/>
（2）类选择器：css也可以通过类名对标签进行设置 <br/>
（3）标签选择器：css可以直接用标签去设置</p>

<p style="margin: 0 0 1.1em; line-height: 1.6;">id选择器和类选择器的区别： <br/>
（1）类选择器使用.类名进行选择，而id选择器使用#id名进行选择 <br/>
（2）类选择器的类名可以有很多重名，而id选择器的id必须唯一</p>

<hr style="-moz-box-sizing: content-box; box-sizing: content-box; height: 0; margin-top: 21px; margin-bottom: 21px; border: 0; border-top: 1px solid rgba(102,128,153,0.1); margin: 2em 0; line-height: 1.6;"/>

</div><div style="line-height: 1.6;">

<h4 style="font-family: inherit; font-weight: bold; color: inherit; margin-top: 10.5px; margin-bottom: 10.5px; font-size: 1.25em; margin: 1.2em 0 .6em 0; text-align: start; line-height: 1.6;">一些基本的概念</h4>

</div><div style="line-height: 1.6;">

<h5 style="font-family: inherit; font-weight: bold; color: inherit; margin-top: 10.5px; margin-bottom: 10.5px; font-size: 1em; margin: 1.2em 0 .6em 0; text-align: start; line-height: 1.6;">1. 正常流</h5>

<p style="margin: 0 0 1.1em; line-height: 1.6;">所谓正常流就是从上到下，从左到右的布局方式</p>

</div><div style="line-height: 1.6;">

<h5 style="font-family: inherit; font-weight: bold; color: inherit; margin-top: 10.5px; margin-bottom: 10.5px; font-size: 1em; margin: 1.2em 0 .6em 0; text-align: start; line-height: 1.6;">2. 替换元素和非替换元素</h5>

<p style="margin: 0 0 1.1em; line-height: 1.6;">（1）替换元素是要根据标签的内容和属性去选择不同的内容的元素 <br/>
（2）非替换元素就是内容直接显示到显示器的标签元素</p>

</div><div style="line-height: 1.6;">

<h5 style="font-family: inherit; font-weight: bold; color: inherit; margin-top: 10.5px; margin-bottom: 10.5px; font-size: 1em; margin: 1.2em 0 .6em 0; text-align: start; line-height: 1.6;">3. 行内元素</h5>

<p style="margin: 0 0 1.1em; line-height: 1.6;">行内元素就是在元素的前后不会出现换行。像<code style="font-family: 'Source Code Pro',monospace; font-size: .9em; padding: 2px 4px; color: #c7254e; background-color: #f9f2f4; white-space: normal; border-radius: 4px;">&lt;strong&gt;``````span</code>等。</p>

<hr style="-moz-box-sizing: content-box; box-sizing: content-box; height: 0; margin-top: 21px; margin-bottom: 21px; border: 0; border-top: 1px solid rgba(102,128,153,0.1); margin: 2em 0; line-height: 1.6;"/>

</div><div style="line-height: 1.6;">

<h4 style="font-family: inherit; font-weight: bold; color: inherit; margin-top: 10.5px; margin-bottom: 10.5px; font-size: 1.25em; margin: 1.2em 0 .6em 0; text-align: start; line-height: 1.6;">单位</h4>

</div><div style="line-height: 1.6;">

<h5 style="font-family: inherit; font-weight: bold; color: inherit; margin-top: 10.5px; margin-bottom: 10.5px; font-size: 1em; margin: 1.2em 0 .6em 0; text-align: start; line-height: 1.6;">1. em</h5>

<p style="margin: 0 0 1.1em; line-height: 1.6;">在Css中1em是等同于字体中font-size设置的像素大小，假如一段字体大小是24px,左边距为1em，那么它的左边距合像素就是24px。</p>

</div><div style="line-height: 1.6;">

<h5 style="font-family: inherit; font-weight: bold; color: inherit; margin-top: 10.5px; margin-bottom: 10.5px; font-size: 1em; margin: 1.2em 0 .6em 0; text-align: start; line-height: 1.6;">2. ex</h5>

<p style="margin: 0 0 1.1em; line-height: 1.6;">在规范中ex是指现在所用的字体下小写的x的高度，但大多数浏览器的实现都是作为0.5em进行计算的，正因为如此现在为止ex也很少使用</p>

</div><div style="line-height: 1.6;">

<h5 style="font-family: inherit; font-weight: bold; color: inherit; margin-top: 10.5px; margin-bottom: 10.5px; font-size: 1em; margin: 1.2em 0 .6em 0; text-align: start; line-height: 1.6;">3. px</h5>

<p style="margin: 0 0 1.1em; line-height: 1.6;">目前大多数浏览器中采用96ppi(ppi即每英尺像素数)作为参考像素，但是一般Web浏览器都会使用显示器上使用的实际像素。</p>

<p style="margin: 0 0 1.1em; line-height: 1.6;">另外之所以将px作为相对单位定义，是因为在不同的设备(如打印机)，用户代理会将像素缩放为合理的度量</p>

<hr style="-moz-box-sizing: content-box; box-sizing: content-box; height: 0; margin-top: 21px; margin-bottom: 21px; border: 0; border-top: 1px solid rgba(102,128,153,0.1); margin: 2em 0; line-height: 1.6;"/>

</div><div style="line-height: 1.6;">

<h4 style="font-family: inherit; font-weight: bold; color: inherit; margin-top: 10.5px; margin-bottom: 10.5px; font-size: 1.25em; margin: 1.2em 0 .6em 0; text-align: start; line-height: 1.6;">盒子模型</h4>

<p style="margin: 0 0 1.1em; line-height: 1.6;">盒子模型，即可以把网页中的每个元素看成是盒子的内容。而盒子就需要包装，所以就会有相应的外边距，内边距，边框，内容</p>

</div><div style="line-height: 1.6;">

<h5 style="font-family: inherit; font-weight: bold; color: inherit; margin-top: 10.5px; margin-bottom: 10.5px; font-size: 1em; margin: 1.2em 0 .6em 0; text-align: start; line-height: 1.6;">1. 外边距和内边距的不同</h5>

<p style="margin: 0 0 1.1em; line-height: 1.6;">外边距不会被背景的图片填充，而内边距就会被背景图片或背景颜色填充</p>

</div><div style="line-height: 1.6;">

<h5 style="font-family: inherit; font-weight: bold; color: inherit; margin-top: 10.5px; margin-bottom: 10.5px; font-size: 1em; margin: 1.2em 0 .6em 0; text-align: start; line-height: 1.6;">2. 用百分数去设置宽时注意事项</h5>

<p style="margin: 0 0 1.1em; line-height: 1.6;">边距（包括外边距和内边距）的值可以用百分数表示，这里要注意这个百分比是相对于父元素的width进行计算的，而不是浏览器窗体。 <br/>
这里左右边距采用父元素百分比计算是没有疑问的，但是要注意上下边距的百分比值也是相对父元素的宽度定义的。 <br/>
总之就是一句话，就是以父级元素的宽作为标准。</p>

<hr style="-moz-box-sizing: content-box; box-sizing: content-box; height: 0; margin-top: 21px; margin-bottom: 21px; border: 0; border-top: 1px solid rgba(102,128,153,0.1); margin: 2em 0; line-height: 1.6;"/>

</div><div style="line-height: 1.6;">

<h4 style="font-family: inherit; font-weight: bold; color: inherit; margin-top: 10.5px; margin-bottom: 10.5px; font-size: 1.25em; margin: 1.2em 0 .6em 0; text-align: start; line-height: 1.6;">浮动和定位</h4>

</div><div style="line-height: 1.6;">

<h5 style="font-family: inherit; font-weight: bold; color: inherit; margin-top: 10.5px; margin-bottom: 10.5px; font-size: 1em; margin: 1.2em 0 .6em 0; text-align: start; line-height: 1.6;">1. 浮动</h5>

<p style="margin: 0 0 1.1em; line-height: 1.6;">（1）浮动分为左浮动和右浮动。默认为不浮动。 <br/>
（2）浮动元素不能相互覆盖，也不能超出其包含块的范围 <br/>
（3）行级元素与浮动元素重合，其边框，背景色和内容都在浮动元素之上；而块级元素则会被遮盖。</p>

</div><div style="line-height: 1.6;">

<h5 style="font-family: inherit; font-weight: bold; color: inherit; margin-top: 10.5px; margin-bottom: 10.5px; font-size: 1em; margin: 1.2em 0 .6em 0; text-align: start; line-height: 1.6;">2. 定位</h5>

<p style="margin: 0 0 1.1em; line-height: 1.6;">（1）定位类型：static（静态类型），relative（相对定位），absolue（绝对定位），fixed（固定定位） <br/>
（2）static定位时，你设置的偏移值不会有作用。 <br/>
（3）absolute定位时，元素会从文档流中删除，所以可能会覆盖其他元素 <br/>
（4）包含快宽的算法： <br/>
<code style="font-family: 'Source Code Pro',monospace; font-size: .9em; padding: 2px 4px; color: #c7254e; background-color: #f9f2f4; white-space: normal; border-radius: 4px;">包含块的宽=元素左偏移+元素左外边距+元素左边框宽+元素左内边距+元素宽+元素右内边距+元素右边框宽+元素右外边距+元素右偏移</code> <br/>
（5）固定定位，固定定位包含块是视窗，记住这点就行。 <br/>
（6）<code style="font-family: 'Source Code Pro',monospace; font-size: .9em; padding: 2px 4px; color: #c7254e; background-color: #f9f2f4; white-space: normal; border-radius: 4px;">z-index</code>:<code style="font-family: 'Source Code Pro',monospace; font-size: .9em; padding: 2px 4px; color: #c7254e; background-color: #f9f2f4; white-space: normal; border-radius: 4px;">z-index</code>:用于区分元素的重叠情况，其值越大表示离用户越近。 <br/>
这里要注意元素的后代元素所定义的z-index是相对于该元素而言的，而不是初始包含块</p>

<hr style="-moz-box-sizing: content-box; box-sizing: content-box; height: 0; margin-top: 21px; margin-bottom: 21px; border: 0; border-top: 1px solid rgba(102,128,153,0.1); margin: 2em 0; line-height: 1.6;"/>

</div><div style="line-height: 1.6;">

<h5 style="font-family: inherit; font-weight: bold; color: inherit; margin-top: 10.5px; margin-bottom: 10.5px; font-size: 1em; margin: 1.2em 0 .6em 0; text-align: start; line-height: 1.6;">作业1.get和post的差异？</h5>

<p style="margin: 0 0 1.1em; line-height: 1.6;">（1）get是从服务器上获取数据，post是向服务器传送数据。 <br/>
get是把参数数据队列加到提交表单的ACTION属性所指的URL中，值和表单内各个字段一一对应，在URL中可以看到。post是通过HTTP post机制，将表单内各个字段与其内容放置在HTML HEADER内一起传送到ACTION属性所指的URL地址。用户看不到这个过程。 <br/>
（2）对于get方式，服务器端用Request.QueryString获取变量的值，对于post方式，服务器端用Request.Form获取提交的数据。 <br/>
（3）get传送的数据量较小，不能大于2KB。post传送的数据量较大，一般被默认为不受限制。但理论上，IIS4中最大量为80KB，IIS5中为100KB。 <br/>
（4）get安全性非常低，post安全性较高。</p>

</div><div style="line-height: 1.6;">

<h5 style="font-family: inherit; font-weight: bold; color: inherit; margin-top: 10.5px; margin-bottom: 10.5px; font-size: 1em; margin: 1.2em 0 .6em 0; text-align: start; line-height: 1.6;">一些延伸知识</h5>

<p style="margin: 0 0 1.1em; line-height: 1.6;">HTTP 定义了与服务器交互的不同方法，最基本的方法是 GET 和 POST。事实上 GET 适用于多数请求，而保留 POST 仅用于更新站点。根据 HTTP 规范，GET 用于信息获取，而且应该是 安全的和幂等的。所谓安全的意味着该操作用于获取信息而非修改信息。换句话说，GET 请求一般不应产生副作用。幂等的意味着对同一 URL 的多个请求应该返回同样的结果。完整的定义并不像看起来那样严格。从根本上讲，其目标是当用户打开一个链接时，她可以确信从自身的角度来看没有改变资源。 比如，新闻站点的头版不断更新。虽然第二次请求会返回不同的一批新闻，该操作仍然被认为是安全的和幂等的，因为它总是返回当前的新闻。反之亦然。POST 请求就不那么轻松了。POST 表示可能改变服务器上的资源的请求。仍然以新闻站点为例，读者对文章的注解应该通过 POST 请求实现，因为在注解提交之后站点已经不同了 <br/>
7 <br/>
在FORM提交的时候，如果不指定Method，则默认为GET请求，Form中提交的数据将会附加在url之后，以?分开与url分开。字母数字字符原 样发送，但空格转换为“+“号，其它符号转换为%XX,其中XX为该符号以16进制表示的ASCII（或ISO Latin-1）值。GET请求请提交的数据放置在HTTP请求协议头中，而POST提交的数据则放在实体数据中；GET方式提交的数据最多只能有1024字节，而POST则没有此限制。</p>

</div><div style="line-height: 1.6;">

<h5 style="font-family: inherit; font-weight: bold; color: inherit; margin-top: 10.5px; margin-bottom: 10.5px; font-size: 1em; margin: 1.2em 0 .6em 0; text-align: start; line-height: 1.6;">相应报文状态码</h5>

<ol style="margin-top: 0; margin-bottom: 1.1em; line-height: 1.6;"><li style="line-height: 1.6;"><p style="margin: 0 0 1.1em; line-height: 1.6;">状态吗说明：</p>

<hr style="-moz-box-sizing: content-box; box-sizing: content-box; height: 0; margin-top: 21px; margin-bottom: 21px; border: 0; border-top: 1px solid rgba(102,128,153,0.1); margin: 2em 0; line-height: 1.6;"/>

<p style="margin: 0 0 1.1em; line-height: 1.6;">1xx 服务端接收到请求，但仍在处理中并没有完成。 <br/>
2xx：服务器成功处理请求。 <br/>
3xx：请求处理完成，但客户端需要从其他位置获取资源 <br/>
4xx：客户端错误 <br/>
5xx：服务器错误</p>

<hr style="-moz-box-sizing: content-box; box-sizing: content-box; height: 0; margin-top: 21px; margin-bottom: 21px; border: 0; border-top: 1px solid rgba(102,128,153,0.1); margin: 2em 0; line-height: 1.6;"/></li>
<li style="line-height: 1.6;"><p style="margin: 0 0 1.1em; line-height: 1.6;">常见状态码</p>

<hr style="-moz-box-sizing: content-box; box-sizing: content-box; height: 0; margin-top: 21px; margin-bottom: 21px; border: 0; border-top: 1px solid rgba(102,128,153,0.1); margin: 2em 0; line-height: 1.6;"/></li>
</ol>

<p style="margin: 0 0 1.1em; line-height: 1.6;">200 请求成功 <br/>
301 永久重定向 <br/>
302 临时重定向 <br/>
303 重定向 <br/>
304 从缓存读取 <br/>
401 未授权 <br/>
404 资源不存在 <br/>
500 服务器错误 <br/>
503 服务不可用</p></div><div style="line-height: 1.6;"></div></div><center style="display:none">%23%23%23css%u7B14%u8BB0%0A%23%23%23%23css%0A%23%23%23%23%231.%20%20css%u7B80%u8FF0%20css%u7684%u4F5C%u7528%u662F%u7528%u4E8E%u7F51%u9875%u7684%u7F8E%u5316%uFF0C%u5B83%u5728html%u4E2D%u6709%u4E09%u79CD%u8C03%u7528%u65B9%u5F0F%u3002%0A%u5206%u522B%u662F%uFF1A%uFF081%uFF09%u884C%u5185%u5F15%u7528%20%uFF082%uFF09%3Chead%3E%u6807%u7B7E%u4E2D%u5F15%u7528%20%uFF083%uFF09%u5916%u90E8%u5F15%u5165%u65B9%u5F0F%20%u4E2A%u4EBA%u5EFA%u8BAE%u6700%u597D%u8FD8%u662F%u5916%u90E8%u5F15%u5165%uFF0C%u8FD9%u5BF9%u4E8E%u4EE5%u540E%u7684%u7BA1%u7406%u548C%u7EF4%u62A4%u5F88%u6709%u4F5C%u7528%u3002%0A%u884C%u5185%u65B9%u5F0F%u5F15%u5165%20%u6240%u8C13%u884C%u5185%u5F15%u5165%uFF0C%u662F%u6307%u5728%u5177%u4F53%u7684%u6807%u7B7E%u540E%u9762%u76F4%u63A5%u52A0%u4E0Acss%u6837%u5F0F%u3002%0A%u8FD9%u6837%u53EF%u80FD%u770B%u8D77%u6765%u6BD4%u8F83%u76F4%u89C2%uFF0C%u4F46%u662F%u4EE3%u7801%u7684%u7F8E%u89C2%u6027%u548C%u53EF%u8BFB%u6027%u90FD%u5927%u5927%u964D%u4F4E%u3002%u4E2A%u4EBA%u4E0D%u5EFA%u8BAE%u4F7F%u7528%u3002%0A%u5934%u90E8%u65B9%u5F0F%u5F15%u5165%u5934%u90E8%u5F15%u5165%u5C31%u662F%u628A%u6240%u6709%u7684css%u4EE3%u7801%u653E%u5728%60%60%60%3Cstyle%3E%60%60%60%u6807%u7B7E%u91CC%u9762%uFF0C%u8FD9%u6837%u53EF%u4EE5%u589E%u5F3A%u4EE3%u7801%u7684%u7EF4%u62A4%u5DE5%u4F5C%u3002%0A%23%23%23%23%23%u4EE5%u5916%u90E8%u6587%u4EF6%u65B9%u5F0F%u5F15%u5165%u5176%u5B9E%uFF0C%u8FD9%u79CD%u65B9%u6CD5%u8DDF%u7B2C%u4E8C%u79CD%u7C7B%u4F3C%uFF0C%u53EA%u662F%u8BE5%u65B9%u5F0F%u628Acss%u4EE3%u7801%u5355%u72EC%u653E%u5728%u4E00%u4E2A%u6587%u4EF6%u5939%u91CC%uFF0C%u65B9%u4FBF%u56E2%u961F%u5F00%u53D1%u3002%0A%23%23%23%23%232.%20css%u6539%u53D8%u5B57%u4F53%u7684%u6837%u5F0F%0Acss%u53EF%u4EE5%u6539%u53D8%u5B57%u4F53%u7684%u5C5E%u6027%u5E38%u7528%u7684%u6709%uFF1A%u5B57%u4F53%u7C7B%u578B%uFF0C%u5B57%u4F53%u7684%u5927%u5C0F%20%uFF0C%u5B57%u4F53%u7684%u98CE%u683C%u3002%0A%23%23%23%23%233.%20css%u6539%u53D8%u6587%u672C%u7684%u6837%u5F0F%0Acss%u5BF9%u6587%u672C%u7684%u989C%u8272%uFF0C%u5B57%u95F4%u8DDD%uFF0C%u5BF9%u9F50%u65B9%u5F0F%u7B49%u7B49%u90FD%u53EF%u4EE5%u8FDB%u884C%u8BBE%u7F6E%u3002%u5177%u4F53%u600E%u4E48%u53BB%u8BBE%u7F6E%uFF0C%u522B%u95EE%u6211%u3002%0A%23%23%23%23%234.%20css%u6539%u53D8%u80CC%u666F%0A%u5C0F%u4F19%u4F34%u4EEC%u662F%u4E0D%u662F%u89C9%u5F97%u9875%u9762%u7684%u989C%u8272%u4F1A%u5F88%u96BE%u770B%u3002%u6CA1%u5173%u7CFB%uFF0Ccss%u53EF%u4EE5%u8BBE%u7F6E%u7684%u3002%u6709%u4E86css%u53EF%u4EE5%u6539%u6210%u6211%u4EEC%u81EA%u5DF1%u60F3%u8981%u7684%u989C%u8272%u6216%u8005%u81EA%u5DF1%u559C%u6B22%u7684%u56FE%u7247%u3002%0A%23%23%23%23%235.%20css%u6539%u53D8%u5217%u8868%u7684%u6837%u5F0F%0A%u4EC0%u4E48%u53EB%u5217%u8868%uFF0C%u8FD9%u4F60%u80FD%u4E0D%u52A8%u554A%u3002%u901A%u8FC7css%u6211%u4EEC%u53EF%u4EE5%u53BB%u8BBE%u7F6E%u6211%u4EEC%u81EA%u5DF1%u770B%u4E0D%u60EF%u7684%u5217%u8868%uFF0C%u5176%u4E2D%u5305%u62EC%u53BB%u6539%u53D8%u5217%u8868%u7684%u98CE%u683C%u554A%uFF0C%u5217%u8868%u7684%u663E%u793A%u4F4D%u7F6E%uFF0C%u6216%u8005%u4F60%u4E5F%u53EF%u4EE5%u8BBE%u7F6E%u4E3A%u81EA%u5DF1%u559C%u6B22%u7684%u56FE%u7247%u3002%u5176%u4E2D%uFF0C%u5E38%u7528%u7684%u5217%u8868%u7684%u98CE%u683C%u6709%uFF1Acircle%uFF08%u7A7A%u5FC3%u5C0F%u5706%u70B9%uFF09%uFF0Cdisc%uFF08%u5B9E%u5FC3%u5C0F%u5706%u70B9%uFF09%u7B49%u7B49%u3002%0A%u54E5%u4EEC%u513F%uFF0C%u522B%u5FD8%u4E86%u3002%u5217%u8868%u5305%u62EC%u6709%u5E8F%u5217%u8868%u548C%u65E0%u5E8F%u5217%u8868%u4E24%u79CD%u3002css%u90FD%u53EF%u4EE5%u5BF9%u5176%u8FDB%u884C%u8BBE%u7F6E%u7684%u3002%0A%23%23%23%23%236.%20css%u6539%u53D8%u8FB9%u6846%u6837%u5F0F%0A%u7F51%u9875%u8981%u505A%u7684%u5F88%u597D%u770B%uFF0C%u5FC5%u987B%u6709%u5F88%u597D%u770B%u7684%u8FB9%u6846%u5427%u3002css%u53EF%u4EE5%u5BF9%u8FB9%u6846%u8FDB%u884C%u8BBE%u7F6E%uFF0C%u53EF%u4EE5%u5BF9%u8FB9%u6846%u7684%u6837%u5F0F%uFF0C%u8FB9%u6846%u7684%u989C%u8272%uFF0C%u8FB9%u6846%u7684%u5BBD%u5EA6%u7B49%u7B49%u90FD%u53EF%u4EE5%u8BBE%u7F6E%u3002%u8FD8%u6709%uFF0C%u53EF%u4EE5%u628A%u8FB9%u6846%u8BBE%u7F6E%u6210%u5706%u89D2%u7684%u54E6%uFF0C%60%60%60border-radius%60%60%60%u8FD9%u4E2A%u5C5E%u6027%u8BBE%u7F6E%uFF0C%u8BA9%u4F60%u7684%u8FB9%u6846%u96E8%u4E2D%u4E0D%u540C%u3002%0A%23%23%23%23%237.%20css%u5BF9div%u7684%u8BBE%u7F6E%0Acss%u5BF9div%u8BBE%u7F6E%uFF0C%u53EF%u4EE5%u8BBE%u7F6E%u5B83%u7684%60%60%60width%60%60%60%uFF08%u5BBD%u5EA6%uFF09%uFF0C%60%60%60height%60%60%60%uFF08%u9AD8%u5EA6%uFF09%uFF0Cbackground-color%uFF08%u80CC%u666F%u8272%uFF09%u7B49%u8BBE%u7F6E%u3002%0A%u5BF9%u4E8Ediv%uFF0C%u53EF%u4EE5%u8BBE%u7F6E%u6D6E%u52A8%u65B9%u5F0F%uFF0C%u5305%u62EC%u5DE6%u6D6E%u52A8%u548C%u53F3%u6D6E%u52A8%u3002%u53EF%u80FD%u6709%u65F6%u5019%u6D6E%u52A8%u4F1A%u5E26%u6765%u4E0D%u4FBF%uFF0C%u60F3%u8981%u6E05%u9664%u6D6E%u52A8%u5C31%u7528%60%60%60clear%60%60%60%u53BB%u6E05%u9664%u76F8%u5E94%u7684%u6D6E%u52A8%u3002%0A%23%23%23%23%238.%20css%u5BF9%u8D85%u94FE%u63A5%u7684%u8BBE%u7F6E%0A%u8D85%u94FE%u63A5%u5C31%u662F%u7F51%u9875%u7684%u7075%u9B42%uFF0C%u6240%u4EE5%u5B66%u4E60%u4E00%u4E0Bcss%u5BF9%u8D85%u94FE%u63A5%u7684%u8BBE%u7F6E%uFF0C%u53EF%u4EE5%u8BA9%u4F60%u505A%u51FA%u66F4%u597D%u7684%u7F51%u9875%u3002%u8D85%u94FE%u63A5%u7684%u5C5E%u6027%u5305%u62EC%uFF1Aa%3Alink%28%u6CA1%u88AB%u70B9%u51FB%29%uFF0Ca%3Avisited%uFF08%u88AB%u70B9%u51FB%u8FC7%uFF09%uFF0Ca%3Ahover%28%u9F20%u6807%u7ECF%u8FC7%29%uFF0Ca%uFF1Aactive%uFF08%u88AB%u70B9%u51FB%u7684%u65F6%u5019%uFF09%u3002%u5206%u522B%u53EF%u4EE5%u5BF9%u8FD9%u56DB%u79CD%u72B6%u6001%u8BBE%u7F6E%u76F8%u5E94%u7684%u5C5E%u6027%u503C%u3002%0A%23%23%23%23%239.%20css%u7684%u9009%u62E9%u5668%0A%u8BF4%u4E86%u8FD9%u4E48%u591A%uFF0C%u5FC5%u987B%u5F97%u9009%u62E9%u4E00%u4E2A%u76F8%u5E94%u7684%u5143%u7D20%u5427%u3002css%u4E2D%u7684%u9009%u62E9%u5668%u5305%u62EC%0A%uFF081%uFF09id%u9009%u62E9%u5668%uFF1Acss%u53EF%u4EE5%u901A%u8FC7%u4E0D%u540C%u7684id%u5BF9%u6807%u7B7E%u8FDB%u884C%u76F8%u5E94%u7684%u8BBE%u7F6E%0A%uFF082%uFF09%u7C7B%u9009%u62E9%u5668%uFF1Acss%u4E5F%u53EF%u4EE5%u901A%u8FC7%u7C7B%u540D%u5BF9%u6807%u7B7E%u8FDB%u884C%u8BBE%u7F6E%0A%uFF083%uFF09%u6807%u7B7E%u9009%u62E9%u5668%uFF1Acss%u53EF%u4EE5%u76F4%u63A5%u7528%u6807%u7B7E%u53BB%u8BBE%u7F6E%0A%0Aid%u9009%u62E9%u5668%u548C%u7C7B%u9009%u62E9%u5668%u7684%u533A%u522B%uFF1A%0A%uFF081%uFF09%u7C7B%u9009%u62E9%u5668%u4F7F%u7528.%u7C7B%u540D%u8FDB%u884C%u9009%u62E9%uFF0C%u800Cid%u9009%u62E9%u5668%u4F7F%u7528%23id%u540D%u8FDB%u884C%u9009%u62E9%0A%uFF082%uFF09%u7C7B%u9009%u62E9%u5668%u7684%u7C7B%u540D%u53EF%u4EE5%u6709%u5F88%u591A%u91CD%u540D%uFF0C%u800Cid%u9009%u62E9%u5668%u7684id%u5FC5%u987B%u552F%u4E00%0A***%0A%23%23%23%23%u4E00%u4E9B%u57FA%u672C%u7684%u6982%u5FF5%0A%23%23%23%23%231.%20%u6B63%u5E38%u6D41%0A%u6240%u8C13%u6B63%u5E38%u6D41%u5C31%u662F%u4ECE%u4E0A%u5230%u4E0B%uFF0C%u4ECE%u5DE6%u5230%u53F3%u7684%u5E03%u5C40%u65B9%u5F0F%0A%23%23%23%23%232.%20%u66FF%u6362%u5143%u7D20%u548C%u975E%u66FF%u6362%u5143%u7D20%0A%uFF081%uFF09%u66FF%u6362%u5143%u7D20%u662F%u8981%u6839%u636E%u6807%u7B7E%u7684%u5185%u5BB9%u548C%u5C5E%u6027%u53BB%u9009%u62E9%u4E0D%u540C%u7684%u5185%u5BB9%u7684%u5143%u7D20%0A%uFF082%uFF09%u975E%u66FF%u6362%u5143%u7D20%u5C31%u662F%u5185%u5BB9%u76F4%u63A5%u663E%u793A%u5230%u663E%u793A%u5668%u7684%u6807%u7B7E%u5143%u7D20%0A%23%23%23%23%233.%20%u884C%u5185%u5143%u7D20%0A%u884C%u5185%u5143%u7D20%u5C31%u662F%u5728%u5143%u7D20%u7684%u524D%u540E%u4E0D%u4F1A%u51FA%u73B0%u6362%u884C%u3002%u50CF%60%60%60%3Cstrong%3E%60%60%60%60%60%60span%60%60%60%u7B49%u3002%0A***%0A%23%23%23%23%20%u5355%u4F4D%0A%23%23%23%23%231.%20em%0A%u5728Css%u4E2D1em%u662F%u7B49%u540C%u4E8E%u5B57%u4F53%u4E2Dfont-size%u8BBE%u7F6E%u7684%u50CF%u7D20%u5927%u5C0F%uFF0C%u5047%u5982%u4E00%u6BB5%u5B57%u4F53%u5927%u5C0F%u662F24px%2C%u5DE6%u8FB9%u8DDD%u4E3A1em%uFF0C%u90A3%u4E48%u5B83%u7684%u5DE6%u8FB9%u8DDD%u5408%u50CF%u7D20%u5C31%u662F24px%u3002%0A%23%23%23%23%232.%20ex%0A%u5728%u89C4%u8303%u4E2Dex%u662F%u6307%u73B0%u5728%u6240%u7528%u7684%u5B57%u4F53%u4E0B%u5C0F%u5199%u7684x%u7684%u9AD8%u5EA6%uFF0C%u4F46%u5927%u591A%u6570%u6D4F%u89C8%u5668%u7684%u5B9E%u73B0%u90FD%u662F%u4F5C%u4E3A0.5em%u8FDB%u884C%u8BA1%u7B97%u7684%uFF0C%u6B63%u56E0%u4E3A%u5982%u6B64%u73B0%u5728%u4E3A%u6B62ex%u4E5F%u5F88%u5C11%u4F7F%u7528%0A%23%23%23%23%233.%20px%0A%u76EE%u524D%u5927%u591A%u6570%u6D4F%u89C8%u5668%u4E2D%u91C7%u752896ppi%28ppi%u5373%u6BCF%u82F1%u5C3A%u50CF%u7D20%u6570%29%u4F5C%u4E3A%u53C2%u8003%u50CF%u7D20%uFF0C%u4F46%u662F%u4E00%u822CWeb%u6D4F%u89C8%u5668%u90FD%u4F1A%u4F7F%u7528%u663E%u793A%u5668%u4E0A%u4F7F%u7528%u7684%u5B9E%u9645%u50CF%u7D20%u3002%0A%0A%u53E6%u5916%u4E4B%u6240%u4EE5%u5C06px%u4F5C%u4E3A%u76F8%u5BF9%u5355%u4F4D%u5B9A%u4E49%uFF0C%u662F%u56E0%u4E3A%u5728%u4E0D%u540C%u7684%u8BBE%u5907%28%u5982%u6253%u5370%u673A%29%uFF0C%u7528%u6237%u4EE3%u7406%u4F1A%u5C06%u50CF%u7D20%u7F29%u653E%u4E3A%u5408%u7406%u7684%u5EA6%u91CF%0A***%0A%23%23%23%23%u76D2%u5B50%u6A21%u578B%0A%u76D2%u5B50%u6A21%u578B%uFF0C%u5373%u53EF%u4EE5%u628A%u7F51%u9875%u4E2D%u7684%u6BCF%u4E2A%u5143%u7D20%u770B%u6210%u662F%u76D2%u5B50%u7684%u5185%u5BB9%u3002%u800C%u76D2%u5B50%u5C31%u9700%u8981%u5305%u88C5%uFF0C%u6240%u4EE5%u5C31%u4F1A%u6709%u76F8%u5E94%u7684%u5916%u8FB9%u8DDD%uFF0C%u5185%u8FB9%u8DDD%uFF0C%u8FB9%u6846%uFF0C%u5185%u5BB9%0A%23%23%23%23%231.%20%u5916%u8FB9%u8DDD%u548C%u5185%u8FB9%u8DDD%u7684%u4E0D%u540C%0A%u5916%u8FB9%u8DDD%u4E0D%u4F1A%u88AB%u80CC%u666F%u7684%u56FE%u7247%u586B%u5145%uFF0C%u800C%u5185%u8FB9%u8DDD%u5C31%u4F1A%u88AB%u80CC%u666F%u56FE%u7247%u6216%u80CC%u666F%u989C%u8272%u586B%u5145%0A%23%23%23%23%232.%20%u7528%u767E%u5206%u6570%u53BB%u8BBE%u7F6E%u5BBD%u65F6%u6CE8%u610F%u4E8B%u9879%0A%u8FB9%u8DDD%uFF08%u5305%u62EC%u5916%u8FB9%u8DDD%u548C%u5185%u8FB9%u8DDD%uFF09%u7684%u503C%u53EF%u4EE5%u7528%u767E%u5206%u6570%u8868%u793A%uFF0C%u8FD9%u91CC%u8981%u6CE8%u610F%u8FD9%u4E2A%u767E%u5206%u6BD4%u662F%u76F8%u5BF9%u4E8E%u7236%u5143%u7D20%u7684width%u8FDB%u884C%u8BA1%u7B97%u7684%uFF0C%u800C%u4E0D%u662F%u6D4F%u89C8%u5668%u7A97%u4F53%u3002%0A%u8FD9%u91CC%u5DE6%u53F3%u8FB9%u8DDD%u91C7%u7528%u7236%u5143%u7D20%u767E%u5206%u6BD4%u8BA1%u7B97%u662F%u6CA1%u6709%u7591%u95EE%u7684%uFF0C%u4F46%u662F%u8981%u6CE8%u610F%u4E0A%u4E0B%u8FB9%u8DDD%u7684%u767E%u5206%u6BD4%u503C%u4E5F%u662F%u76F8%u5BF9%u7236%u5143%u7D20%u7684%u5BBD%u5EA6%u5B9A%u4E49%u7684%u3002%0A%u603B%u4E4B%u5C31%u662F%u4E00%u53E5%u8BDD%uFF0C%u5C31%u662F%u4EE5%u7236%u7EA7%u5143%u7D20%u7684%u5BBD%u4F5C%u4E3A%u6807%u51C6%u3002%0A***%0A%23%23%23%23%u6D6E%u52A8%u548C%u5B9A%u4F4D%0A%0A%23%23%23%23%231.%20%u6D6E%u52A8%0A%uFF081%uFF09%u6D6E%u52A8%u5206%u4E3A%u5DE6%u6D6E%u52A8%u548C%u53F3%u6D6E%u52A8%u3002%u9ED8%u8BA4%u4E3A%u4E0D%u6D6E%u52A8%u3002%0A%uFF082%uFF09%u6D6E%u52A8%u5143%u7D20%u4E0D%u80FD%u76F8%u4E92%u8986%u76D6%uFF0C%u4E5F%u4E0D%u80FD%u8D85%u51FA%u5176%u5305%u542B%u5757%u7684%u8303%u56F4%0A%uFF083%uFF09%u884C%u7EA7%u5143%u7D20%u4E0E%u6D6E%u52A8%u5143%u7D20%u91CD%u5408%uFF0C%u5176%u8FB9%u6846%uFF0C%u80CC%u666F%u8272%u548C%u5185%u5BB9%u90FD%u5728%u6D6E%u52A8%u5143%u7D20%u4E4B%u4E0A%uFF1B%u800C%u5757%u7EA7%u5143%u7D20%u5219%u4F1A%u88AB%u906E%u76D6%u3002%0A%23%23%23%23%232.%20%u5B9A%u4F4D%0A%uFF081%uFF09%u5B9A%u4F4D%u7C7B%u578B%uFF1Astatic%uFF08%u9759%u6001%u7C7B%u578B%uFF09%uFF0Crelative%uFF08%u76F8%u5BF9%u5B9A%u4F4D%uFF09%uFF0Cabsolue%uFF08%u7EDD%u5BF9%u5B9A%u4F4D%uFF09%uFF0Cfixed%uFF08%u56FA%u5B9A%u5B9A%u4F4D%uFF09%0A%uFF082%uFF09static%u5B9A%u4F4D%u65F6%uFF0C%u4F60%u8BBE%u7F6E%u7684%u504F%u79FB%u503C%u4E0D%u4F1A%u6709%u4F5C%u7528%u3002%0A%uFF083%uFF09absolute%u5B9A%u4F4D%u65F6%uFF0C%u5143%u7D20%u4F1A%u4ECE%u6587%u6863%u6D41%u4E2D%u5220%u9664%uFF0C%u6240%u4EE5%u53EF%u80FD%u4F1A%u8986%u76D6%u5176%u4ED6%u5143%u7D20%0A%uFF084%uFF09%u5305%u542B%u5FEB%u5BBD%u7684%u7B97%u6CD5%uFF1A%0A%60%60%60%u5305%u542B%u5757%u7684%u5BBD%3D%u5143%u7D20%u5DE6%u504F%u79FB+%u5143%u7D20%u5DE6%u5916%u8FB9%u8DDD+%u5143%u7D20%u5DE6%u8FB9%u6846%u5BBD+%u5143%u7D20%u5DE6%u5185%u8FB9%u8DDD+%u5143%u7D20%u5BBD+%u5143%u7D20%u53F3%u5185%u8FB9%u8DDD+%u5143%u7D20%u53F3%u8FB9%u6846%u5BBD+%u5143%u7D20%u53F3%u5916%u8FB9%u8DDD+%u5143%u7D20%u53F3%u504F%u79FB%60%60%60%0A%uFF085%uFF09%u56FA%u5B9A%u5B9A%u4F4D%uFF0C%u56FA%u5B9A%u5B9A%u4F4D%u5305%u542B%u5757%u662F%u89C6%u7A97%uFF0C%u8BB0%u4F4F%u8FD9%u70B9%u5C31%u884C%u3002%0A%uFF086%uFF09%60%60%60z-index%60%60%60%3A%60%60%60z-index%60%60%60%3A%u7528%u4E8E%u533A%u5206%u5143%u7D20%u7684%u91CD%u53E0%u60C5%u51B5%uFF0C%u5176%u503C%u8D8A%u5927%u8868%u793A%u79BB%u7528%u6237%u8D8A%u8FD1%u3002%0A%u8FD9%u91CC%u8981%u6CE8%u610F%u5143%u7D20%u7684%u540E%u4EE3%u5143%u7D20%u6240%u5B9A%u4E49%u7684z-index%u662F%u76F8%u5BF9%u4E8E%u8BE5%u5143%u7D20%u800C%u8A00%u7684%uFF0C%u800C%u4E0D%u662F%u521D%u59CB%u5305%u542B%u5757%0A***%0A%23%23%23%23%23%u4F5C%u4E1A1.get%u548Cpost%u7684%u5DEE%u5F02%uFF1F%0A%uFF081%uFF09get%u662F%u4ECE%u670D%u52A1%u5668%u4E0A%u83B7%u53D6%u6570%u636E%uFF0Cpost%u662F%u5411%u670D%u52A1%u5668%u4F20%u9001%u6570%u636E%u3002%0Aget%u662F%u628A%u53C2%u6570%u6570%u636E%u961F%u5217%u52A0%u5230%u63D0%u4EA4%u8868%u5355%u7684ACTION%u5C5E%u6027%u6240%u6307%u7684URL%u4E2D%uFF0C%u503C%u548C%u8868%u5355%u5185%u5404%u4E2A%u5B57%u6BB5%u4E00%u4E00%u5BF9%u5E94%uFF0C%u5728URL%u4E2D%u53EF%u4EE5%u770B%u5230%u3002post%u662F%u901A%u8FC7HTTP%20post%u673A%u5236%uFF0C%u5C06%u8868%u5355%u5185%u5404%u4E2A%u5B57%u6BB5%u4E0E%u5176%u5185%u5BB9%u653E%u7F6E%u5728HTML%20HEADER%u5185%u4E00%u8D77%u4F20%u9001%u5230ACTION%u5C5E%u6027%u6240%u6307%u7684URL%u5730%u5740%u3002%u7528%u6237%u770B%u4E0D%u5230%u8FD9%u4E2A%u8FC7%u7A0B%u3002%0A%uFF082%uFF09%u5BF9%u4E8Eget%u65B9%u5F0F%uFF0C%u670D%u52A1%u5668%u7AEF%u7528Request.QueryString%u83B7%u53D6%u53D8%u91CF%u7684%u503C%uFF0C%u5BF9%u4E8Epost%u65B9%u5F0F%uFF0C%u670D%u52A1%u5668%u7AEF%u7528Request.Form%u83B7%u53D6%u63D0%u4EA4%u7684%u6570%u636E%u3002%0A%uFF083%uFF09get%u4F20%u9001%u7684%u6570%u636E%u91CF%u8F83%u5C0F%uFF0C%u4E0D%u80FD%u5927%u4E8E2KB%u3002post%u4F20%u9001%u7684%u6570%u636E%u91CF%u8F83%u5927%uFF0C%u4E00%u822C%u88AB%u9ED8%u8BA4%u4E3A%u4E0D%u53D7%u9650%u5236%u3002%u4F46%u7406%u8BBA%u4E0A%uFF0CIIS4%u4E2D%u6700%u5927%u91CF%u4E3A80KB%uFF0CIIS5%u4E2D%u4E3A100KB%u3002%0A%uFF084%uFF09get%u5B89%u5168%u6027%u975E%u5E38%u4F4E%uFF0Cpost%u5B89%u5168%u6027%u8F83%u9AD8%u3002%0A%23%23%23%23%23%u4E00%u4E9B%u5EF6%u4F38%u77E5%u8BC6%0AHTTP%20%u5B9A%u4E49%u4E86%u4E0E%u670D%u52A1%u5668%u4EA4%u4E92%u7684%u4E0D%u540C%u65B9%u6CD5%uFF0C%u6700%u57FA%u672C%u7684%u65B9%u6CD5%u662F%20GET%20%u548C%20POST%u3002%u4E8B%u5B9E%u4E0A%20GET%20%u9002%u7528%u4E8E%u591A%u6570%u8BF7%u6C42%uFF0C%u800C%u4FDD%u7559%20POST%20%u4EC5%u7528%u4E8E%u66F4%u65B0%u7AD9%u70B9%u3002%u6839%u636E%20HTTP%20%u89C4%u8303%uFF0CGET%20%u7528%u4E8E%u4FE1%u606F%u83B7%u53D6%uFF0C%u800C%u4E14%u5E94%u8BE5%u662F%20%u5B89%u5168%u7684%u548C%u5E42%u7B49%u7684%u3002%u6240%u8C13%u5B89%u5168%u7684%u610F%u5473%u7740%u8BE5%u64CD%u4F5C%u7528%u4E8E%u83B7%u53D6%u4FE1%u606F%u800C%u975E%u4FEE%u6539%u4FE1%u606F%u3002%u6362%u53E5%u8BDD%u8BF4%uFF0CGET%20%u8BF7%u6C42%u4E00%u822C%u4E0D%u5E94%u4EA7%u751F%u526F%u4F5C%u7528%u3002%u5E42%u7B49%u7684%u610F%u5473%u7740%u5BF9%u540C%u4E00%20URL%20%u7684%u591A%u4E2A%u8BF7%u6C42%u5E94%u8BE5%u8FD4%u56DE%u540C%u6837%u7684%u7ED3%u679C%u3002%u5B8C%u6574%u7684%u5B9A%u4E49%u5E76%u4E0D%u50CF%u770B%u8D77%u6765%u90A3%u6837%u4E25%u683C%u3002%u4ECE%u6839%u672C%u4E0A%u8BB2%uFF0C%u5176%u76EE%u6807%u662F%u5F53%u7528%u6237%u6253%u5F00%u4E00%u4E2A%u94FE%u63A5%u65F6%uFF0C%u5979%u53EF%u4EE5%u786E%u4FE1%u4ECE%u81EA%u8EAB%u7684%u89D2%u5EA6%u6765%u770B%u6CA1%u6709%u6539%u53D8%u8D44%u6E90%u3002%20%u6BD4%u5982%uFF0C%u65B0%u95FB%u7AD9%u70B9%u7684%u5934%u7248%u4E0D%u65AD%u66F4%u65B0%u3002%u867D%u7136%u7B2C%u4E8C%u6B21%u8BF7%u6C42%u4F1A%u8FD4%u56DE%u4E0D%u540C%u7684%u4E00%u6279%u65B0%u95FB%uFF0C%u8BE5%u64CD%u4F5C%u4ECD%u7136%u88AB%u8BA4%u4E3A%u662F%u5B89%u5168%u7684%u548C%u5E42%u7B49%u7684%uFF0C%u56E0%u4E3A%u5B83%u603B%u662F%u8FD4%u56DE%u5F53%u524D%u7684%u65B0%u95FB%u3002%u53CD%u4E4B%u4EA6%u7136%u3002POST%20%u8BF7%u6C42%u5C31%u4E0D%u90A3%u4E48%u8F7B%u677E%u4E86%u3002POST%20%u8868%u793A%u53EF%u80FD%u6539%u53D8%u670D%u52A1%u5668%u4E0A%u7684%u8D44%u6E90%u7684%u8BF7%u6C42%u3002%u4ECD%u7136%u4EE5%u65B0%u95FB%u7AD9%u70B9%u4E3A%u4F8B%uFF0C%u8BFB%u8005%u5BF9%u6587%u7AE0%u7684%u6CE8%u89E3%u5E94%u8BE5%u901A%u8FC7%20POST%20%u8BF7%u6C42%u5B9E%u73B0%uFF0C%u56E0%u4E3A%u5728%u6CE8%u89E3%u63D0%u4EA4%u4E4B%u540E%u7AD9%u70B9%u5DF2%u7ECF%u4E0D%u540C%u4E86%0A7%0A%u5728FORM%u63D0%u4EA4%u7684%u65F6%u5019%uFF0C%u5982%u679C%u4E0D%u6307%u5B9AMethod%uFF0C%u5219%u9ED8%u8BA4%u4E3AGET%u8BF7%u6C42%uFF0CForm%u4E2D%u63D0%u4EA4%u7684%u6570%u636E%u5C06%u4F1A%u9644%u52A0%u5728url%u4E4B%u540E%uFF0C%u4EE5%3F%u5206%u5F00%u4E0Eurl%u5206%u5F00%u3002%u5B57%u6BCD%u6570%u5B57%u5B57%u7B26%u539F%20%u6837%u53D1%u9001%uFF0C%u4F46%u7A7A%u683C%u8F6C%u6362%u4E3A%u201C+%u201C%u53F7%uFF0C%u5176%u5B83%u7B26%u53F7%u8F6C%u6362%u4E3A%25XX%2C%u5176%u4E2DXX%u4E3A%u8BE5%u7B26%u53F7%u4EE516%u8FDB%u5236%u8868%u793A%u7684ASCII%uFF08%u6216ISO%20Latin-1%uFF09%u503C%u3002GET%u8BF7%u6C42%u8BF7%u63D0%u4EA4%u7684%u6570%u636E%u653E%u7F6E%u5728HTTP%u8BF7%u6C42%u534F%u8BAE%u5934%u4E2D%uFF0C%u800CPOST%u63D0%u4EA4%u7684%u6570%u636E%u5219%u653E%u5728%u5B9E%u4F53%u6570%u636E%u4E2D%uFF1BGET%u65B9%u5F0F%u63D0%u4EA4%u7684%u6570%u636E%u6700%u591A%u53EA%u80FD%u67091024%u5B57%u8282%uFF0C%u800CPOST%u5219%u6CA1%u6709%u6B64%u9650%u5236%u3002%0A%23%23%23%23%23%u76F8%u5E94%u62A5%u6587%u72B6%u6001%u7801%0A1.%20%u72B6%u6001%u5417%u8BF4%u660E%uFF1A%0A***%0A%201xx%20%u670D%u52A1%u7AEF%u63A5%u6536%u5230%u8BF7%u6C42%uFF0C%u4F46%u4ECD%u5728%u5904%u7406%u4E2D%u5E76%u6CA1%u6709%u5B8C%u6210%u3002%0A%202xx%uFF1A%u670D%u52A1%u5668%u6210%u529F%u5904%u7406%u8BF7%u6C42%u3002%0A%203xx%uFF1A%u8BF7%u6C42%u5904%u7406%u5B8C%u6210%uFF0C%u4F46%u5BA2%u6237%u7AEF%u9700%u8981%u4ECE%u5176%u4ED6%u4F4D%u7F6E%u83B7%u53D6%u8D44%u6E90%0A%20%204xx%uFF1A%u5BA2%u6237%u7AEF%u9519%u8BEF%0A%205xx%uFF1A%u670D%u52A1%u5668%u9519%u8BEF%0A***%0A2.%20%u5E38%u89C1%u72B6%u6001%u7801%0A***%0A200%20%u8BF7%u6C42%u6210%u529F%0A301%20%u6C38%u4E45%u91CD%u5B9A%u5411%0A302%20%u4E34%u65F6%u91CD%u5B9A%u5411%0A303%20%u91CD%u5B9A%u5411%0A304%20%u4ECE%u7F13%u5B58%u8BFB%u53D6%0A401%20%u672A%u6388%u6743%0A404%20%u8D44%u6E90%u4E0D%u5B58%u5728%0A500%20%u670D%u52A1%u5668%u9519%u8BEF%0A503%20%u670D%u52A1%u4E0D%u53EF%u7528%0A</center><br/></span>
</div></body></html> 