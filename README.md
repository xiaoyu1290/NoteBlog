# 1.环境要求
+ OS：支持Mac/Linux/Windows及一切支持Java运行环境的操作系统
+ Java版本：JDK8及以上
+ 数据库：MySQL数据库（5.7及以上）
-----
# 2.项目信息
## 项目技术
+ `SpringBoot `
+ `Mybatis`
+ `Spring Data JPA`
+ `Maven`
+ `Hutool`
## 功能展示
+ 待完善...

-----
# 3.更新日志
## 说明
+ [^]：更新/修复的功能，[+]：新增的功能，[-]：移除的功能

### v4.0.0(20180707)
+ [^] 更新`SpringBoot`至最新版 2.0
+ [^] 更新`layui`版本至最新 2.3
+ [^] 根目录包名更改为 \[*.v4\] 
+ [+] 增加初始化配置页面，方便上手配置
+ [+] 后台增加对字数的统计
+ [-]  移除对`h2`数据库的支持
+ [-]  移除`template`模块，改用`Spring Data JPA`
### v3.3.1(20180407)
+ 修复发布笔记页面和关于内容页面的富文本编辑器加载失败的BUG
+ 修复用户管理不能搜索的BUG
+ 修复博文管理中浏览数显示错误的BUG
+ 增加笔记管理中点击标题可以直接访问笔记前端显示内容的功能
+ 加强评论的sql和xss过滤条件
### v3.3.0(20180324)
+ 修复修改文章封面会同时修改管理员头像的BUG
+ 修复某些手机浏览器上页面显示不全的BUG
+ 重新加入mysql，现在可以h2/MySQL二选一啦
### v3.2.0(20180317)
+ 更新相关模块依赖为最新1.11.0.RELEASE版
+ 扩大参数表的值字段的长度
+ 数据库由独立mysql改为Embedded H2 ，方便部署和备份
+ 首页\[网站信息\]面板和\[会员登录\]面板显示可调整顺序设定
+ 调整优化相关代码，解决部分潜在的问题
+ 修复留言的xss漏洞
### v3.1.0(20180226)
+ 新增 留言 功能，右下角的 fixBar 图标点击进入留言板块页面
+ 更新 `template` 依赖至最新快照版本
+ 优化验证评论开放是否的代码，防止恶意评论
+ 修复管理员回复时用户名颜色错误以及认证标识未显示问题
+ 修复评论偶尔不能正确屏蔽的问题
+ 修复后台管理中评论管理内容偶尔显示有误的问题
### v3.0.2(20180224)
+ 优化文章置顶的排序代码
+ 修复文章浏览数统计和点赞统计问题
+ 优化编辑文章时候的Nkeditor的默认字体
### v3.0.1(20180223)
+ 更新相关依赖模块至最新
+ 修改后台编辑器(NKeditor)初始化默认字体样式，以及默认字体大小为14px
+ 修正日志文件大小分割功能
+ 修正页脚在内容不是很多时的位置显示问题
+ 优化部分代码
### v3.0.basic(20180216)
+ 笔记博客v3第一版发布