# 你好

```swift
private static func layoutView(with image: UIImage) {
    let ratio: CGFloat = image.size.width / image.size.height
    let x = 0.0
    var y = 0.0
    let w = view.width
    let h = self.view.width / ratio
    imageView.frame = CGRectMake(x, y, w, h)
    
    if h < self.view.height {
        //图片比设备屏幕长
        imageView.center = scrollView.center
    }
    
    
    if h > self.view.height {
        scrollView.contentSize = CGSizeMake(view.width, h)
    }
}
```

哈哈哈
```html
<p>This is a paragraph</p>
<a href="//docsify.js.org/">Docsify</a>
```

你好
```bash
echo "hello"
```