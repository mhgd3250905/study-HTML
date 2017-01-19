##前端学习笔记

### 防止文本出格 ###


1.学习的过程中出现了文本出格的现象

通过css设置修正：

	.mContnet{
    	word-break: break-all;
	}

2 学习的过程中需要实现类似简书的文本内容显示三行并且最后一行末尾省略：

![](http://i.imgur.com/FJKoGU2.png)

	.mContnet{
	    word-break: break-all;
	    overflow : hidden;
	    text-overflow: ellipsis;
	    display: -webkit-box;
	    -webkit-line-clamp: 3;
	    -webkit-box-orient: vertical;
	}

资料摘自：
[http://c7sky.com/text-overflow-ellipsis-on-multiline-text.html](http://c7sky.com/text-overflow-ellipsis-on-multiline-text.html)