# IntelliJ IDEA 个人配置

使用方法： 

1. IntelliJ IDEA
2. File | Settings Repository指定远程仓库地址 (自己在github或者gitee上新建一个空的git仓库即可)
3. Overwrite Local or Overwrite Remote

## 常用配置

看这两个就行：

1. [IDEA的常见的设置和优化（功能）](https://blog.csdn.net/zeal9s/article/details/83544074)
2. [2020年最新-IDEA最详细配置（配图文收藏版配置）](https://www.bilibili.com/read/cv5707434/)

## 常用插件

| 序号 | 名称                           | 备注                                                         |
| ---- | :----------------------------- | ------------------------------------------------------------ |
| 1    | Alibaba Java Coding Guidelines | 阿里编程规范，可以检查自己的java命名规范编程规范以及bug，并会给出相应的解决方案 |
| 2    | Grep Console                   | 对控制台输出的不同级别的日志进行上色，比如info级别是黑色，WARN级别是黄色，ERROR是橙色。不用找日志把眼睛找瞎了。 |
| 3    | Kotlin                         | 项目中使用到了Kotlin可以安装，现idea默认已自带               |
| 4    | Lombok                         | 以简单的注解形式简化POJO，现idea默认已自带                   |
| 5    | Translation                    | 翻译                                                         |
| 6    | JRebel                         | 热加载插件，  代码改动之后无需重启服务，被修改的类会自动重新加载，破解请自行百度<br/>或者参考：[JRebel插件使用详解](https://blog.csdn.net/lianghecai52171314/article/details/105637251)<br/>修改完Java代码后，就可以通过快捷键 Ctrl+shift+F9 刷新项目 |
| 7    | CodeGlance                     | 类似于Sublime的右侧，整体代码滚动条，使用此插件可以查看缩略图一样，快速切换到自己需要去的地方~ |
| 8    | Rainbow Brackets               | 彩色括号匹配                                                 |
| 9    | Atom Material Icons            | 各种文件夹、文件图标                                         |
| 10   | .ignore                        | 生成各种模板化的git忽略文件                                  |
| 11   | MyBatis Log Free               | mybatis自己控制的参数编译有点反人类，选中需要转换的mybatis log日志，然后点击右键，选择Restore sql from slection<br/>这个版本免费：[地址](https://plugins.jetbrains.com/plugin/10065-mybatis-log-plugin) |
| 12   | Free Mybatis plugin 或 MybatisX | 生成mapper xml文件<br/>快速从代码跳转到mapper及从mapper返回代码<br/>mybatis自动补全及语法错误提示<br/>集成mybatis generator gui界面<br/>根据数据库注解，生成swagger model注解 |
| 13   | Maven Helper                   | 查找和排除冲突依赖项的简便方法                               |
| 14   | RestfulTool                    | 1.根据 URL 直接跳转到对应的方法定义 ( Ctrl \ or Ctrl Alt N );<br/>2.提供了一个 Services tree 的显示窗口;<br/>3.一个简单的 http 请求工具;<br/>4.在请求方法上添加了有用功能: 复制生成 URL;,复制方法参数...<br/>5.其他功能: java 类上添加 Convert to JSON 功能，格式化 json 数据 ( Windows: Ctrl + Enter; Mac: Command + Enter )。 |
| 15   | GenerateAllSetter              | 当你进行对象之间赋值的时候，你会发现好麻烦呀，能不能有一个更好的办法呢~ 有，只要你选中需要生成set方法的对象，按下快捷键 alt+enter |
| 16   | codota                         | 需联网使用，代码智能自动补全，比idea自带的提示还要详细，你甚至可以直接搜索一个词的类似用法，看看大神是怎么写的。 |
| 17   | IDE Eval Reset                 | 30天试用期无限循环（相当于破解）。<br/>1.添加第三方插件仓库`https://plugins.zhile.io`<br/>2.搜索：`IDE Eval Reset`插件进行安装<br/>3.在idea主界面help-->eval Reset点击重启idea<br/>或者参考：[idea 安装eval reset插件](https://blog.csdn.net/OracleOracolo/article/details/113886757) |

## 主题

- 默认的 吸血鬼 主题，完美~

![image.png](https://images.gitee.com/uploads/images/2019/0118/000955_8a1a2c2a_945727.png)

## 字体

* 推荐 JetBrains Mono
* IDEA应用字体 和 代码字体 设置：

![IDEA应用字体](https://images.gitee.com/uploads/images/2019/0118/000955_06dda8fd_945727.png)
![代码字体](https://images.gitee.com/uploads/images/2019/0118/000955_dd80cfab_945727.png)


## 代码模板 

### 类似 sysout

* Editor->General->Postfix Completion 

* Editor->Live Templates

相关配置见：[IDEA代码模板](https://blog.csdn.net/Yinyaowei/article/details/103836510)

![image.png](https://images.gitee.com/uploads/images/2019/0118/000956_1335a7b5_945727.png)

### 文件头注释

![image.png](https://images.gitee.com/uploads/images/2019/0118/000957_0a1a36f9_945727.png)

