# build-your-own-cv
Build your own CV using GitHub Pages

Gone are the days of the poorly formatted and fiddly Word Documents and PDFs. In this lab you are going to build your own online CV that you can present to prospective employers. Through the lab you will learn how to write HTML and style it with CSS.

## Step 1 - Create your code repository
Log into [GitHub](https://github.com/) and create a new repository as shown below

![create-repository](./assets/create-repository.png)

Fill in the information on the screen with the following:
- Name = my-digital-cv (feel free to call this something personal eg. liams-digital-cv)
- Description (optional) = A digital CV hosted with GitHub Pages
- Public = this makes the code repository public and allows anyone on the internet to see it
- Add a README.md file
- License = MIT
- Click `Create repository`

![new-repository-information](./assets/new-repository-info.png)

It should then look something like

![new-repository](./assets/new-repository.png)

## Step 2 - Install CodeSwing plugin

In the URL address bar, add the following prefix to the new repository url `vscode.dev/` and press "Enter" (as shown below)

![url-prefix](./assets/url-prefix.png)

It should then look something like this

![url-prefix](./assets/vscode-preview.png)

Next you need to install a new plugin called `CodeSwing`. This plugin allows you to see your code edits as you make them all from within the browser window.

On the left menu, click on the 4 small boxes icon. Then type into the search bar `codeswing`. Click on the top result and select `install`.

![install-codeswing](./assets/codeswing-plugin.png)

## Step 3 - Initialise the project workspace

Now the plugin is installed you now need to initialise the workspace using the CodeSwing plugin. To do that, go back to the main project folder (shown below).

![vscode-workspace](./assets/vscode-workspace.png)

Next, open the VS Code command palette by navigating to `View` -> `Command Palette...` and follow the steps below to initialise a `CodeSwing` workspace.

![command-palette](./assets/command-palette.png)

Search for `CodeSwing` and select the option `CodeSwing: Initialize Workspace as Swing`
![select-codeswing](./assets/select-codeswing.png)

In the next option menu, select the option `Basic: HTML-Only` as you are only writing HTML and CSS in this workshop 
![html-only](./assets/html-only.png)

The page will reload and you will see it split in half. On the left you will have an open `index.html` file and on the right, a preview of the `index.html` file. In the Workspace, you will also see some new files have been created. It should now look like this

![codeswing-workspace](./assets/codeswing-workspace.png)

---
**Optional Step** 

In the `index.html` file, on the left side of the split window, type `<h1> Hello World! </h1>` and you can watch it appear on the right side of the screen as a preview for what it will look like on the internet.

---

