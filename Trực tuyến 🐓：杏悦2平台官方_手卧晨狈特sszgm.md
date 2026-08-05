杏悦2平台官方【Q-——333307——】杏悦2平台官方【 辋芷《888yx●vip》 】
杏悦2平台官方【Q-——333307——】杏悦2平台官方【 辋芷《888yx●vip》 】

 从零搭建个人博客：GitHub Pages + Hexo 完整教程（2025亲测有效）

> 你是否想过拥有一个完全属于自己的技术博客？不需要购买服务器，不需要备案，甚至不需要花一分钱——GitHub Pages 就能帮你实现。本文将手把手教你用 Hexo 框架搭建一个高性能的静态博客，整个过程只需 20 分钟。

 为什么要用 GitHub Pages 搭建博客？

在开始之前，我们先聊聊为什么这套方案如此受欢迎。GitHub Pages 是 GitHub 提供的免费静态网站托管服务，它具备三大核心优势：完全免费、支持自定义域名、全球 CDN 加速。配合 Hexo 这款基于 Node.js 的博客框架，你只需两条命令就能生成一个秒开的静态站点。

 环境准备：三分钟搞定所有依赖

第一步：安装 Node.js 和 Git
- 前往 [Node.js 官网](https://nodejs.org/) 下载 LTS 版本
- 下载 [Git](https://git-scm.com/) 并完成默认安装

第二步：全局安装 Hexo CLI
打开终端（Mac/Linux）或命令提示符（Windows），输入：
```bash
npm install -g hexo-cli
```
> 如果提示权限错误，Mac/Linux 用户请加 `sudo`，Windows 用户请使用管理员模式。

 实操部署：从零到上线只需五步

接下来是最关键的部署环节，请跟随我的节奏一步步操作：

1. 初始化博客项目
```bash
hexo init my-blog
cd my-blog
npm install
```

2. 本地预览
```bash
hexo server
```
访问 `http://localhost:4000` 即可看到默认博客。

3. 创建 GitHub 仓库
到 GitHub 新建仓库，命名为 `你的用户名.github.io`（务必完全一致）。

4. 关联部署
修改根目录下 `_config.yml` 文件中的 deploy 配置：
```yaml
deploy:
  type: git
  repo: https://github.com/你的用户名/你的用户名.github.io.git
  branch: main
```
然后安装部署插件并推送：
```bash
npm install hexo-deployer-git --save
hexo clean && hexo generate && hexo deploy
```

5. 验证上线
等待 2-5 分钟后，浏览器访问 `https://你的用户名.github.io`，看到博客说明已经成功部署。

 进阶优化：让博客真正属于你

基础部署完成后，你可能想换主题或绑定域名。推荐 NexT 主题（支持 Google Analytics、评论系统等丰富插件），绑定域名只需在仓库 Settings → Pages 中填写你的域名，并添加一条 CNAME 解析记录。

---

💬 互动时刻：你已经完成博客搭建了吗？在部署过程中是否遇到报错问题？欢迎在评论区留言，我会第一时间为你解答！也可以分享你的博客链接，我会挑选几位朋友的网站去参观学习。

📌 收藏提醒：这篇文章值得你点赞+收藏，后续换电脑重装环境时可以直接对照操作。关注我，下期将分享《Hexo 博客如何写文章及 Markdown 语法精讲》，我们不见不散！

---

本文已同步收录至作者博客，如需转载请联系授权。

相关推荐：

https://github.com/adamsjonathan8709/jjgpxy/blob/main/Th%E1%BB%83%20thao%20%E2%9A%BD%EF%B8%8F%EF%BC%9A%E6%9D%8F%E6%82%A62%E5%A8%B1%E4%B9%90%E5%B9%B3%E5%8F%B0_%E5%91%B3%E6%90%9C%E7%8C%8E%E4%B9%A0%E7%81%B8sflee.md

<img src="https://i.postimg.cc/1RVggNH7/xingyue2-00014.png" />

相关推荐：

https://github.com/adamsjonathan8709/jjgpxy/commit/8513c17578ba84f2e4c5fe6ad1572c27942a1396

<img src="https://i.postimg.cc/YS2Gjnnm/xingyue2-00001.png" />
相关推荐：

https://github.com/cooperjoseph0197/tdhpql/blob/main/Th%E1%BB%83%20thao%20%E2%9A%BD%EF%B8%8F%EF%BC%9A%E6%9D%8F%E6%82%A62%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91_%E7%97%88%E7%BA%AB%E6%8D%95%E9%94%A5%E9%9D%9Euanuo.md

<img src="https://i.postimg.cc/ZqYB077H/xingyue2-00002.png" />
相关推荐：

https://github.com/cooperjoseph0197/tdhpql/commit/be6cf4da3edad7b92ccfc015cdb27da2f35626e9

<img src="https://i.postimg.cc/4dqmLJJ8/xingyue2-00010.png" />

资讯来源：新华网、人民网、央视新闻、中新网、凤凰网、澎湃新闻、界面新闻、新浪新闻、搜狐网、财新网、观察者网、第一财经等主流平台，以独树一帜的观察视角与扎实的深度报道能力，在资讯领域收获广泛关注。
