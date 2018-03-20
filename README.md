# morepages

> A Vue.js project

基于vue-cli的多页面工程，对配置文件做一些调整后，可以轻松实现多页面。

### 1、首先安装glob，npm i glob -D

### 2、更改build包下的utils.js文件

### 3、更改build包下的webpack.base.conf.js文件

### 4、更改build包下的webpack.dev.conf.js文件

### 5、更改build包下的webpack.prod.conf.js文件

### 6、按src文件夹中的目录进行更改，包名须为pages，如果想用其它名字，请到utils.js中更改。每个页面的包名以及包内的文件名须一致

### 7、componenets包下为公共组件，assets包下为静态文件，这与之前的vue-cli一样

#### 以上更改的地方已在文件中说明，都用了多个“--”进行标识，正常运行与打包的命令与之前都一致

#### 注意点：在引入.vue文件的时候，必须写完整，如import Index from 'index.vue'，不能简写，否则会报错