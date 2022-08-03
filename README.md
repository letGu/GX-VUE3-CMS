CMS :内容管理系统
基于webpack打包
vite 有一些问题还未解决 比如热更新什么的
vue cli  默认集成vite 时 就可以使用vite了
vuex状态管理

> Vue3Admin 是基于Vue3、Vuex、VueRouter、ElementPlus、TypeScript、Echarts5等后台系统解决方案

### 技术栈：
开发工具：Visual Studio Code
编程语言：TypeScript4.x + JavaScript
构建工具：vite2.x / Webpack
前端框架：Vue3.x
状态管理：Vuex4.x
UI框架：Element ElementPlus
可视化：Echart5.x
富文本：WangEditor
工具库：@vueuse/core + dayjs + countup.JavaScript
数据模拟：mock.js
CSS预编译：Sass/Less
HTTP工具：Axios
Git Hook 工具：husky
代码规范：EditorConfig + Prettier + ESLint
提交规范：Commitizen + Commitllnt
自动部署：CentOS + Jenkins + Nginx

生产环境依赖


vue create vue3-ts-cms



# 查看自己的安装源
npm config get registry
 
# 更换npm源为国内淘宝镜像
npm config set registry http://registry.npm.taobao.org/
 
# 或者更换为国内npm官方镜像
npm config set registry http://registry.cnpmjs.org/
 
# 还原npm源
npm config set registry https://registry.npmjs.org/