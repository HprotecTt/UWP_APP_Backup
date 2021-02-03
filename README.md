# UWP离线包安装管理
## 安装
- 首先你需要[应用安装程序](https://www.microsoft.com/store/productId/9NBLGGH4NNS1)
![应用安装程序](https://tva3.sinaimg.cn/large/008fEidvgy1gnabmf9ln0j30tb083gm9.jpg)
- 然后双击 .appx后缀名的安装包文件即可直接安装 UWP 应用
![应用安装](https://tvax1.sinaimg.cn/large/008fEidvgy1gnabpbybiej30sg0k2aax.jpg)
- 若不能安装，请依次打开【设置】-【更新和安全】-【开发者选项】，选中【旁加载应用】后再次尝试
## 管理
- 依次打开【设置】-【应用】，在【应用和功能】中找到所安装的软件，点击【高级选项】
![应用和功能](https://tvax1.sinaimg.cn/large/008fEidvgy1gnac23jzsyj30sf0flq8q.jpg)
- 你可以在此设置应用权限、终止应用运行、重置应用、卸载应用：
![高级选项1](https://tva1.sinaimg.cn/large/008fEidvgy1gnac232el3j31hc0xcgmr.jpg)
![高级选项2](https://tvax2.sinaimg.cn/large/008fEidvgy1gnac23axc6j31hc0i40ta.jpg)
- 在开始菜单找到你安装的应用，可将之固定到开始屏幕、卸载。在开始屏幕可以调整磁贴位置、样式等
![开始菜单](https://tvax4.sinaimg.cn/large/008fEidvgy1gnacbbl9g9j30va09raek.jpg)
> 若你需要批量清空UWP应用缓存，可使用快捷键【Window】+【R】打开运行窗口，输入wsreset后确认
> ![运行wsreset](https://tva4.sinaimg.cn/large/008fEidvgy1gnacla4zmaj30e907kaa5.jpg)
> 将会清空全部UWP应用的缓存
> ![wsreset](https://tvax1.sinaimg.cn/large/008fEidvgy1gnacl9vgdcj30xy0hqt8n.jpg)
> 清理完成后将自动打开Microsoft Store
> ![microsoft store](https://tvax1.sinaimg.cn/large/008fEidvgy1gnacl9o3j0j31070n5tn2.jpg)

# 从Microsoft Store抓取UWP应用离线安装包
- 在应用详情页面点击【分享】-【复制链接】
![复制链接](https://tva1.sinaimg.cn/large/008fEidvgy1gnadplh9jgj30w30mygv5.jpg)
- 前往[【Microsoft Store - Generation Project】](https://store.rg-adguard.net/)将链接粘贴到文本框中
![抓取](https://tvax4.sinaimg.cn/large/008fEidvgy1gnadpmljfjj310x0c9n3k.jpg)
- 单击选择应用名称对应后缀名为【.appx】或【 .appxbundle】的项目即可下载得到对应安装包，安装时会自动下载安装运行库，所以相关运行库和框架可以不下载
![下载](https://tvax2.sinaimg.cn/large/008fEidvgy1gnadpm7vi6j31hc0ue7p1.jpg)

> 将后缀名为【 .appxbundle】的文件后缀名更改为【.zip】后解压可得到适用于不同平台的应用安装包及相关依赖
> ![解压](https://tvax4.sinaimg.cn/large/008fEidvgy1gnadwfh9nvj313j0lkwhg.jpg)
> 其中【arm】为Windows Phone安装包，【x86】为32位PC安装包，【x64】为64位PC安装包

# 本项目目录结构
分类
	安装包
	简介文档
