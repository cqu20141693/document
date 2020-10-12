- [1. visual stdio code 使用手册](#1-visual-stdio-code-使用手册)
  - [1.1. 快捷键](#11-快捷键)
  - [1.2. 插件](#12-插件)
    - [1.2.1. markdown plugin](#121-markdown-plugin)
    - [1.2.2. git plugin](#122-git-plugin)
    - [1.2.3. vue plugin](#123-vue-plugin)
- [2. 附录](#2-附录)
  - [2.1. 插件使用](#21-插件使用)
  - [2.2. 用户自定义settings](#22-用户自定义settings)

### 1. visual stdio code 使用手册

#### 1.1. 快捷键

1. ctrl + ` : 打开终端
2. ctrl + shift + P : 打开命令面板
3. alt + shift + f : 格式化文档
4. ctrl + [或者] ： 可以左右移动代码块

``` code
输入settings ： 打开用户settings.json 可以进行自定义配置

```

#### 1.2. 插件

##### 1.2.1. markdown plugin

1. markdown-formatter

``` code
    可以格式化代码： alt + shift + f
    可以自动生成提示：ul img tab
```

2. Markdown Preview enhanced
  
   1. 
      ``` code

          ctrl + shift + v ： previe 和源代码切换查看
          直接打开命令面板： 输入export 即可选择输入各种文件类型

          ctrl + k v：打开右侧预览，先同时按ctrl + k ,然后按v 即可,也可以右击选择
          打开右侧预览后的新功能：    
          可以右击输出各种格式的文件
          打开命令面板： 
          输入命令 image helper 快速引入图片,并会将图片放入assert中
      ```
   2. ![GetImage](/assets/GetImage.jpg)
  
3. Markdown All in One
  
  1. ![img](../assets/GetImage.jpg)
  2. 功能介绍
      ``` code

          打开命令面板： 
          输入命令： all in creat content 生成目录
          输入命令： all in update section number 更新序号
          输入命令： all in update content 更新目录
          
          列表提示： 比如直接从目录一 enter 后自动生成目录二
          图片导入提示：当输入图片路径的时候会有一定的搜索能力
      ```

##### 1.2.2. git plugin

1. GitHub Authentication

``` code
  授权后可进行
  git clone
  提交和撤回最新一次提交
  推送，拉取，合并代码
  分支创建和删除

  通过打开命令面板： 输入create/remve/push/pull/fetch/merge/clone/undo last commit
```

2. GitLens

``` code
  可以直接查看每一行代码最近修改的记录
  可以直接查看提交记录和每个文件的提交记录

```

##### 1.2.3. vue plugin

### 2. 附录

#### 2.1. 插件使用

1. 看插件官方文档
2. 通过命令命令面板查看插件快捷功能 

#### 2.2. 用户自定义settings

1. 对user->setting.json 进行配置
