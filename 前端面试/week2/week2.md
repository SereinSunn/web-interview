**JS中不同的输出方式**

1.弹窗方式输出


```
window.alert('弹窗方式输出');
```



弹窗方式显示是一种阻断式的输出方式，只有点击确定按钮，才能继续该语句下面的内容
以“alert（）”方式弹窗的效果，只有一个确定按钮，一般情况下是用来给用户提示的

2.控制台输出



```
console.log('控制台输出');
console.warn('这是一个警告！');
console.error('这是一个错误！');
```


一般情况下用于开发人员调试

3.向body中输出一个内容

```
document.write('body中输出');
document.write('<div>body中输出</div>');
document.write('<h1>body中输出</h1>');
```

可接收从服务器传来的信息，显示在页面中



4.在网页中弹出输入框，一般用于接收用户输入的信息

```
window.prompt('请输入信息');
```


相比较“alert()”,多出了一个取消按钮

5.在网页中弹出提示框，显示信息，该方法一般与if判断语句结合使用

```
window.confirm('信息是否正确？');
```



```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>JS常用输出方式</title>
</head>
<body>
<script>
    // 1.弹窗,阻断式
    window.alert('弹窗方式输出');
    // debugger;


    //2.控制台输出
    console.log('控制台输出');
    console.warn('这是一个警告！');
    console.error('这是一个错误！');


    //3.向body中输出一个内容
    document.write('body中输出');
    document.write('<div>body中输出</div>');
    document.write('<h1>body中输出</h1>');


    // 4.在网页中弹出输入框，一般用于接收用户输入的信息
    window.prompt('请输入信息');


    // 5.在网页中弹出提示框，显示信息，该方法一般与if判断语句结合使用
    window.confirm('信息是否正确？');
</script>
</body>
</html>
```



