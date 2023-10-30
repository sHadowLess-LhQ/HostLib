HostLib

#### 软件架构

升级满帮集团开源插件库框架宿主库

### 缘由

原框架AGP版本低，不支持很多新特性（尤其是ViewBinding），升级到AGP 7.0.2

但原框架支持剔除公共库的AGP插件，升级后无法使用

（太菜了，不会写基于7.0.2的AGP插件）

Step 2. 添加依赖

a、克隆引入

直接下载源码引入model

b、远程仓库引入

[![](https://jitpack.io/v/com.gitee.shadowless_lhq/host-lib.svg)](https://jitpack.io/#com.gitee.shadowless_lhq/host-lib)

```
     dependencies {
          implementation 'com.gitee.shadowless_lhq:host-lib:Tag'
     }
```

### 使用方法

具体使用方法参照原项目使用方法：

[Phantom — 唯一零 Hook 稳定占坑类 Android 热更新插件化方案](https://github.com/ManbangGroup/Phantom)
