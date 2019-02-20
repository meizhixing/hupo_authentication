### 第一阶段：前后端分离，微服务化
原来的博客系统，分成三部分：注册登录中心前后端，Blog。
```
mkdir hupo_pc
cd hupo_pc
npm init -y
git init
git status
git add ......
git commit ......
git 
```
拷贝代码，然后部署起来，包括
各种依赖包的 npm install ... --save，或者 --save-dev
以及.bowerrc配置路径，bower install ... --save，
不过bootstrap,jquery，可以使用CDN加速（如 https://www.bootcdn.cn/），不一定要放到自己的代码中来。
以后部署时可以
```
npm install 
bower install
```
另外，还需要配置.gitignore，忽略node_modules和bower_components。

