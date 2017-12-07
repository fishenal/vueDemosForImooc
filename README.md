# vueDemosForImooc
慕课网课程的一些补充示例

1. 手把手搭建空白vue项目
2. 在vue项目里使用axios
3. 使用axios搭建模拟数据

1. 简单使用vuejs学习接口功能
2. 环境搭建：
  a. 环境准备
  b. 使用vue-cli初始化空白项目
  c. 安装axios进行数据请求
  d. 使用axios搭建模拟数据服务

a. 环境准备
第一步，安装nodejs，>=4.x, 6.x preferred https://nodejs.org/zh-cn/download/
第二步，安装git, https://git-scm.com/
第三步，启动终端shell，注意：如果命令找不到，变量配置

第四步，配置npm 中国镜像， https://npm.taobao.org/
 配置alias 
 alias cnpm="npm --registry=https://registry.npm.taobao.org \
--cache=$HOME/.npm/.cache/cnpm \
--disturl=https://npm.taobao.org/dist \
--userconfig=$HOME/.cnpmrc"
 使用 cnpm install ...
 
b.初始化空白项目
第一步，安装vue-cli cnpm install vue-cli -g, 注意： linux 系统下目录权限问题使用sudo, permission denied
 成功： All packages installed (254 packages installed from npm registry, use 26s, speed 115.83kB/s, json 287(446.47kB), tarball 2.55MB)
第二步，vue init <template-name> <project-name>
vue init webpack my-project
项目选项， 检查项目文件

第三步，安装项目依赖，注意，在当前项目目录下， cnpm install
第四步，启动项目， npm run start


* 下面的内容，是你的项目需要使用ajax，跟后台请求数据所需要安装和配置的东西

c，安装axios
项目目录下
cnpm install axios --save

使用Axios在项目里发送请求，在需要使用ajax的组件内，引用axios，根据标准接口使用，是Promise对象


d, 搭建一个模拟数据的服务
cnpm install mockjs --dev-save

