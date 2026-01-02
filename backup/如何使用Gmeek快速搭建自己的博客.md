大家好我是SYSTEM-WIN20-HJL，有时我们想分享一些技术的教学时，往往会想搞一个自己的个人博客，今天我来教大家怎么快速搭建一个自己的个人博客

### 1.创建仓库
首先进入[GitHub首页](https:\\www.github.com)，点击右上角sign up，注册一个GitHub账号。注册好后点击搜索框，搜索`Gmeek`找到[Meekdai/Gmeek](https://github.com/Meekdai/Gmeek)，点开项目后往下拉，会看到一个`使用模板创建仓库`，点进去，再点击创建，这样就成功创建好了一个博客的框架。

### 2.打开GitHub Pages
打开`settings`一栏在左侧列表找到Pages，点击它，右面选择`GitHub Actions`，这样GitHub Pages就打开了。如果想用自定义域名，就在下面的`Custom Domain`处填入你的域名，点击Save，来到你的域名提供商的DNS这里，新建一个`CNAME`值，把你的域名作为<你的GitHub用户名>.github.io。

### 3.修改配置
在仓库文件区域，找到并点击`config.json`，修改里面的信息，如标题、副标题、介绍等，然后点击提交。点击上面的`Actions`一栏，在左侧找到`build gmeek`，然后运行这个action，运行完之后会有个√，这时就完成基本构建了。

### 4.撰写文章
如果你想要编写文章，那么只要在仓库的issue里提交就可以了，同时，他还支持markdown语法

### 5.总结
以上就是使用Gmeek搭建自己的个人博客的所有内容了，是不是很简单？如果这篇文章对你有帮助，那就上bilibili给SYSTEM-WIN20-HJL点个关注吧，你的支持是我更新内容最大的动力！