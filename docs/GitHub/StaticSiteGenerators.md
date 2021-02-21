# Static site generators

To publish your documentation on GitHub Pages, you don't have to create the HTML files yourself. You can use static site generator, that is, a software application that creates HTML pages from templates or components and a given content source. Most static site generators accept files written in Markdown. 

## Jekyll

Jekyll is a static site generator. If you use GitHub Pages, Jekyll would be a good option, because it is integrated with GitHub. 

### Configuring Jekyll

If you don't want to create the set of files needed to generate the page yourself, you can use a template. One of the Jekyll templates is Just the Docs. To use it, you can copy the ***just-the-docs*** repository on GitHub from ***pmarsceill*** account.

To copy ***just-the-docs*** to your repository, perform the following actions:

1. Go to GitHub.
2. Log in to your account.
3. In the top left corner on GitHub search for ***just-the-docs*** repository by ***pmarsceill*** and select it.
4. To copy the repository click ***Fork***.
5. Click ***Code***.
6. Select ***Open with GitHub Desktop***.

To prepare your repository for configuration, perform the following actions:

1. Open your repository in VS Code.
2. In the top left corner click ***File***, then select ***Add Folder to Workspace...***
3. Select ***just-the-docs*** and click ***Add***. Now you should see your repository and ***just-the-docs*** in the Workspace in the left sidebar.

To configure your repository, perform following actions:

1. Copy ***_config.yml*** file from ***just-the-docs*** to your repository and open it.
2. After the **`title:`** type the name of your web page.  
   
   **📝 Note:** What you enter will be visible in the top left corner of your page.

3. After the **`remote_theme:`** type: ***my_username/just-the-docs***.

   **Example:** If your username is *John30*, type: *John30/just-the-docs*.

4. After the **`aux_links:`** type: ***"Source repository on GitHub": - "//github.com/my_username/my_username.github.io"***.
   
   **Example:** If your username is *John30*, type: *"Source repository on GitHub": - "//github.com/John30/John30.github.io"*

5. After the **`footer_content:`** type any text you want in the footer of your page.
6. Copy main ***index.md*** file from ***just-the-docs*** to your repository and open it.
7. After the **`title:`** type the title of the homepage. It will also be visible in the table of contents.
8. After the **`nav_order:`** should be "***1***".

The ***_config.yml*** and ***index.md*** are the two primary files that should be in your repository. The simplest sites have three more folders appearing in the repository. You can find them in the table below.

| Folder | Description |
| ------ | ----------- |
| ***docs***   | This folder is for your text files. You can also put here subfolders for separate chapters. |
| ***assets*** | This folder contains the ***Images*** subfolder where the images are located.|
| ***_includes*** | This folder is for SVG files.|




