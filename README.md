# HostLib

#### 软件架构

升级满帮集团开源插件库框架宿主库

### 缘由

原框架AGP版本低，不支持很多新特性（尤其是ViewBinding），升级到AGP 7.0.2

但原框架支持剔除公共库的AGP插件，升级后无法使用

（太菜了，不会写基于7.0.2的AGP插件）

### 安装教程

Step 1. 添加maven仓库地址和配置

```
     //旧AndroidStudio版本
     //build.gradle
     allprojects {
         repositories {
            ...
             maven { url 'https://jitpack.io' }
         }
     }
     
     //新AndroidStudio版本
     //settings.gradle
     dependencyResolutionManagement {
          repositoriesMode.set(RepositoriesMode.FAIL_ON_PROJECT_REPOS)
          repositories {
            ...
             maven { url 'https://jitpack.io' }
          }
      }
```

Step 2. 添加依赖

a、克隆引入

直接下载源码引入model

b、远程仓库引入

[![](https://jitpack.io/v/sHadowLess-LhQ/HostLib.svg)](https://jitpack.io/#sHadowLess-LhQ/HostLib)
[![](https://jitpack.io/v/sHadowLess-LhQ/CommonLib.svg)](https://jitpack.io/#sHadowLess-LhQ/CommonLib)

```
     dependencies {
         implementation 'com.github.sHadowLess-LhQ:HostLib:Tag'
         implementation 'com.github.sHadowLess-LhQ:CommonLib:Tag'
     }
```

#### 使用说明

### 使用方法

具体使用方法参照原项目使用方法：

[Phantom — 唯一零 Hook 稳定占坑类 Android 热更新插件化方案](https://github.com/ManbangGroup/Phantom)
