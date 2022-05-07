#   				React Issue Blog

#   A minimal personal blog system.

- Get issues by `Github api` - [My articles repo](https://github.com/J1uT1an/article/issues)
- Deploy with `Github pages` - [My github.io repo](https://github.com/J1uT1an/J1uT1an.github.io)

项目介绍

​	功能

- 代码高亮
- 响应式
- 文章锚点导航
- 回到顶部
- 评论跳转
- 极简
- 页面极简，代码极简。用最精简的代码，实现最需要的功能。

3个页面：Issue list, Issue content, About
5个文件：Posts.js, Post.js, PostContent.js, About.js, Catalog.js
定义成你的博客
本地预览

> git clone [git@github.com](mailto:git@github.com):J1uT1an/J1uT1an.github.io.git
>
> cd react-issue-blog
>
> npm install
>
> npm run start

浏览器打开 [http://localhost:3000](https://link.segmentfault.com/?enc=WA5Uf2USSj6A8%2BXGutQArw%3D%3D.3od3Prslobtv5UBOlJnD4XZaAQefhsss3cP5L81bwUQ%3D) 即可本地启动。

自定义
更改src/config.js中的内容，自定义成为你的博客（需要在github上有一个带issues的repository）。

export const config = {
	// Your Github UserName
	githubUserName: "J1uT1an",
	// Your Github Repo Name Where You Have your issues as Blog
	githubRepo: "article",
	// About Page links
	thirdPartySite: [
	{
		href: "mailto:[1031894647@qq.com](mailto:1031894647@qq.com)", // third Party Site url
		title: "[1031894647@qq.com](mailto:1031894647@qq.com)", //
	},
	{
		href: "https://github.com/J1uT1an",
		title: "GitHub",
	},
	{
		href: "https://space.bilibili.com/504823243?spm_id_from=333.1007.0.0",
		title: "MyBilibili",
	},
	//Other sites ...
	],
	porject: {
		reactblog:'https://github.com/J1uT1an/J1uT1an.github.io'
	},
};

构建和部署
	构建：

> npm run build 生成 build 文件夹

​	部署：

1. 在 Github 上新建一个名为 github.your_username.io 的仓库
2. 将build文件夹之中的内容拷贝到 github.your_username.io 仓库下，推送到远程。
3. 访问 github.your_username.io