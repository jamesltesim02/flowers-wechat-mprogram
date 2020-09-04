## 目录结构  
    ┌─cloudfunctions        云函数目录（阿里云为aliyun，腾讯云为tcbuniCloud） 
    │─components            符合vue组件规范的uni-app组件目录  
    │  └─comp-a.vue         可复用的a组件  
    ├─hybrid                存放本地网页的目录  
    ├─platforms             存放各平台专用页面的目录  
    ├─pages                 业务页面文件存放的目录  
    │  ├─index  
    │  │  └─index.vue       index页面  
    │  └─list  
    │     └─list.vue        list页面  
    ├─static                存放应用引用静态资源（如图片、视频等）的目录，注意：静态资源只能存放于此  
    ├─wxcomponents          存放小程序组件的目录  
    ├─main.js               Vue初始化入口文件  
    ├─App.vue               应用配置，用来配置App全局样式以及监听 应用生命周期  
    ├─manifest.json         配置应用名称、appid、logo、版本等打包信息  
    └─pages.json            配置页面路由、导航条、选项卡等页面类信息  