## Quantumult X 教程备忘录
1.  lazyProfiles_QX-20200221.conf是根据[教程](https://merlinblog.xyz/wiki/quanx.html "教程")导入，且自己修改部分的全部配置备份（不含订阅）
1. 脚本[链接](https://github.com/yichahucha/surge/tree/master  "链接")      
1. 另一篇详解[教程](https://www.notion.so/Quantumult-X-1d32ddc6e61c4892ad2ec5ea47f00917 "教程")

#### 更新于20200222
- APP全部更新后，目前发现优酷可以正常播放，且视频无广告。京东无法显示历史价格，且APP加载明细变慢，注释rewrite后恢复规则，发现京东比价恢复正常。微博更新后好像看不到开屏广告了。

#### 更新于20200221
- 有个bug:优酷app提示错误代码，看路由记录都是直连，只有完全关闭qx才能访问优酷app，淘宝支付宝没影响，不解。
- 默认CN策略是代理，已改为直连。修改后可以一直挂代理，国内就直连，国外走代理，几乎没有感知
- 增加了京东比价脚本，虽然也有微博脚本，但是不确定缓存原因导致还有广告。
