#iOS 面试题

##初级篇
1. `View` `ViewController` 的关系？
2. `tintColor` 是做什么的？
3. 如何给一个`UIView` 切出圆角？
4. 为什么在`UITableViewDataSource`里面的`cellForRowAtIndexPath`中，要调用`dequeueReusableCellWithIdentifier`, 而不是直接新建一个`UITableViewCell`？
5. 如何异步地从网上下载一个文件？用过开源库吗？
6. 你如何处理 JSON 文件？用过开源库吗？



##中级篇
1. 现在有一个 `UITableView`, 其中一个 Cell 要显示一个网页。如何动态根据网页本身大小确定高度？(iOS 7/8 不同)
2. 用 Auto Layout 排版的时候，如何动态改变 Constriants ？比如 `|[view1]-5-[view2]|`，要做一个动画将 `view2` 隐藏，layout 变为 `|[view1]|`, 怎么写？
3. 使用过 Singleton 吗？在 Swift 里如何实现一个 Singleton class？
4. Swift 中 `map`, `reduce`, `filter` 是 lazy 的。什么是 lazy？
5. 你要写一个词语接龙。有一个语料库`corpus:[String]`, 设计合适的数据结构。
6. `drawRect`是做什么的？
7. 如何在两个并列的 `UIButton` 之间加一条指定颜色长度的分割线？
7. `HTTP`的`POST`和`GET`啥区别？（区别挺多的，麻烦多说点）

##高级篇
1. 什么是ARC？（ARC是为了解决什么问题诞生的？）
5. 描述一个你遇到过的retain cycle例子。
6. `+(void)load`; `+(void)initialize`；有什么用处？
7. 为什么其他语言里叫函数调用， `Objective-C`里则是给对象发消息（或者谈下对runtime的理解）
8. 什么是method swizzling?
9. method swizzling 在 Swift 中能实现吗？
9. `UIView`和`CALayer`是啥关系？
10. 如何高性能的给 `UIImageView` 加个圆角？（不准说`layer.cornerRadius`!）
13. 麻烦你设计个简单的图片内存缓存器
14. 讲讲你用Instrument优化动画性能的经历吧（别问我什么是Instrument）
15. `loadView`是干嘛用的？
16. `viewWillLayoutSubView`是什么？
17. GCD里面有哪几种Queue？你自己建立过串行queue吗？背后的线程模型是什么样的？
18. 用过`Core Data`或者`sqlite`吗？读写是分线程的吗？遇到过死锁没？咋解决的？

