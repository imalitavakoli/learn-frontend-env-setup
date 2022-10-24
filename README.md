# Learn setting up a simple Frontend environment for beginners
If you're just getting started to be a web designer or frontend developer, then this tutorial can be helpful! **Before coding, you need to setup your comfortable environment**, right? That's exactly what we're going to cover here in this short tutorial :smile:

**In this tutorial we introduce some text editors** with some of the most popular editors' extensions and learn how to use them in order to edit our *.html*, *.css*, *.js*, and other working files.
We also go a little bit further and **learn how to install *node.js* on our system and some of the most helpful node packaged modules** such as *Yeoman*, *Gulp*, *Sass*, and *Babel*. These tools help us scaffold a modern web app project.




# What text editor?
Well, to code and bring up a simple webpage, you don't need to install a specific text editor on your system! A simple *Notepad* can do the job! But if we could have an editor which is smarter and designed specifically for coding, it can make a huge difference in helping us to design webpages or develop web apps faster and well formatted. So here I mention some of these editors:

- **[Notepad++](https://notepad-plus-plus.org/)**: It's light, and **useful for simple and fast editing**, *NOT* starting a project from scratch! Just open an existing file, edit something in it, save, and close the editor!

- **[Atom](https://atom.io/)**: It's smart, and **useful for light projects**, *NOT* huge projects. Atom is beautifully designed, and gives you a good feeling, but it's not intelligent enough! So I prefer to use it when I like to start a simple project, or want to just edit multiple files of an existing project, save, and close the editor!

- **[Visual Studio Code](https://code.visualstudio.com/)**: It's professional, and **useful for projects in any scale**! It's smart, and has advanced code auto-completion and tools which help you be a hero web designer or frontend developer!

More? Of course there are lots of other editors out there, but I just mentioned these three editors here in this tutorial, because not only they are free to download, but also they're more than enough for what we need them to do! I mean fast or comprehensive editing!




# Visual Studio Code essential extensions?
I and most of the developers nowadays, use the *Visual Studio Code* editor for different projects in any scale most of the times. It's free, yet so powerful. So I decided to introduce some of this editor's essential extensions (for web designing) here only. But the similar extensions are available for the *Atom* editor known as "*packages*" as well.

So when you install the *Visual Studio Code* editor on your system, simply open it, and go to *View > Extensions* in order to **open the extensions panel and search for the following extensions** to install them:

- **[Live Server (Five Server)](https://marketplace.visualstudio.com/items?itemName=yandeu.five-server)**: This extension is developed by *Yannick* and it launches a development local Server with instant updates, highlights and PHP support.

- **[file-icons](https://marketplace.visualstudio.com/items?itemName=file-icons.file-icons)**: This extension is developed by *file-icons* and it shows File-specific icons in VSCode for improved visual grepping.

- **[HTML CSS Support](https://marketplace.visualstudio.com/items?itemName=ecmel.vscode-html-css)**: This extension is developed by *ecmel* and it enables CSS Intellisense for HTML.

- **[DocBlocker](https://marketplace.visualstudio.com/items?itemName=flydreame.docblocker)**: This extension is developed by *FlyDreame* and adds simple comments to any place.

- **[Spell Right](https://marketplace.visualstudio.com/items?itemName=ban.spellright)**: This extension is developed by *Bartosz Antosik* and it is a multilingual, offline and lightweight spellchecker.

- **[Bookmarks](https://marketplace.visualstudio.com/items?itemName=alefragnani.Bookmarks)**: This extension is developed by *Alessandro Fragnani* and it let's you mark lines and jump to them. (After installing the extension, then you can open the Command Palette and type "Bookmarks" to see all of the extension's shortcuts)

- **[Atom One Light Theme](https://marketplace.visualstudio.com/items?itemName=akamud.vscode-theme-onelight)**: This extension is developed by *Mahmoud Ali* and enables the One Light Theme based on Atom. (I personally love this theme because I think it's clean and beautiful)

- **[Atom One Dark Theme](https://marketplace.visualstudio.com/items?itemName=akamud.vscode-theme-onedark)**: This extension is developed by *Mahmoud Ali* and enables the One Dark Theme based on Atom. (I personally love this theme because I think it's clean and beautiful)

More? Well, *Visual Studio Code* itself already has many built-in features that helps you code fast and easy, but there are also lots of extensions that can be installed on it to make it even more powerful and customized based on your own specific coding needs. For example if you're using *VueJS framework*, you can install *[Vue Language Features (Volar)](https://marketplace.visualstudio.com/items?itemName=Vue.volar)* extension to improve your coding experience.




# Visual Studio Code tips & tricks?
Well, to work faster and easier with *Visual Studio Code*, you can consider the following:

- To open **Command Palette** fast, you can use the following shortcuts. *Windows: Ctrl+Shift+P*. *MacOS: Cmd+Shift+P*. Command Palette lets you do some tasks in editor fast.

- To **navigate between recently opened files or symbols in a single file** fast, you can use the following shortcuts. *Windows: Ctrl+P*. *MacOS: Cmd+P*.

- To use **multi cursor** in order to edit different places in a single file at once, you can use the following shortcuts. *Windows: Alt+Click Left* or *Ctrl+Alt+UP* or *Ctrl+Alt+DOWN*. *MacOS: Option+Click Left* or *Cmd+Opt+UP* or *Cmd+Opt+DOWN*.

- To **replace a repetitive keyword all at once**, you can simply click on one of the keywords, and use the following shortcuts. *Windows: Ctrl+Shift+L*. *MacOS: Cmd+Shift+L*.

- To simply **prettify a file on save**, you can go to *file > preferences > settings > search "format on save"* and check *Editor: Format On Save*.

- To **render vertical rulers**, you can go to *file > preferences > settings > search "rulers"* and click *Edit in settings.json* under the *Editor: Rulers* title, and in the opened *.json* file edit *"editor.rulers"* property to render vertical rulers in Visual Studio Code and save it. e.g., `"editor.rulers": [80, 100]` or `"editor.rulers": [{ "column": 80, "color": "#e9a073" }]`. Vertical rulers are rendered after a certain number of monospace characters that you have defined. They can be helpful when you like to write comments in your codes, and would like to break lines and then continue writing for easier reading later.

- I also personally love to see a **mini map** for my files. So make sure to check *Minimap* in *View*, then right click on the Minimap (when viewing a file) and check *Fill* in *Vertical size*, so that the Minimap can be identical to your large viewed file.

- **Emmet** is built right into Visual Studio Code. Emmet is a toolkit which greatly improves HTML & CSS workflow. It lets you type CSS-like abbreviation, and expand it into HTML. e.g., type `h1+p*2+hr.classname+(blockquote>(section>p)+q+footer>a+cite)+hr.classname+ul>li*2>a.btn.color${btn $}` in your HTML and press *tab*, then you will see the magic happens! [Click here](https://code.visualstudio.com/docs/editor/emmet) to learn more about Emmet in Visual Studio Code.

More? For sure Visual Studio Code is a powerful editor and has lots of features. [Click here](https://code.visualstudio.com/docs/getstarted/introvideos) to learn more about its interface, settings, and more.


# Useful CLI (Command-Line Interface) tools?
Looking for more advanced development environment? Well, you may need to install some frontend development related node packaged modules, or let me say some useful CLI tools, on your system.

Before using a CLI tool, **first you need to [download and install *node.js*](https://nodejs.org/download/)** (which includes *npm*) on your system. *npm* stands for [*node packaged modules*](https://www.npmjs.com/) and is a way to manage development dependencies through *node.js*. **Then open your Terminal / Command Prompt** to be able to run some commands through it.

Here I mention some of the most useful CLI tools for web designing and frontend developing that I myself also love. To install them on your system, you need to run the commands that I mention for each one of them as I'm introducing them:


## [Yeoman](https://yeoman.io/)
It's the **web's scaffolding tool for modern webapps**. It actually helps you kickstart a project fast and with the best practices, suggested by the community. When you kickstart a project with *Yeoman*, it configures everything needed, and downloads all of the dependencies! At the end, it provides you a ready-to-use scaffolding, so that you won't need to spend time to structure your project, you just focus on building.

 1. Run `npm install --global yo` to install *Yeoman* the very first time on your system.

 2. Run `npm install -g generator-webapp` to install a Yeoman generator. (here we install *generator-webapp* that is one of the most popular *Yeoman* generators created to kickstart a basic frontend developing environment. [Click here](https://yeoman.io/generators/) to search for more generators)

 3. Run `cd my/path/to/project` to change directory to the folder you like to save your project in.

 4. Run `yo webapp` when you are at the root of your project, to scaffold your webapp project. (By calling `yo` command followed by the already installed generator, that in our case it's `webapp`, you let *Yeoman* scaffold and make everything ready to kickstart your project)


## [Gulp](https://gulpjs.com/)
It's a **JavaScript task runner** which helps you automate & enhance your workflow.

 1. Run `npm install -g gulp-cli` to install *Gulp CLI* the very first time on your system.

 2. Run `cd my/path/to/project` to change directory to the folder of your project.

 3. Run `npm init` when you are at the root of your project, to let *node.js* create a "*package.json*" file for your project. ("*package.json*" is a file which holds references to you project's dependencies and some other information about your webapp project. [Click here](https://heynode.com/tutorial/what-packagejson/) to learn more about it)

 4. Run `npm install --save-dev gulp` to install local *Gulp* as a development dependency for your project. (By calling this command, "*node_modules*" folder will be created, *Gulp* will be installed there, and "*package.json*" file will be modified to mention that you have *Gulp* installed as a development dependency for your project)

 5. After you have a "*package.json*" file for your project, and also created a "*gulpfile.js*" file at the root of your project, I mean beside the "*package.json*" file, then run `gulp` to run your project's tasks and you're all done! ("*gulpfile.js*" file is a file which you configure all of the needed tasks that should be done for your project inside of it. [Click here](https://gulpjs.com/docs/en/getting-started/javascript-and-gulpfiles) to learn more about it)

 - *Optional!* You can also manually modify your "*package.json*" file and mention the local dependencies that you like your project to have in it, save it, then run `npm install` to install all of the dependencies. (And of course just like how you installed *Gulp* itself and modified "*package.json*" file via a command run, you can install dependencies and modify "*package.json*" file all at once via a command run. e.g., `npm install gulp-uglify --save-dev` and `npm install gulp-concat --save-dev` commands, install the mentioned development dependencies for your project and modify the "*package.json*" file)


## [Sass](https://sass-lang.com/)
It's **CSS with superpowers**. It helps you write CSS more efficiently by using variables, functions, and methods. [Click here](https://sass-lang.com/guide) to learn more about the Sass language.

 1. Run `npm install -g sass` to install *Sass* the very first time on your system.

 2. Run `cd my/path/to/project` to change directory to the folder of your project.

 3. Run `sass <name>.scss <name>.css` to convert a *.scss* to a *.css* file. **NOTE:** Replace `<name>` with the name of your files.

 - *Optional!* By running `sass --watch <name>.scss <name>.css`, you let *Sass* watch a specific Sass file for any changes, so that when it is saved, it will generate a new CSS file accordingly. You can press *Ctrl+C* to stop watching.

 - *Optional!* By running `sass --watch <folder>:<folder>`, you let *Sass* watch all Sass files in a folder, and generate their identical CSS files in another folder.


## [Babel](https://babeljs.io/)
It's a **JavaScript compiler**. It helps you write the next generation JavaScript, and convert it into older versions. e.g., you can write in ES6(ECMAScript 6) syntax and use *Babel* to compile it into ES5, so that older browsers can read your codes.

 1. Run `cd my/path/to/project` to change directory to the folder of your project.

 2. Run `npm init` when you are at the root of your project, to let *node.js* create a "*package.json*" file for your project.

 3. Run `npm install @babel/core @babel/cli --save-dev` to install local *Babel* as a development dependency for your project.

 4. We've installed *Babel*, but it doesn't do anything by default as it needs to have some presets enabled! So run `npm install @babel/preset-env --save-dev` to install preset environment. Now create a "*babel.config.json*" file and write the following inside of it to enable transforms for ES2015+ preset: `{ "presets": ["@babel/preset-env"] }`. ("*babel.config.json*" file is a file which holds *Babel* configurations. [Click here](https://babeljs.io/docs/en/usage/#configuration) to learn more about it)

 5. Run `npx babel src --out-dir lib` to transform all JavaScript files in "src" folder from ES6 syntax to ES5 and put the new transformed files to "lib" folder.

 - *Optional!* Run `npx babel src --out-file script-compiled.js` to transform all JavaScript files in "src" folder from ES6 syntax to ES5 and concatenate all of them, and output the results into one single file named "*script-compiled.js*".

 - *Optional!* By using `--watch` option in your command (e.g., `npx babel src --watch --out-file script-compiled.js`), you let *Babel* watch for any JavaScript file changes. You can press *Ctrl+C* to stop watching.

 - *Optional!* If you have used ES6 module loader syntax in your codes and like to bundle them up all together when they are transformed from ES6 syntax to ES5, then you can use the *[Browserify](https://browserify.org/)* CLI tool. In order to do that run `npm install -g browserify` to install it the very first time on your system, then run `browserify lib/moduleLoader.js -o lib/bundle.js` to bundle up all of the modules imported in the "*moduleLoader.js*" file, all in the "*bundle.js*" file, and feed your HTML files with just the "*bundle.js*" file.




# What's next?
In this tutorial I tried to introduce you to some text editors, let you know about some essential extensions of Visual Studio Code, talk about some tips & tricks of Visual Studio Code, and teach you how to use some cool CLI tools in order to level up your frontend developing skills.


Like to learn more? Checkout the following resources:

* ["Getting Started with Visual Studio Code"](https://youtube.com/playlist?list=PLj6YeMhvp2S5UgiQnBfvD7XgOMKs3O_G6) is a  series of video tutorials that lets you learn VS Code's must-have features.

* ["The Command Line for Web Design"](https://webdesign.tutsplus.com/series/the-command-line-for-web-design--cms-777) is a series of tutorials specifically for web designers, showing you how to utilize command line tools that are incredibly useful specifically for web design projects.
