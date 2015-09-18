Idialog对话框插件
===
基于jquery的对话框插件，优点：小巧、易于修改扩展

```javascript
//弹出框使用示例
var d = Idialog({
	top:100,
	width:500,
	content:$('#test'),
	init:function(body){
		//console.log(body);
	},
	ok:function(obj){
		//console.log(obj);
		return false;
	},
	cancel:true
});

//tips使用示例
Idialog.tips("message",3); //提示3秒后消失
```
