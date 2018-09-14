这是wps项目的前端开发环境模板。

### 特性

    * 支持less解析
    * 支持浏览器兼容前辍处理
    * 支持require.js模块化开发
    * 支持文件版本管理，name.[ext]?v=[hash]
    * 自动启动服务器，自动监听文件修改，刷新浏览器实时预览效果

### 使用说明

    因为项目特殊，有一步是处于前后端混合开发的时候，所以该模板有三种流程：

    1 静态开发流程，只做纯样式，静态JS效果,对应命令行 npm run static
    2 混合开发流程，开始进入后端环境，与后端联调,对应命令行 npm run dev
    3 发布构建流程，产出正式上线的文件，与后端联调,对应命令行 npm run build
