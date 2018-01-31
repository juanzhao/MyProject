# MyProject
项目技术点
 UIPanGestureRecognizer 手势 实现
 
在view中取到滑动距离 
CGPoint translation = [panGestureRecognizer translationInView:self.firstCategoryView];

滑动结束后判断
panGestureRecognizer.state == UIGestureRecognizerStateEnded
