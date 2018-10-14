# hello-world

#浏览器兼容性查询网站：https://caniuse.com

#模版引擎：arttemplate

#js三大图表库：http://www.cnblogs.com/qmsu/p/5521057.html

#兼容低版本ie浏览器的图表插件：http://www.humblesoftware.com/flotr2

#各大模板引擎：http://www.cnblogs.com/guohu/p/3870677.html

#阿里图标库：http://www.iconfont.cn/

#hello

*{-webkit-tap-highlight-color:rgba(0,0,0,0);
	-webkit-touch-callout:none;
	-webkit-user-select:none;
	-webkit-appearance:none;
	outline:none;
	box-sizing:border-box;
	-webkit-box-sizing:border-box;
}
body,html,h1,h2,h3,h4,h5,h6,p,ul,ol,li,dl,dt,dd,pre,form,fieldset, legend, input, textarea, p, blockquote, th, td, hr, button, article, aside, details, figcaption, figure, footer, header, hgroup, menu, nav, section {
	margin:0;
	padding:0;
}
h1,h2,h3,h4,h5,h6{font-size:15px;}
html{font-size:100px;height:100%;overflow-y:scroll;}
section,nav{display:block;}
input[type="text"],input[type="email"],input[type="url"],input[type="number"],input[type="password"],textarea{-webkit-user-select:text;}
input,.select,textarea{-webkit-user-select:initial;font-family:Arial,Helvetica,sans-serif;border:none;}
a{text-decoration:none;color:#5e5e5e;}
ul,li,ol{list-style:none;}
i,em{font-style:normal;}
img{border:0 none;}
/*去除默认apple手机显示圆角*/
input{-webkit-border-radius:0;-moz-border-radius:0;border-radius:0;border:0;background:none;}
/*去除IE10+浏览器文本框后面的小叉叉*/
input::-ms-clear {
    display: none;
}
/*禁止多行文本框textarea拖拽*/
textarea {
    resize: none;
}
/*去除谷歌等浏览器默认发光边框*/
input:focus, textarea:focus {
    outline: none;
    background: none;
    border: none;
    -webkit-tap-highlight-color:rgba(0,0,0,.0);
   /*border: 1px solid orange;用户自己添加样式，载入焦点时，边框颜色*/
}
/*默认提示输入框，字体样式*/
::-webkit-input-placeholder {
color:#999;
font-size:.24rem;
line-height:normal;
} 
body{
	font:0.24rem/1 "\5fae\8f6f\96c5\9ed1","Microsoft YaHei",Helvetica,Arial,sans-serif;
	background-color:#fff;
	max-width:750px;
	margin:0 auto;
	color:#333;
	overflow:hidden;
	opacity:0;
	background-color:#101010;
	-webkit-text-size-adjust:none;
}
.none{display:none;}
.t-l{text-align:left;}
.t-c{text-align:center;}
.t-r{text-align:right;}
.f-l{float:left;}
.f-r{float:right;}
.clearfix:after,.clear:before{content:"";display:table;}
.clearfix:after{clear:both;} 
