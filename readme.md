# 你妹的  我在学习markdown
## [CSDN](http://www.baidu.com)
**1. 欢迎屌丝进来学习**  
![blockchain](https://ss0.bdstatic.com/70cFvHSh_Q1YnxGkpoWK1HF6hhy/it/u=702257389,1274025419&fm=27&gp=0.jpg "区块链")  
[简书](http://jianshu.com)  
<a href="http://jianshu.com" target="_blank">超链接名</a>  

* 列表内容  
 * 你好  
 * 安徽的
 
 **src/app/guard/login.guard.ts**
```
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

|左对齐标题|右对齐标题|居中对齐标题|
|:-|-:|:-:|
|短文本|中等文本|稍微长一点的文本|
|稍微长一点的文本|短文本|中等文|

