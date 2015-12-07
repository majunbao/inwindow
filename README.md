# 检测元素是显示在窗体内

# Event

* inwindow
* outwindow

## inwindow
`inwindow` 事件，当某元素显示在窗体中时，触发此事件

```javascript
// 延迟加载图片
// 当图片显示在窗口中时才载入图片
$('img').on('inwindow',function(){
  $(this).src($(this).data('src'))
})
```

# Method

* inwindow