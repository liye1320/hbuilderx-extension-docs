# HBuilderX插件安装失败解决方案

插件安装失败，可能有各种各样的原因。当出现插件安装失败，又没有明确提示相关错误时，点击菜单【帮助】【查看运行日志】，看下日志中的错误。根据具体错误来解决问题

## 问题：npm install执行失败

某些nodejs插件，比如`less`、`eslint-js`插件，插件zip包没有自带node_modules。

从插件市场导入此类插件后，HBuilderX会自动安装node_modules，如果node_modules安装失败，会导致插件安装失败。

##### 解决方案

以`less`插件为例：打开HBuilderX安装目录，进入`plugins/compile-less`目录，看下目录下是否存在`node_modules`。

如果不存在，在终端打开此目录，手动执行`npm install`