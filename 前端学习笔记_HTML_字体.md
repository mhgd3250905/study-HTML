##前端学习笔记

### 字体修改 ###
----------
2017/1/22 13:05:35

自定义字体并使用：

	/*自定义字体*/
	@font-face {
	    /* font-properties */
	    font-family: FZLTH;
	    src:url('fonts/FZLTH.ttf');
	}
	
	div {
	    font-family: FZLTH;
	} 

> 但是在开发过程中不同的浏览器会有不同的字体需求，这里推荐一个网站：
[https://www.fontsquirrel.com/tools/webfont-generator](https://www.fontsquirrel.com/tools/webfont-generator "指定字体上传，下载对应不同格式")