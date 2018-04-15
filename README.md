#网上购物超市客户端



###  首先，列出我们需要的东西

  ```
node.js环境（npm包管理器）
vue-cli 脚手架构建工具
cnpm  npm的淘宝镜像
  ```

- 安装node.js
  1.下载node.js,直接从官网上下载，安装过程很简单，一路下一步就可以
  2.根据自己电脑选择32位/64位。安装好node，可以先进行下简单的测试安装是否成功了，``node -v``
- 安装cnpm
    - 由于npm有些资源被屏蔽或者是国外资源的原因，经常会导致用npm安装依赖包的时候失败，所有我还需要npm的国内镜像---cnpm
      在命令行中输入 ``npm install -g cnpm --registry=http://registry.npm.taobao.org``

- 安装webpack
    ``npm install webpack -g``

- 安装vue-li
    ``cnpm install vue-cli -g``
这个过程会耗时十几秒，等走完就好

好了，到此整个环境就搭建好了

### 运行项目

- 切换到项目目录下
- 运行项目之后安装依赖``npm  install``,安装成功后你会发现项目里多了个node-modules文件夹
- 执行命令``npm run dev``,项目就运行起来啦！:smile:





























