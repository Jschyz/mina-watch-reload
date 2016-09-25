#微信小程序开发监听文件改变自动编译

<img src="https://cloud.githubusercontent.com/assets/876707/18773863/cca59fae-8185-11e6-9d7b-050ba646b456.png" width = "172" height = "150" alt="LOGO" align=center />

##介绍
微信小程序IDE0.9版本功能还没完善，比如监听并自动编译、SASS预编译（wxss理解成css的子集）。开发不够便利，冲着极客精神，发现IDE发现IDE界面实现原理上基本都是[React](https://github.com/facebook/react) ＋ [monaco](https://github.com/Microsoft/monaco-editor)实现的。 

##下载声明

* 相关代码纯属技术研究与爱好，请在学习使用后删除
* 当微信官方提供正式版本后，请支持微信官方，一起把应用号做的更好

##破解步骤

***Mac测试可用，Windows测试可用***

1. 下载开发工具，并安装（***注意：一定要安装0.9版本***）
2. 打开『微信Web开发者工具』的程序目录
  * Windows：使用资源管理器查看
  * Mac：右键点击图标，选择『显示包内容』
3. 进入程序目录后，替换以下文件：
  * Windows：
    * \package.nw\app\dist\components\sidebar\sidebar.js
  * Mac：
    * /Resources/app.nw/app/dist/components/sidebar/sidebar.js

  **[替换的文件点击这里下载](https://github.com/Jschyz/mina-watch-reload/archive/master.zip)**

##效果截图

![IDE](https://raw.githubusercontent.com/Jschyz/mina-watch-reload/master/watch-reload.gif)
