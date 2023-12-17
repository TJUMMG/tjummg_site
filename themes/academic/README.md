# Additional README

## （中文）关于这个repo你可能想知道这些问题

### 1. 这个仓库是什么？

这个仓库是 Hugo academic theme 的一个fork，并且版本被退回至 commit id: 464a10d94741d532a3fdd77f3d6f206b739b40c5
（由于这个仓库与[原仓库](https://github.com/wowchemy/wowchemy-hugo-modules)的发展方向完全不同，未来不会向原仓库提交PR，且为了更方便地添加说明文字，本仓库已由fork转换成standalone）

*选择退回这个版本是因为academic主题的开发者在这次commit前修复了一个感知明显的bug——导航栏明暗模式显示问题。并且目前 (2021.7.2) 这个主题新旧版在核心功能上没有太大差别，旧版也足够好用。

### 2. 为什么要建立这个仓库？

Hugo academic 主题的开发者对这个主题进行了一次比较大的改动。新版的Hugo academic 主题使用[Hugo Modules](https://gohugo.io/hugo-modules/)，这使得搭建博客变得“更简单”，但也使用户几乎无法进一步定制这个主题，之后会举一个例子。而这个版本使用“传统的”Hugo themes，用户自由度更高。

### 3. 如何使用这个主题？

正如上面说的：这个版本使用“传统的”Hugo themes。所以只需：

* 下载/clone这个repo至博客的`themes/academic`目录（如果clone，记得把文件夹重命名为`academic`，并删除`.git`）
* 复制`exampleSite`到博客根目录
* `hugo server`预览效果
* 修改&定制你的主页...

请注意，你需要确保你使用的是**Hugo extended**，这个主题在“hugo extended v0.83.1”上实测可用，更旧一些的版本应该也会可用，但一定要使用Hugo **extended**。

### 4. 如何定制这个主题，有文档吗？

没有“直接的”文档。Hugo academic 主题的开发者把旧版的文档删除了，并且他们似乎在有意将自己与Hugo剥离（新版主题已经不附带指向Hugo官网的链接了）。

旧版和新版在feature上并没有很大差别（核心feature基本一致），[新版的文档](https://wowchemy.com/docs/)有很大的参考价值。

当然，我认为最快速的方法是直接阅读并修改exampleSite，里面提供的注释还算详细。

你需要修改全部文件都在博客根目录的以下文件夹中：

* config (很重要)
* content
* static

### 5. `api-cn`分支是什么？

原主题使用的部分api在中国大陆访问不稳定，导致网站访问速度很慢。我将这些造成“访问速度慢”的api替换成了国内的镜像。具体修改请看[这个issue](https://github.com/Chen-Gary/hugo-theme-academic-old/issues/2)。

如果你认为访问你主页的人大多来自中国大陆，请考虑使用`api-cn`分支的主题。

### 6. 这个主题适合那些人？

[新版academic主题](https://wowchemy.com/)做的很棒，按官方教程几乎对代码/命令没有要求，强烈建议大家试试。如果你仍然想要使用旧版主题，你可能是这样的人：

* 首先，当然你想要搭建一个个人学术主页
* 有一定使用Hugo的基础（没有基础的话可以参考Hugo官网的教程；也可以看我写的[教程](https://www.garychen.top/post/building-blog-using-hugo/)）
* 不介意折腾（因为没有文档）
* 有自定义主题的需求
* 补充上条，如果你想要修改主题中的部分api来达到提高地区访问速度的效果（参考/直接使用`api-cn`分支的主题）
* 不急于使用最新的feature，不介意使用旧版

### 7. 这个仓库会更新academic主题的最新feature吗？

不会。。。前端也太难了吧😭

真的很感谢 Hugo academic theme 的团队，他们把这个主题开发得非常很棒。请访问他们[最新的网站](https://wowchemy.com/)，看看他们提供的服务是否符合你的需求。


## (English) You may want to know the following about this repo

Well... If you do not read Chinese, the key point is this repo is the **old version** of Hugo academic theme. Like other "traditional" Hugo themes, clone this repo to `themes/` in the root folder of you blog, rename it to "academic", and delete `.git`. Then you are free to go.

This repo is tested in **hugo extended v0.83.1**, and you may expected it works in some other Hugo versions. But make sure you are using **Hugo extended**.

I have explained why you may need the old version of Hugo academic theme above in Chinese. If you really want to read the details, please try Google translate at this point. I will try to provide the English translation... Maybe... Or may not...

(As you found this repo, you have got your own reasons why to choose the old version right? 😏)

This repo is made **standalone** instead of a fork now. Since this repo parts ways with the [original one](https://github.com/wowchemy/wowchemy-hugo-modules) and will not open any PR to the original repo, making it standalone allow me to add additional specifications easier. 

I really want to thank the great work by the team of Hugo academic theme. Please check their [new website](https://wowchemy.com/), and see if that suits your needs.








---

(以下为原README / The original README as follow)

<p align="center"><a href="https://sourcethemes.com/academic/" target="_blank" rel="noopener"><img src="https://sourcethemes.com/academic/img/logo_200px.png" alt="Academic logo"></a></p>

# [Academic](https://sourcethemes.com/academic/): the website builder for [Hugo](https://gohugo.io)

### The Page Builder to Easily Create Professional Websites :pencil2: :newspaper: :rocket:

**Create _any_ kind of website for free with Academic using Markdown, Jupyter, or RStudio. Choose a beautiful color theme and build anything with the Page Builder - over 50 _widgets_, _themes_, and _language packs_ included!**

[Check out the latest **demo**](https://academic-demo.netlify.app) of what you'll get in less than 10 minutes, or [view the **showcase**](https://sourcethemes.com/academic/user-stories/) of personal, project, and business sites.

- 👉 [**Get Started**](https://sourcethemes.com/academic/docs/install/)
- 📚 [View the **documentation**](https://sourcethemes.com/academic/docs/)
- 💬 [Chat with the **Academic community**](https://spectrum.chat/academic) or [**Hugo community**](https://discourse.gohugo.io)
- :heart: **Support development** of Academic:
  - :heart: [**Become a backer** on GitHub or Patreon to **unlock rewards and extra features**](https://sourcethemes.com/academic/plans/)
  - ☕️ [**Donate a coffee**](https://paypal.me/cushen)
  - :woman_technologist: [**Contribute**](https://sourcethemes.com/academic/docs/contribute/)
- 🐦 Twitter: [@source_themes](https://twitter.com/source_themes) [@GeorgeCushen](https://twitter.com/GeorgeCushen) [#MadeWithAcademic](https://twitter.com/search?q=%23MadeWithAcademic&src=typd)
- 💡 [Request a **feature** or report a **bug**](https://github.com/gcushen/hugo-academic/issues)
- ⬆️ **Updating?** View the [Update Guide](https://sourcethemes.com/academic/docs/update/) and [Release Notes](https://sourcethemes.com/academic/updates/)

[![Screenshot](https://raw.githubusercontent.com/gcushen/hugo-academic/master/academic.png)](https://github.com/gcushen/hugo-academic/)

**Key features:**

- **Page builder** - Create *anything* with [**widgets**](https://sourcethemes.com/academic/docs/page-builder/) and [**elements**](https://sourcethemes.com/academic/docs/writing-markdown-latex/)
- **Edit any type of content** - Blog posts, publications, talks, slides, projects, and more!
- **Create content** in [**Markdown**](https://sourcethemes.com/academic/docs/writing-markdown-latex/), [**Jupyter**](https://sourcethemes.com/academic/docs/jupyter/), or [**RStudio**](https://sourcethemes.com/academic/docs/install/#install-with-rstudio)
- **Plugin System** - Fully customizable [**color** and **font themes**](https://sourcethemes.com/academic/themes/)
- **Display Code and Math** - Code highlighting and [LaTeX math](https://en.wikibooks.org/wiki/LaTeX/Mathematics) supported
- **Integrations** - [Google Analytics](https://analytics.google.com), [Disqus commenting](https://disqus.com), Maps, Contact Forms, and more!
- **Beautiful Site** - Simple and refreshing one page design
- **Industry-Leading SEO** - Help get your website found on search engines and social media
- **Media Galleries** - Display your images and videos with captions in a customizable gallery
- **Mobile Friendly** - Look amazing on every screen with a mobile friendly version of your site
- **Multi-language** - 15+ language packs including English, 中文, and Português
- **Multi-user** - Each author gets their own profile page
- **Privacy Pack** - Assists with GDPR
- **Stand Out** - Bring your site to life with animation, parallax backgrounds, and scroll effects
- **One-Click Deployment** - No servers. No databases. Only files.

## Themes

Academic comes with **automatic day (light) and night (dark) mode** built-in. Alternatively, click the sun/moon icon in the top right of the [Demo](https://academic-demo.netlify.app) to set your preferred mode!

Choose a stunning theme for your site and [customize it](https://sourcethemes.com/academic/docs/customization/#custom-theme) to your liking:

[![Themes](https://raw.githubusercontent.com/gcushen/hugo-academic/master/images/themes.png)](https://sourcethemes.com/academic/themes/)

[Browse more themes...](https://sourcethemes.com/academic/themes/)

## The Future of Technical Content Writing

[![Writing technical content](https://sourcethemes.com/academic/img/docs/writing-technical-content.gif)](https://academic-demo.netlify.apppost/writing-technical-content/)

## Ecosystem

* **[Academic Admin](https://github.com/sourcethemes/academic-admin):** An admin tool to import publications from BibTeX or import assets for an offline site
* **[Academic Scripts](https://github.com/sourcethemes/academic-scripts):** Scripts to help migrate content to new versions of Academic

## Create your site

You can choose from one of the following four methods to install:

* **one-minute Github/Gitlab install using your web browser (recommended)**
* install on your computer using Git with the Command Prompt/Terminal app
* install on your computer by downloading the ZIP files
* install on your computer with RStudio

### Create your site with GitHub

[**Create your site now with GitHub** :rocket:](https://sourcethemes.com/academic/docs/install/)

### Create your site on your computer with Git

Prerequisites:

* [Download and install Git](https://git-scm.com/downloads)
* [Download and install Hugo Extended v0.73-v0.74](https://gohugo.io/getting-started/installing/#quick-install)

Install:

1. [Fork](https://github.com/sourcethemes/academic-kickstart#fork-destination-box) the *Academic Kickstart* repository to create a new website
   
   * If you already created your site with **Netlify**, then skip this step
2. Clone your fork to your computer with Git, replacing `sourcethemes` in the command below with your GitHub username: 

    ```bash
    git clone https://github.com/sourcethemes/academic-kickstart.git My_Website
    ```
    
3. Initialize the theme:

    ```bash
    cd My_Website
    git submodule update --init --recursive
    ```

### Create your site on your computer _without_ Git

Prerequisites:

* [Download and install Hugo Extended v0.73-v0.74](https://gohugo.io/getting-started/installing/#quick-install)

Install:

1. [Download](https://github.com/sourcethemes/academic-kickstart/archive/master.zip) and extract *Academic Kickstart*
2. [Download](https://github.com/gcushen/hugo-academic/archive/master.zip) and extract the *Academic theme* files from the `hugo-academic-master` folder to the `themes/academic/` folder in *Academic Kickstart*

### Create your site with RStudio

[Install Academic with RStudio](http://localhost:59000/academic/docs/install-locally/#install-with-rstudio)

## Demo content

For inspiration, refer to the [Markdown content](https://github.com/gcushen/hugo-academic/tree/master/exampleSite) which powers the [Demo](https://academic-demo.netlify.app).

If you wish to initialise your site with the demo content, copy the contents of the `themes/academic/exampleSite/` folder to your website root folder, overwriting existing files if necessary. The `exampleSite` folder contains an example config file and content to help you get started. The following command can be used to accomplish this:

```bash
cp -av themes/academic/exampleSite/* .
```

## Get Started

[View the guide to Personalize and Deploy your new site](https://sourcethemes.com/academic/docs/get-started/).

## Updating

[View the Update Guide](https://sourcethemes.com/academic/docs/update/).

Feel free to *star* the project on [Github](https://github.com/gcushen/hugo-academic/) and follow [@source_themes](https://twitter.com/source_themes) on Twitter to help keep track of [updates](https://sourcethemes.com/academic/updates).

## License

Copyright 2016-present [George Cushen](https://georgecushen.com).

Released under the [MIT](https://github.com/gcushen/hugo-academic/blob/master/LICENSE.md) license.

[![Analytics](https://ga-beacon.appspot.com/UA-78646709-2/hugo-academic/readme?pixel)](https://github.com/igrigorik/ga-beacon)
