---
layout: default
title: Static site generators
nav_order: 6
---


# Static site generators <!-- omit in toc -->

To publish your documentation on GitHub Pages, you don't have to create the HTML files yourself. You can use static site generator, that is, a software application that creates HTML pages from templates or components and a given content source. Most static site generators accept files written in Markdown. 

## Table of Contents <!-- omit in toc -->

- [Jekyll](#jekyll)
  - [Configuring Jekyll](#configuring-jekyll)
    - [How to copy ***just-the-docs*** to your repository](#how-to-copy-just-the-docs-to-your-repository)
    - [How to prepare your repository for configuration](#how-to-prepare-your-repository-for-configuration)
    - [How to configure your repository with ***just-the-docs***](#how-to-configure-your-repository-with-just-the-docs)

# Jekyll

Jekyll is a static site generator. If you use GitHub Pages, Jekyll would be a good option, because it is integrated with GitHub. 

## Configuring Jekyll

If you don't want to create the set of files needed to generate the page yourself, you can use a template. One of the Jekyll templates is Just the Docs. To use it, you can copy the ***just-the-docs*** repository on GitHub from ***pmarsceill*** account.

### How to copy ***just-the-docs*** to your repository  
  
1. Go to GitHub.
2. Log in to your account.
3. In the top left corner on GitHub search for ***just-the-docs***.

   ![just-the-docs](/assets/images/just-the-docs.png)

4. Then select repository by ***pmarsceill***.  

   ![pmarsceill](/assets/images/pmarsceill.png) 


5. To copy the repository click ***Fork***.  

   ![Fork](/assets/images/fork.png) 

6. Click ***Code*** and select ***Open with GitHub Desktop***.  

    ![Code](/assets/images/code2.png) 

7. In the top left corner of GitHub Desktop, click ***Current repository just-the-docs***, then click ***Add*** and select ***Clone repository***.

    ![Clone repository](/assets/images/add.png) 

8. When you see the notification ***Clone a repository***, select GitHub.com and repository ***my_username/just-the-docs***. Then choose local path and click ***Clone***.

    ![Clone repository 2](/assets/images/zofia.png)

9.  When you see the notification ***How are you planning to use this fork?***, select ***For my own purposes***. Then click ***Continue***.

    ![For my own purposes](/assets/images/for.png)

### How to prepare your repository for configuration

1. Open your repository in VS Code.

    ![Open your repository](/assets/images/open.png) 

2. In the top left corner click ***File***, then select ***Add Folder to Workspace...***  


3. Select ***just-the-docs*** and click ***Add***. 
   


   Now you should see your repository and ***just-the-docs*** in the Workspace in the left sidebar.

### How to configure your repository with ***just-the-docs***

1. Copy ***_config.yml*** file from ***just-the-docs*** to your repository and open it.
2. After the **`title:`** type the name of your web page.  
   
   **📝 Note:** What you enter will be visible in the top left corner of your page.

3. After the **`remote_theme:`** type: ***my_username/just-the-docs***.

4. After the **`aux_links:`** type: ***"Source repository on GitHub": - "//github.com/my_username/my_username.github.io"***.
   


5. After the **`footer_content:`** type any text you want in the footer of your page.

   Below you can see an example of a configured ***_config.yml*** file:
   
   ![_config.yml](/assets/images/yml2.png)

6. Copy main ***index.md*** file from ***just-the-docs*** to your repository and open it.
7. After the **`title:`** type the title of the homepage. It will also be visible in the table of contents.
8. After the **`nav_order:`** type ***1***.

   Below you can see an example of a configured ***index.md*** file:

   ![index.md](/assets/images/index.png)

The ***_config.yml*** and ***index.md*** are the two primary files that should be in your repository. The simplest sites have three more folders appearing in the repository. You can find them in the table below.
| Folder | Description |
| ------ | ----------- |
| ***docs***   | This folder is for your text files. You can also put here subfolders for separate chapters. |
| ***assets*** | This folder contains the ***Images*** subfolder where the images are located.|
| ***_includes*** |This folder is for SVG files.  |





If you need more information, please use the documentation provided by the creator of Just the Docs: [pmarsceill.github.io/just-the-docs/](https://pmarsceill.github.io/just-the-docs/).


