# J1uT1an.github.io
J1uT1an的第一个项目--搭建一个属于自己的博客，中间有参考kelyu0的项目，表示感谢。
初代版本，后面学会更多的之后再进行修改迭代。

<h1 align="center">
  React Issue Blog
</h1>
<h2 align="center">
  A minimal personal blog system.
</h2>

## 👉参考kelyu0的项目 [Demo](https://kelyu0.github.io/)

- Front-end : `React` + `React-router`, bootstrapped with [Create React App](https://github.com/facebook/create-react-app).
- Get issues by `Github api` - [My articles repo](https://github.com/J1uT1an/article/issues)
- Deploy with `Github pages` - [My github.io repo](https://github.com/J1uT1an/J1uT1an.github.io)

## 🔥 Features

- Syntax/Code Highlighting
- Article anchor navigation
- Responsive
- Back to the top
- Jump to github comments

## 🌱 Minimalist

Minimalist page, minimal code. Use the most streamlined code to achieve the most needed functions.

- 3 Pages：Issue list, Issue content, About
- 5 Files：Posts.js, Post.js, PostContent.js, About.js, Catalog.js

## 🚀 Usage

### Local preview

```
  git clone git@github.com:J1uT1an/J1uT1an.github.io.git
  cd react-issue-blog
  npm install
  npm run start
```

Open http://localhost:3000 to view it in the browser.

### Customize

Change the content in src/config.js and customize it as your blog.

```js
export const config = {
  // Your Github UserName
  githubUserName: "J1uT1an",
  // Your Github Repo Name Where You Have your issues as Blog
  githubRepo: "article",
  // About Page links
  thirdPartySite: [
    {
      href: "mailto:1031894647@qq.com", // third Party Site url
      title: "1031894647@qq.com", //
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
```

### build

    npm run build  # Compiles and minifies for production
