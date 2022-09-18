# apple store 商品提醒 青龙脚本
## 使用
型号和地区获取：https://www.apple.com.cn/shop/buy-iphone/iphone-14-pro/MQ8A3CH/A

1. 新建脚本
2. 新建环境变量 APPLE_SKU=MQ1C3CH/A APPLE_LOCATION=浙江_杭州_拱墅区
3. 添加任务 命令 task task apple-store.js 0 */5 * * * ?

