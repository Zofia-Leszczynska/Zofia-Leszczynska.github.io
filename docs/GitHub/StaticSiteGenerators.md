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

1. Copy the file ***_config.yml*** from ***just-the-docs*** to your repository.
2. Open it.
3. After the **`title:`** enter the name of your web page.  
   
   **📝 Note:** What you enter will be visible in the top left corner of your page.

4. After the **`remote_theme:`** enter: ***my_username/just-the-docs***.

   **Example:** If your username is *John30*, enter: *John30/just-the-docs*.

5. After the **`aux_links:`** enter: ***"Source repository on GitHub": - "//github.com/my_username/my_username.github.io"***.
   
   **Example:** If your username is *John30*, enter: *"Source repository on GitHub": - "//github.com/John30/John30.github.io"*

6. After the **`footer_content:`** 



