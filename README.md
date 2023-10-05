## Readme

- [生成代码]([Willjay5991/root.github.io: Personal website](https://github.com/Willjay5991/root.github.io))
- 本项目中只包含` _site`中生成的文件





## 个人网页-制作-发布-记录

**生成静态网页文件**

----

- fork [王晋东主页仓库]([jindongwang/jindongwang.github.io: Personal website](https://github.com/jindongwang/jindongwang.github.io))

- 参照[链接](https://blog.csdn.net/qq_36816662/article/details/128314516) 安装ruby， gem， jekyll等必要的本地文件
- 修改`_config.yml`中对应的内容
- 执行` jekyll build`生成对应的静态网页文件`./_site/*`
- 切换到`_site/.`目录下，执行`jekyll serve`, 在浏览器中就能访问已经生成的网页了，这样执行不必重新编译，速度较快

---



**gitub发布静态文件**

---

- 新建仓库, 名字为`yourgithubID.github.io`
- clone到本地，并把上面生成的`_site`中的所有内容，放置到本地仓库文件夹中`yourgithubID.github.io`, 推送仓库到github
- 设置**setting**---**pages**----**source**----'main/root'
- 等待github自动发布，发布成果后“github page” 下会提示“your site is live at xxxx”
- 后续每次推送都会延迟发布，耐心等待
