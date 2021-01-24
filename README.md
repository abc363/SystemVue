
vue项目整体结构

（1）从github地址clone下来后执行npm install安装
（2）执行npm install vue-quill-editor --save语句安装富文本编辑器

（3）UI框架是用的Element UI。
（4）图片放在src/img和static/img和assets/icon中，可能有些乱。
（5）Axios请求封装文件在src/scripts/utils/helper.js中。
（6）一些vue的全局变量、方法写在src/main.js中。
（7）src/components是最主要的目录文件，所有组件都放在这里。
（8）路由放在src/router/index.js中。

登陆页---Login.vue
注册页---Resigter.vue
后台主页---Index.vue
首页菜单---home.vue
产品管理菜单---Product.vue
产品新增修改弹框---product-card.vue
文件上传组件---uploadFile.vue
新闻管理菜单---news.vue
新闻新增修改弹框---news-card.vue
个人信息---personal.vue
销售情况---sale.vue

npm run dev进行本地调试
npm run build是打包命令，打包生成的BackNode文件夹可以放在服务器中。（在服务器中重新命名就好）

git 上传
git add .
git commit -m "xxx"
git push