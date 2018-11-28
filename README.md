### RulerSlider

移动端滑动选择价格 `停止维护`

#### 效果图

![DEMO](/image/1.png)

#### 使用方式

Demo

```javascript
new Ruler({
  rulerid: "#rulerid",
  ratioText: ["1月", "2月"],
  ratioindex: 0
  ...
});
```

#### 参数

```javascript
{
	            rulerid: '#rulerid',// ruler id选择器
	            ratioText:["1月", "2月"], //展示在底部的文案
	            ratioindex: 0,  //初始按钮的位置，从0开始
	            ontransitionend: null,  //动画结束后回调
	            onafterinit: null,  //初始化后回调
	            titleFn: null,
	            onstart: null,//点击回调
	            onmove: null,//移动回调
	            onend: null//滑动结束回调
}
```

#### 方法

Ruler#setposition(index) //设置位置
