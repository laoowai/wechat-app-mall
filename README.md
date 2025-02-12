Project Structure
```
/ (project root)
├── config.js
├── app.js
├── app.json
├── app.wxss
├── project.config.json
├── images/                // common images
├── lib/                   // common library files (if any)
├── utils/                 // helper functions (if needed)
└── pages/
    ├── index/             // 首页
    │   ├── index.js
    │   ├── index.json
    │   ├── index.wxml
    │   └── index.wxss
    ├── list/              // 商品列表
    │   ├── index.js
    │   ├── index.json
    │   ├── index.wxml
    │   └── index.wxss
    ├── details/           // 商品详情
    │   ├── index.js
    │   ├── index.json
    │   ├── index.wxml
    │   └── index.wxss
    ├── user/              // 个人中心
    │   ├── index.js
    │   ├── index.json
    │   ├── index.wxml
    │   └── index.wxss
    ├── order/             // 我的订单
    │   ├── index.js
    │   ├── index.json
    │   ├── index.wxml
    │   └── index.wxss
    ├── coupon/            // 优惠券
    │   ├── index.js
    │   ├── index.json
    │   ├── index.wxml
    │   └── index.wxss
    ├── cart/              // 购物车
    │   ├── index.js
    │   ├── index.json
    │   ├── index.wxml
    │   └── index.wxss
    ├── addressList/       // 我的地址
    │   ├── index.js
    │   ├── index.json
    │   ├── index.wxml
    │   └── index.wxss
    └── addressAdd/        // 添加地址
        ├── index.js
        ├── index.json
        ├── index.wxml
        └── index.wxss
```





# 微信小程序实现移动端商城

## 说明
```

>  如果对您有帮助，您可以点右上角 "Star&fork" 支持一下 谢谢！ ^_^

>  博客地址:https://juejin.im/post/5b836d056fb9a019f671320f

>  配置HTTPS：https://juejin.im/post/5b88b58151882542db3bedf7

>  服务端:https://github.com/FZliweiliang/wechat-app-mall-server

>  提示小程序大于2M可以把screenshot文件夹删除
```

### 项目截图:

<img src="https://github.com/474782977/wechat-app-mall/blob/master/screenshot/1.png" width="320px" style="display:inline;">
<img src="https://github.com/474782977/wechat-app-mall/blob/master/screenshot/2.png" width="320px" style="display:inline;">
<img src="https://github.com/474782977/wechat-app-mall/blob/master/screenshot/3.png" width="320px" style="display:inline;">
<img src="https://github.com/474782977/wechat-app-mall/blob/master/screenshot/4.png" width="320px" style="display:inline;">
<img src="https://github.com/474782977/wechat-app-mall/blob/master/screenshot/5.png" width="320px" style="display:inline;">
<img src="https://github.com/474782977/wechat-app-mall/blob/master/screenshot/6.png" width="320px" style="display:inline;">
<img src="https://github.com/474782977/wechat-app-mall/blob/master/screenshot/7.png" width="320px" style="display:inline;">
<img src="https://github.com/474782977/wechat-app-mall/blob/master/screenshot/8.png" width="320px" style="display:inline;">
<img src="https://github.com/474782977/wechat-app-mall/blob/master/screenshot/9.png" width="320px" style="display:inline;">
<img src="https://github.com/474782977/wechat-app-mall/blob/master/screenshot/10.png" width="320px" style="display:inline;">
<img src="https://github.com/474782977/wechat-app-mall/blob/master/screenshot/11.png" width="320px" style="display:inline;">

## 项目布局
```
|-- images               // 公共图片
|-- lib                  // 公共文件
|-- pages                // 页面
|   |-- index            // 首页
|   |-- list             // 商品列表
|   |-- details	         // 商品详情
|   |-- user             // 个人中心
|   |-- order            // 我的订单
|   |-- coupon           // 优惠券
|   |-- cart             // 购物车
|   |-- addressList      // 我的地址
|   |-- addressAdd       // 添加地址
|-- README.md            // 说明
```

## 开发环境：
调试基础库 2.0.4
