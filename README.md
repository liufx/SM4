# SM4
##国密4 微信小程序前端加密解密


##使用指南

* 直接引入SM4文件夹 其中包含base64js.min.js 和sm4.js
* ecb加密 

```javascript

 var s=  sm4.encrypt_ecb('张三', "krbdcwdVsFFwqx53");
   console.log(s)
   
```
* ecb解密

```javascript

 var b=  sm4.decrypt_ecb(s, "krbdcwdVsFFwqx53")
  console.log(b)
  
```
* cbc加密 

```javascript

  var s1=  sm4.encrypt_cbc('2020-04-07 11:38:32', "hVkFxbbvLB8o7iAh","krbdcwdVsFFwqx53");
  console.log(s1)
   
```
* cbc解密

```javascript

  var b1=  sm4.decrypt_cbc(s1, "hVkFxbbvLB8o7iAh","krbdcwdVsFFwqx53");
  console.log(b1)
  
```


##有问题反馈
在使用中有任何问题，欢迎反馈给我，可以用以下联系方式跟我交流

* 邮件: (547166147@qq.com)
* 微信: lfx19890801
* 简书: [@Smile_188](https://www.jianshu.com/u/cc3ecc8ef368)

##捐助开发者
在兴趣的驱动下,写一个`免费`的东西，有欣喜，也还有汗水，希望你喜欢我的作品，同时也能支持一下。
##感激
感谢以下的项目,排名不分先后

* [SM4国密加密解密实现代码demo](https://blog.csdn.net/qq_35713752/article/details/104544023)
