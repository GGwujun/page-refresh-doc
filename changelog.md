# 更新日志

## 20170918

- 更新版本 `1.0.5`

    - 增加 `getPosition` API，可以获取当前滚动位置

## 20170916

- 更新版本 `1.0.4`

    - 修复`iOS Webview`下特定场景下拉刷新回弹时会有黑屏的BUG
    
    - `Core`内部增加`_resetUpLoadingHook`

## 20170913

- 更新版本 `1.0.3`

    - 修复`Npm`引入与文件`UMD`引入方式冲突问题
    
    - 去除`Npm`发布项目中的无用依赖，改到`dev`中

## 20170907

- 更新版本 `1.0.2`

    - 增加`isUseBodyScroll`配置，使用`body`的`scroll`事件来实现上拉，在特殊场景下有用
    
    - 增加`dampRateBegin`配置，设置下拉小于`offset`时的阻尼系数
    
    - 增加`mui透明导航栏嵌套`示例

## 20170906

- 更新版本 `1.0.1`

    - 增加横向滑动配置
    
    - 增加`default`主题设置下拉成功提示

## 20170902

- 发布版本 `1.0.0`

## 20170831

- 提供基础文档

## 20170830

- 内存版本`0.04`，代码基本完成，示例基本提供，剩余文档

## 20170821

- 用`GitBook`构建API文档框架