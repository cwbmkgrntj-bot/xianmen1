# 仙门灵田录 iPhone PWA
这是可添加到 iPhone 主屏幕的网页游戏原型。

## 当前内容
- 灵田播种/计时成长/收获
- 灵石与修为、本机存档
- 修炼、炼丹、灵宠寻宝、时装切换
- iPhone 竖屏布局、PWA manifest、Service Worker、主屏幕图标

## iPhone 安装
必须部署到 HTTPS（例如自己的服务器、支持静态站点的托管平台）：
1. 将本目录所有文件上传，确保 `index.html` 位于网站根目录。
2. iPhone 用 Safari 打开 HTTPS 游戏网址。
3. 点分享按钮 -> 添加到主屏幕 -> 添加。
4. 从主屏幕图标启动，进入独立窗口。

## 本地测试
电脑可用静态服务器预览（不要直接 file:// 打开），例如：
`python -m http.server 8000`
然后访问 `http://localhost:8000`。PWA安装需要HTTPS或localhost。

## 说明
当前为单机玩法原型；好友真实偷菜、账号、云端存档、排行榜、微信登录等需要后续服务器/云开发接入。
