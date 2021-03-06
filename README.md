# GDG Suzhou Website Source

本网站基于 hexo 构建静态网站。 目标：

- 一种活动发布渠道
- 往期活动回顾
- GDG Suzhou 各种官方沟通渠道汇总

*任何人*都可以 clone 后在本地重建网站。
**热切期待一起来共同构建 GDG Suzhou 社区网站。**
包括不限于:

- 提出网站修改意见
- 投稿，贡献文章、内容
- 维护网站

**欢迎随时提出任何问题**

## 欢迎完善问题

*[代办事项](TODO.md)*

## 使用 hexo 构建网站

[hexo 中文官网](https://hexo.io/zh-cn/)

```
# 安装 hexo
$ npm install hexo-cli -g

# 下载代码
$ git clone https://github.com/GDG-Suzhou/gdg-suzhou-org
$ cd gdg-suzhou-org

# 生成静态文件
$ hexo g
# 启动本地服务
$ hexo s
```

打开 http://localhost:4000 即可预览到网站啦
在 *source/_posts* 下修改已有文章，或者

```
# 新建文章，替换 <title> 为你的文章标题
$ hexo new post <title>
```

在 *source/_posts* 下 就会生成新文章，修改即可，完成后提交 PR 即可。

## Note

- 忽略部署配置或者其他一些不想要上传的内容[git 忽略某些行](https://stackoverflow.com/questions/16244969/how-to-tell-git-to-ignore-individual-lines-i-e-gitignore-for-specific-lines-of)

```
$ git config filter.gitignore.clean "sed '/# gitignore$/'d"
```
