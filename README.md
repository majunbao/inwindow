# 检测元素是显示在窗体内

# Event

* inwindow
* outwindow

## inwindow
```javascript
// 延迟加载图片
//当图片显示在窗口中时才载入图片
$('img').on('inwindow',function(){
  $(this).src($(this).data('src'))
})
```

# Method

* inwindow