# AngularJS学习笔记

## 绑定

使用双大括号包含的表达式：

```html
<p>
    Nothing here {{'yet' + '!'}}
</p>
```

绑定告诉AngularJS需要运算其中的表达式并将结果插入DOM中，表达式在当前Angular作用域中运行

## 应用

通过ngApp指令引导AngulaJS应用

```html
<!doctype html>
<html lang="en" ng-app>
<head>
	<meta charset="utf-8">
	<title>My HTML File</title>
	<link rel="stylesheet" href="css/app.css">
	<link rel="stylesheet" href="css/bootstrap.css">
	<script src="lib/angular/angular.js"></script>
</head>
<body>
<p>Nothing here {{'yet' + '!'}}</p>
</body>
</html>	
```

用图片描述：

![](C:\Users\Administrator\Desktop\bootstrapping.png)