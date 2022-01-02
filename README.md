

rn-code-seek(寻码工具)使用说明
=========

## 描述

  快速定位到当前点击的源码地址（支持到class级别），提高开发效率。
### 使用方式一 —— 整包替换
npm i rn-code-seek。
下载rn-code-seek,替换react-native包。
### 使用方式二 —— 文件替换
替换两个文件
1. node_modules/react-native/Libraries/Components/Touchable/Touchable.js
2. node_modules/react-native/Libraries/Renderer/implementations/ReactNativeRenderer-dev.js

