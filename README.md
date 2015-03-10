# UIView-Frame
实现UIView分类，方便在应用中直接修改UIView的frame的各种属性
###使用说明
*将此分类clone 到你的项目中
*将头文件加入到将要使用的头文件中
*修改UIView的frame中的某个属性，如下

```
UIImageView *bg = [[UIImageView alloc]initWithImage:  [UIImage imageNamed:@"bgImage"]];
    bg.width = 200;
    bg.height = 100;
    bg.centerX = contain.centerX;
    bg.y = CGRectGetMaxY(contain.frame) - 10;
```
