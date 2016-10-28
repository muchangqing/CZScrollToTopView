# CZScrollToTopView
点击顶部状态栏，滑动到最上面

###写了一个UIViewController的分类，仅需要设置 self.scrollsToTop = YES；就可以实现多个scrollView嵌套，回到顶部。

*注意：如果控制器中实现了UIScrollViewDelegate<- (void)scrollViewWillBeginDragging:(UIScrollView *)scrollView>方法，就需要手动调用分类提供的方法- (void)cz_scrollViewWillBeginDragging:(UIScrollView *)scrollView;
