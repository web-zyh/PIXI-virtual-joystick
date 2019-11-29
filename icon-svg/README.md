# icon 
## Project setup
```
# 首先添加阿里巴巴图标库到自己的项目中。然后下载到本地。
# 删除掉文件中带有demo的文件。
# vue项目中。在assets文件夹下创建iconfont文件夹，并把剩下的文件复制到里边即可

 * 引入阿里巴巴图标库
 * Unicode 引入 iconfont.css文件 例如
    <span class="icon iconfont"> &#xe624; </span>
 * Font classy 引入 iconfont.css文件 例如
    <i class="iconfont iconzu6"></i>
 * Symbol 引入 iconfont.js  例如
     <svg class="icon" aria-hidden="true"> <use xlink:href="#iconzu7"></use></svg>

引入iconfont.cs和iconfont.js文件
并引入icon-svg组件

* 全局注册icon-svg
Vue.component('icon-svg', IconSvg)
* 页面使用
<icon-svg icon-class="iconseachx"/>
