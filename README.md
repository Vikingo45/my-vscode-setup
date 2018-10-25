# My VSCode Setup

This repository contains my personal configuration for the awesome and extensible Visual Studio Code editor. Here, I keep an updated list of extensions I find useful for my workflow. In addition, I also keep my preferred editor settings as well as any required extension-based settings.  

![VSCode!](./assets/vscode.png)


## Extensions

For the moment, these are the extensions I have installed in my VSCode:  

* [C/C++](https://marketplace.visualstudio.com/items?itemName=ms-vscode.cpptools): Intellisense, debugging, and code browsing.
* [Date & Time](https://marketplace.visualstudio.com/items?itemName=rid9.datetime): Displays a clock and date information in the status bar.
* [Excel Viewer](https://marketplace.visualstudio.com/items?itemName=GrapeCity.gc-excelviewer): View Excel spreadsheets and CSV files within Visual Studio Code workspaces.
* [GitLens](https://marketplace.visualstudio.com/items?itemName=eamodio.gitlens): Supercharge the Git capabilities built into Visual Studio Code — Visualize code authorship at a glance via Git blame annotations and code lens, seamlessly navigate and explore Git repositories, gain valuable insights via powerful comparison commands, and so much more.
* [Highlight-Matching-Tag](https://marketplace.visualstudio.com/items?itemName=vincaslt.highlight-matching-tag): Highlights matching opening and closing tags.
* [Indent-Rainbow](https://marketplace.visualstudio.com/items?itemName=oderwat.indent-rainbow): Makes indentation easier to read.
* [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer): Launch a development local server with live reload feature for static & dynamic pages.
* [Markdown PDF](https://marketplace.visualstudio.com/items?itemName=yzane.markdown-pdf): Convert Markdown to PDF.
* [Material Icon Theme](https://marketplace.visualstudio.com/items?itemName=PKief.material-icon-theme): Material Design Icons for Visual Studio Code.
* [pgsql-html](https://marketplace.visualstudio.com/items?itemName=hubertstrk.pgsql-html): Postgres language support, snippets, runner, html preview.
* [Python](https://marketplace.visualstudio.com/items?itemName=ms-python.python): Linting, debugging, Intellisense, code formatting, refactoring, unit tests, snippets, and more.
* [Rainbow CSV](https://marketplace.visualstudio.com/items?itemName=mechatroner.rainbow-csv): Highlight CSV and TSV files in different colors, Run SQL-like queries.
* [SFTP](https://marketplace.visualstudio.com/items?itemName=liximomo.sftp): SFTP/FTP sync client.
* [Spell Right](https://marketplace.visualstudio.com/items?itemName=ban.spellright): Multilingual, Offline and Lightweight Spellchecker.
* [TODO Highlight](https://marketplace.visualstudio.com/items?itemName=wayou.vscode-todo-highlight): Highlights TODOs, FIXMEs, and any keywords, annotations.
* [Trailing Spaces](https://marketplace.visualstudio.com/items?itemName=shardulm94.trailing-spaces): Highlight trailing spaces and delete them in a flash!
* [Vim](https://marketplace.visualstudio.com/items?itemName=vscodevim.vim): Vim emulation for Visual Studio Code.
* [VS Code Jupyter Notebook Previewer](https://marketplace.visualstudio.com/items?itemName=jithurjacob.nbpreviewer): An extension for supercharging your Data Science workflow by previewing Jupyter Notebook within VS Code. View graphs and interact with Plotly visualizations from within VS Code.
* [vscode-pdf](https://marketplace.visualstudio.com/items?itemName=tomoki1207.pdf): Display pdf file in VSCode.


All these extensions can be installed at once by running [install-extensions.sh](./scripts/install-extensions.sh) from a terminal window.  


## Editor Settings

My current editor settings are saved in [settings.json](./settings/settings.json). Personally, I like to disable the mini map and cursor blinking, and enable things like file auto save after some delay. Some settings may not be ideal for some type of projects, but the good thing is that they can be overwritten when working with workspaces.  


## SFTP Settings

The SFTP extension requires you to specify some settings. [sftp.json](./settings/sftp.json) contains the general structure I follow to configure the extension and [sftp-sample-configuration.json](./settings/sftp-sample-configuration.json) is a complete configuration file. The extension's official documentation can be found [here](https://github.com/liximomo/vscode-sftp).  


## Workspaces

In the workspaces directory, there are some workspace files with custom settings which I use in my workflow.  
