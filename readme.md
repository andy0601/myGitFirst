# 你妹的  我在学习markdown
## [CSDN](http://www.baidu.com)
**1. 欢迎屌丝进来学习**  
![blockchain](https://ss0.bdstatic.com/70cFvHSh_Q1YnxGkpoWK1HF6hhy/it/u=702257389,1274025419&fm=27&gp=0.jpg "区块链")  
[简书](http://jianshu.com)  
<a href="http://jianshu.com" target="_blank">超链接名</a>   
==w s==
```flow
st=>start: 开始|past:> http://www.baidu.com // 开始
e=>end: 结束              // 结束
c1=>condition: 条件1:>http://www.baidu.com[_parent]   // 判断条件
c2=>condition: 条件2      // 判断条件
c3=>condition: 条件3      // 判断条件
io=>inputoutput: 输出     // 输出
//----------------以上为定义参数-------------------------

//----------------以下为连接参数-------------------------
// 开始->判断条件1为no->判断条件2为no->判断条件3为no->输出->结束
st->c1(yes,right)->c2(yes,right)->c3(yes,right)->io->e
c1(no)->e                   // 条件1不满足->结束
c2(no)->e                   // 条件2不满足->结束
c3(no)->e                   // 条件3不满足->结束
```

作者：欧薇娅
链接：https://www.jianshu.com/p/b03a8d7b1719
來源：简书
简书著作权归作者所有，任何形式的转载都请联系作者获得授权并注明出处。

* 列表内容  
 * 你好  
 * 安徽的
 
 **src/app/guard/login.guard.ts**
```javascript
import {CanActivate} from '@angular/router';

export class LoginGuard implements CanActivate {
  canActivate () {
    const loggedIn: boolean = Math.random() < 0.5;

    if (!loggedIn) {
      console.log('用户未登录');
    }

    return loggedIn;
  }
}
```
 
- [x] 选项一
- [ ] 选项二  
- [ ]  [选项3]
 
 [![dddd](https://ss0.bdstatic.com/70cFvHSh_Q1YnxGkpoWK1HF6hhy/it/u=702257389,1274025419&fm=27&gp=0.jpg "区块链")](http://v.youku.com/v_show/id_XMjgzNzM0NTYxNg==.html?spm=a2htv.20009910.contentHolderUnit2.A&from=y1.3-tv-grid-1007-9910.86804.1-2#paction)
 
 [百度1](http://www.baidu.com/)
```
<div>   
    <div></div>
    <div></div>
    <div></div>
</div>
```
 
 ```javascript  
var num = 0;  
for (var i = 0; i < 5; i++) {  
    num+=i;  
}  
console.log(num);  
```
 
姓名|性别|年龄|身高|学历
-|-|-|-|-
王中华|男|33|175|大专
王友华|男|31|175|高中

姓名|技能|排行
--|:-------:|--:
刘备|哭|大哥
关羽|打|二哥
张飞|骂|三弟  

```flow
st=>start: 开始
op=>operation: My Operation
cond=>condition: Yes or No?
e=>end
st->op->cond
cond(yes)->e
cond(no)->op
&```

