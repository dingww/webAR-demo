### 运行
*   npm install
*   npm run dev

### 搭建调试用的AR增强浏览器
*   首先下载[WebARonARKit](https://github.com/google-ar/WebARonARKit)，然后电脑安装[Xcode 9](https://developer.apple.com/xcode/)，用Xcode打开WebARonARKit项目，连接浏览器运行的移动设备（需要支持iOS 11），在xcode的顶部菜单栏选择Product >> Destination 选择连接的设备，连接的设备需要选择信任连接（设置>Safari>高级>连接的苹果账户ip）。
*   macOS safari升级到11以上的版本，将移动设备设为开发调试模式，运行Xcode上的WebARonARKit，移动设备会自动打开AR浏览器，在浏览器地址栏输入项目运行的地址就可以看到AR效果啦。