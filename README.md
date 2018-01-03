# wepy-mark
仿原生应用 Mark 的小程序

[小程序原生版 weapp-mark](https://github.com/Hongye567/weapp-mark)

# 建设中...

### 运行

1. 全局安装 WePY 命令行工具

 如果你已经使用过 [wepy](https://tencent.github.io/wepy/) 可以忽略这一步

 ```bash
 $ npm install wepy-cli -g
 ```

2. 编译

 使用命令行进入项目根目录进行实时编译

 ```bash
 $ wepy build --watch
 ```

3. 预览

 编译后会在项目根目录下生成 dist 文件夹，使用微信开发工具打开 dist 文件夹即可预览。

**重要提醒：**

1. 使用微信开发者工具 --> `添加项目`，`项目目录` 请选择 `dist` 目录。

2. 微信开发者工具 --> `项目` --> `关闭 ES6 转 ES5`。<font color='red'>重要：漏掉此项会运行报错。</font>

3. 微信开发者工具 --> `项目` --> `关闭上传代码时样式自动补全`。<font color='red'>重要：某些情况下漏掉此项也会运行报错。</font>

4. 微信开发者工具 --> `项目` --> `关闭代码压缩上传`。<font color='red'>重要：开启后，会导致真机 computed, props.sync 等等属性失效。</font>
