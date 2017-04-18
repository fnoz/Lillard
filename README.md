# FNBlingBlingLabel
Swift实现的UILabel文字随机渐隐渐现, Swift版RQShineLabel.

暂时没做Pod和Carthage.

### 基础使用Demo：

```
	let blingBlingLabel = FNBlingBlingLabel.init(frame: CGRectMake(0, 0, 300, 200))
	blingBlingLabel.needAnimation = true
	blingBlingLabel.numberOfLines = 0
	blingBlingLabel.textColor = UIColor.whiteColor()
	blingBlingLabel.appearDuration = 1.5
	blingBlingLabel.disappearDuration = 1.5
	self.view.addSubview(blingBlingLabel)
	blingBlingLabel.text = "FNBlingBlingLabel-TestString"
```

### 效果：
![Animating](readme_images/animating.gif)

### 来源：
OC原版是 [RQShineLabel](https://github.com/zipme/RQShineLabel)