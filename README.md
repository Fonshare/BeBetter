收集了以前的GFWList，添加了一些后来遇到的网址

自用以及给我的小伙伴用

用于 ShadowsocksR 的PAC文件

推荐关闭服务器负载均衡并使用PAC模式

GFWList地址 https://raw.githubusercontent.com/Fonshare/GFWList/master/pac.txt

GFWList 是一个开源的黑名单项目，它由成千上万的网友贡献整理而成，从而实现被 GFWed 的域名自动走代理；而 Flora 则从 IP 上去获取中国的 IP 地址段，从而生成智能 PAC ，对国外的 IP 使用代理 使用方法如下

- android 进入节点配置界面 选择路由-自定义ACL文件-输入URL 输入文中链接即可
- iOS Shadowrocket 添加配置文件 写入上面的链接
- windows 右键单击链接 点击另存为 下载pac文件到本地覆盖客户端文件夹中pac.txt即可
