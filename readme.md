#移动端开发问题收集

*	元素事件绑定推荐 

```
$('ele').on('eventName', function(){})
```

*	文本框变动是事件，推荐使用元神oninput事件，而不是jquery的keyup事件
	
*	移动端粘贴板，execCommand有兼容性问题

	*	[H5 复制粘贴 - execCommand](http://www.jianshu.com/p/37322bb86a48)
	*	[clipboard](https://clipboardjs.com/)