# tinymce-fontawesomepicker
tinymce的一个插件，用来选择`fontawesome`图标

# 使用方法
将`fontawesomepicker`文件夹移动至`tinymce`的插件目录下(plugins)，将自动注册插件。
```js
window.tinymce.init({
    selector: 'textarea',
    plugins: 'fontawesomepicker',
    toolbar: 'fontawesomepicker',
    fontawesomeUrl: 'https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.13.0/css/all.min.css'
})
```
或者通过链接的方式加载`fontawesomepicker`插件
```js
window.tinymce.init({
    selector: 'textarea',
    plugins: 'fontawesomepicker',
    toolbar: 'fontawesomepicker',
    external_plugins: {
        //  插件链接
        fontawesomepicker: '/tinymce-fontawesomepicker/fontawesomepicker/plugin.js'
    },
    fontawesomeUrl: 'https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.13.0/css/all.min.css'
})
```

# 展示
![image](20200520140904.jpg)