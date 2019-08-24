![picture alt](https://github.com/aayush4vedi/The-Hitchhikers-Guide-to-the-Full-Stack-Developer/blob/master/Media/wallpaper.jpg)


# Useful Things:
* **DRY**: Don't Repeat Yourself
* 16k APIs [ProgrammableWeb](https://www.programmableweb.com/category/all/news?articletypes=howto&source_code=0)
* Motivation for Side project: [TraversyMedia](https://www.youtube.com/watch?v=eCAj3mWFpNM)
* Status of popular language on github: [github](https://github.blog/2018-11-15-state-of-the-octoverse-top-programming-languages/)
* Stackshare: Why do people like [NodeJs](https://stackshare.io/nodejs) | [Php](https://stackshare.io/php) | [Python](https://stackshare.io/python) | [Golang](https://stackshare.io/go)
* Framework vs Library vs Toolkit: [stackoverflow](https://stackoverflow.com/questions/3057526/framework-vs-toolkit-vs-library)
* Cool IoT-APIs [IFTTT](https://ifttt.com/discover)
* A $100 freelanced portfolio-website [@youtube](https://www.youtube.com/watch?v=k152ovSOR74)
* **REST** is an useful convention/architecture for mapping http routes to CRUD functionalities 
# I. Basic Tools
## 1. IDE
* **VSCode**<br/>
    * [Tips-n-tricks](https://code.visualstudio.com/docs/getstarted/tips-and-tricks) 
    * [Basic Editing Shortcuts](https://code.visualstudio.com/docs/editor/codebasics) >>Multiple cursors
    * Linux/Mac Shortcuts:
        * Search for files <kbd>command</kbd> + <kbd>P</kbd>
        * Show Command Palette <kbd>control</kbd> + <kbd>shift</kbd> + <kbd>P</kbd>
        * Move to End of Line <kbd>control</kbd> + <kbd>right</kbd>
        * Move to End of Word <kbd>control</kbd> + <kbd>option</kbd> + <kbd>right</kbd>/<kbd>left</kbd>
        * Open New Window      <kbd>control</kbd> + <kbd>shift</kbd> + <kbd>N</kbd>
        * Close Window         <kbd>control</kbd> + <kbd>W</kbd>
        * Move Line Up/Down     <kbd>alt</kbd> + <kbd>up</kbd>/<kbd>down</kbd>
        * Delete Line <kbd>control</kbd> + <kbd>shift</kbd> + <kbd>K</kbd>
        * Jump to matching bracket <kbd>control</kbd> + <kbd>shift</kbd> + <kbd>\</kbd>
        * Comment/Uncomment a line <kbd>control</kbd> + <kbd>/</kbd> 
        * Toggle Full Screen <kbd>F11</kbd>
        * Open Markdown Preview <kbd>control</kbd> + <kbd>shift</kbd> + <kbd>V</kbd>
        * Find/Replace <kbd>control</kbd> + <kbd>F</kbd>/<kbd>H</kbd>
        * Split Editor <kbd>control</kbd> + <kbd>Front-\Slash</kbd>
        * Open Next <kbd>control</kbd> + <kbd>tab</kbd>
        * Open Previous <kbd>control</kbd> +<kbd>shift</kbd>+ <kbd>tab</kbd>
        * Show integrated terminal <kbd>control</kbd> + <kbd>`</kbd> 
        * Shortcuts            <kbd>control</kbd> + <kbd>K</kbd>
        * Multiple cursor <kbd>option/alt</kbd> + `click`
            * Move: <kbd>command</kbd> + <kbd>option</kbd> + <kbd>Up/Down</kbd>
        * Duplicate a line <kbd>shift</kbd> +<kbd>option</kbd>+ <kbd>Up/Down</kbd>
         * Rename all instances: <kbd>command</kbd> +<kbd>F2</kbd>
        * Reverse Search?

    * Useful Extensions

        **>> Style:**
        * My fav theme: `One Dark Pro` > `Gruvbox Dark(medium)` > `Material Dark(with high contrast)`
        * Material Icon Theme
        * vscode-pdf
        * Markdown Emoji [cheat-sheet](https://gist.github.com/rxaviers/7360908)
        * Bracket Pair Colorizer 2
        * Indenticator
        * Auto close tag

        **>> HTML/CSS:**
        * Emmet( ```life-savior```): [cheatsheet](https://docs.emmet.io/cheat-sheet/), lorem30
        * HTML Boilerplate
        * Beautify css/sacss
        * Color Highlight
        * CSS Peek
        * IntelliSense for CSS class names 
        
        **>> REST:**
        * REST Client(inbuilt Postman)

        **>> Others**
        * Live Server
        * Live Share(git)
        * [Fira Code](https://medium.com/@qjli/daily-dev-tips-96-visual-studio-code-how-to-enable-this-new-sexy-fira-code-font-89bafbfa245f) : fonts with ligatures
        * Git Lense
        * Multiple clipboards for VSCode: TODO: learn it's commands 



    * Other Tricks
        * Paste 'JSON as Code' in search bar
        * Compare two files with each other: on terminal: `code -d --diff <file1> <file2>`    
        * Type `icons` in command pallate for icon-themes: current-Material     
        * Open a file in split mode(**Zen** mode): <kbd>command</kbd> + `click`
       
            


## 2. Cloud IDE

   * Amazon's `cloud9` shut down
   * Alternative: **GoormIDE**
    * [Setup](https://www.youtube.com/watch?v=iJtOoeM_fS8&list=PL86ehqHzxhy4oHmZoMMJPEKuryOk287oU&index=2)
    * Coupon(from Udemy): cfWQaYAAlkSh

## 3. Design

   * Creation: Adobe Photoshop, XD(not in Linux yet :grimacing: )
   * Tickling: [photopia](https://www.photopea.com/) 
   * [Colorzilla](https://chrome.google.com/webstore/detail/colorzilla/bhlhnicpbhignbdhedgjhgdocnmhomnp/related?hl=en): Chrome Ext. to pic colors from web pages


## 4. Terminals

* **Linux** >> Guake
* **MacOS** >> iTerm2+ zsh
    * [Medium's extensive article](https://www.freecodecamp.org/news/jazz-up-your-zsh-terminal-in-seven-steps-a-visual-guide-e81a8fd59a38/)
    * [Few great plugins](https://opensource.com/article/18/9/tips-productivity-zsh)
    * zsh's Powerlevel10k: [many packages into one](https://gist.github.com/kevin-smets/8568070)
* **Windows** >> :thumbsup:
* **Useful Commands:**
    * **tar :**(tape archive)
        * Compress: `cvf`    : tar cvf newName.tar folderToBeCompressed
        * Extracting: `xvf`  : tar xvf compressedFile.tar
    * **grep**(Globally search for REgular expression and Print-out)
        * Search for the given string in a filename begining with file: `grep "string" file*`
        * `grep -x`, where `x` is :
            * `i` : case insensitive
            * `w` : matches the whole word
            * `r` : recursive(searches in all sub-directories)
    * **find**: Findes file
        * `find -iname "filename.txt"` : case-insensitive search
        * `find ~ -empty` : find all empty files in home directory
    * **ssh**: (Secure Shell)
        * securely connect to a remote server/system: `ssh user_name@host(IP/Domain_name)`
        * `ssh-keygen`
        * [More](https://www.thegeekstuff.com/2008/05/5-basic-linux-ssh-client-commands/)
    * **kill**
        * Get the process id: `ps -ef | grep process_name`
        * Kill it: `kill -9 process_id`
    * **rm** : remove
        * Recursive removal(delete all what's inside): `rm -r folder`
    * **cp** : copy 
        * `cp Src_file Dest_file`
        * `cp - Src_directory Dest_directory` : recursive
    * **mv** : move
        * `mv src dest`
        * `mv oldName newName` : renaming a folder/file
    * **chmod** :(change mode)
        * `chmod ug+rwx file.txt` -Give full access to user and group (i.e read, write and execute ) on a specific file
        * `chmod g-rwx file.txt` -Revoke all access for the group (i.e read, write and execute ) on a specific file
        * `chmod -R ug+rwx file.txt` -Apply the file permissions recursively to all the files
    * **chown** : change ownership
    * **ping** : ping a host `ping -c google.com`
    * **wget** : download something from internet 
        * `wget -O fileName.mp3 url`
    * **ln** : soft-link  `ln -s {source-filename} {symbolic-filename}`
    * **[netstat](https://www.tecmint.com/20-netstat-commands-for-linux-network-management/)**
    * `history` :lists all prev commands
    * **reverse-i-search**: Reverse Incremental Search. <kbd>control</kbd>+ <kbd>r</kbd> 
* Notes:
    * `-` is for letter, `--` for words : `la -a`, `ls --all
    * Rename folder: `mv old new`
    * Run B only if A works: `A && B`
    * `*` if sort-of auto-complete
    * You might already know that Ubuntu is derived from Debian Linux. And Debian uses dpkg packaging system. A packaging system is a way to provide programs and applications for installation. This way, you don’t have to build a program from the source code which, trust me, is not a pretty way to handle packages.**APT** (Advanced Package Tool) is the command line tool to interact with the packaging system. There is already dpkg commands to manage it. But APT is a more friendly way to handle packaging. You can use it to find and install new packages, upgrade packages, remove the packages etc.
    * `sudo apt update` :apt actually works on a database of available packages. If the database is not updated, the system won’t know if there are any newer packages available. This is why updating the repository should be the first thing to do in in any Linux system after a fresh install.
    * `sudo apt remove <package_name>` OR `sudo apt purge <package_name>` : Uninstall a package.**Diff:**
        * `apt remove` just removes the binaries of a package. It leaves residue configuration files.
        * `apt purge` removes everything related to a package including the configuration files.
    * `sudo apt autoremove`: This command removes libs and packages that were installed automatically to satisfy the dependencies of an installed package.

## 5. Browser Tools

* HTTP response status codes: [MDN doc](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status)
* **Chrome Dev Tools**
    * [Google Doc](https://developers.google.com/web/tools/chrome-devtools/beginners/html)
    * [Crash Course @Youtube](https://www.youtube.com/watch?v=x4q86IjJFag) :Kafi cool intro to all tabs
    * [for CSS @Youtube](https://www.youtube.com/watch?v=Z3HGJsNLQ1E): Steal other website's styles
    * ~~crossed~~ styles are disabled because of lower priority


## 6. Git
* **Handy Commands:**
    * `git log` : entire history of logs + `--oneline` + `--graph` + `--decorate` + `--all`
    * `git show`: logs history + all changes in files
    * `git status`
    * `git branch` : to see which branch I'm on rn + `-a ` : to  see all branches 
    * `git checkout -b <new_branch_name>` 
    * `git branch -d <new_branch>` : to delete a branch
    * `git reset HEAD <fileName>` : brings file to staging area => `git checkout -- <FileName>` : brings back file to last commit
    * `git add -A`: for all type of changes
    * `git hist` : get `ids` of commits
    * `git diff <commit1> <commit2>` : to see the diff b/w 2 commits or branches
    * Express Commit: `git commit -am "message"`
    * ` tags`
* **Other Things:**
    * `.gitignore`: use `*.filetype` to ignore all files with this extension
    * `HEAD` points to the last commit of the current branch.(could be changed)
    * **Merging Branches:**
        1. `git checkout -b <new_branch>` 
        2. finish working on `<new_branch>` => commit&push
        3. `git checkout master` (can see history & HEAD location with `git hist`)
        4.  `git merge <new_branch >` (can use  `git hist` to see all heads are at same place)
        5. conflict ressolution
        6. Delete that branch `git branch -d <new_branch>`
    * **`git stash`** TODO:
    * **`git reset & reflog`**: soft & hard TODO:
* Anatomy of Good Commit Messages:
    * when you write a commit message you are writing it as if it’s **about to be applied**, rather than *about what you just did*.
    * Provide as much context as you can: the 6 months rule-will you get it after 6 months? If no, it's not a good commit message.
    * For long commits: use [templates](https://medium.com/sitewards/git-tips-template-your-commit-messages-187d8a2051b8)
 ## 7. Postman

---

# II. Front-End 

## 1. HTML & CSS  :white_check_mark:	

* Semantic HTML5 elements
    * [MDN elements reference](https://developer.mozilla.org/en-US/docs/Web/HTML/Element) : An exhaustive list of 100+ elements
    * [MDN HTML Attributes](https://developer.mozilla.org/en-US/docs/Web/HTML/Attributes)
    * [MDN-CDNs](https://mdbootstrap.com/md-bootstrap-cdn/) one place for everything
* Basic CSS
    * **Selectors:**
        * [Article](https://code.tutsplus.com/tutorials/the-30-css-selectors-you-must-memorize--net-16048) listing all CSS Selectors
        * element
        * #id
        * .class
        * `descendent` X Y Z {...}
        * X:hover
        * *Forget not the multiple classes concept*
    * Closest inheritence wins in deciding the style
    * Animation:
        * `transition: all 0.25s;`
    * Styles:
        * `box-shadow: 11px 13px 15px 0px rgba(65, 64, 64, 0.52);`
        * [UiGradients](https://uigradients.com/#RoseWater): auto generated **beautiful color gradients**
    * **Fonts**
        * [Web Safe Fonts](https://www.cssfontstack.com/) : pre-installed in OS
        * [Web Fonts](https://www.cssfontstack.com/Web-Fonts) : not pre-installed 
        * [MDN](https://developer.mozilla.org/en-US/docs/Web/CSS/font) - font properties
            * `font-family:` "X"
            * `span` -to tweek with a sub-string
        * [Google Fonts](https://fonts.google.com/) ->select fonts -> see load time ->copy the `<link>` -> use! 
    * **Text**
        * [MDN](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Text) -text properties
        * `text-transform:`uppercase
        * `text-shadow` iskool!
    * **[Box Model](https://developer.mozilla.org/en-US/docs/Learn/CSS/Introduction_to_CSS/Box_model)**
        * Element->Padding->Border->Margin :: *"Epaah!-bor-maar raha hai!"*
    * **Float** - like gravity shift, allowing text and inline elements to wrap around it. [@MDN](https://developer.mozilla.org/en-US/docs/Web/CSS/float)
    * **Icons** : Font Awesome
        * [CDN](https://mdbootstrap.com/md-bootstrap-cdn/)
        * [Resizing](https://fontawesome.com/how-to-use/on-the-web/styling/sizing-icons)
    <hr>

     * **Notes:** 
        * `background-color` is for background & `color` is for text.
        * Make alternate `li`'s color different:<br> 
            `li{background: white;}`<br>
            `li:nth-child(2n){background: black;}`
        * `box-sizing: border-box;`
        * `margin: 10% auto;` is a life-savor: puts the div/id/class in centre
        * `::placeholder { color: blue;}`


* CSS3: 
    * box-model: [doc](https://cssreference.io/box-model/)
    * **grid**(2D & preferred): [@youtube](https://www.youtube.com/watch?v=jV8B24rSN5o), [doc](https://cssreference.io/css-grid/), [css-tricks:doc](https://css-tricks.com/snippets/css/complete-guide-grid/)
    * **flexbox**(1D): [@youtube](https://www.youtube.com/watch?v=JJSoEo8JSnc&list=PLillGF-RfqbYeckUaD1z6nviTp31GLTH8&index=23), [doc](https://cssreference.io/flexbox/)  >> aligh items man-makfik inside a div
    * **Other**
        * positioning: [doc](https://cssreference.io/positioning/)
        * transitions: [@youtube](https://www.youtube.com/watch?v=zHUpx90NerM&list=PLillGF-RfqbYeckUaD1z6nviTp31GLTH8&index=40), [doc](https://cssreference.io/transitions/)
        * typography: [doc](https://cssreference.io/typography/)
        * background: [doc](https://cssreference.io/backgrounds/)
        * animations: [doc](https://cssreference.io/animations/)
* Responsive Layout: [article1](https://learn.shayhowe.com/advanced-html-css/responsive-web-design/), [article2](https://internetingishard.com/html-and-css/responsive-design/)
* CSS Preprocessor: SASS
    * Kaaafi cool [article](https://www.creativebloq.com/web-design/what-is-sass-111517618)
    * [@youtube: sass using gulp](https://www.youtube.com/watch?v=rmXVmfx3rNo)
* **Frameworks**
    * Bootstrap: {most popular}
        * [DOC](https://getbootstrap.com/docs/4.3/layout/overview/)
        * [Cheatsheet1](https://hackerthemes.com/bootstrap-cheatsheet/),[cheatsheet2](https://github.com/aayush4vedi/The-Hitchhikers-Guide-to-the-Full-Stack-Developer/blob/master/Files/bootstrap_cheatsheet.zip)
        * [&youtube](https://www.youtube.com/watch?v=5GcQtLDGXy8&list=PLillGF-RfqbYeckUaD1z6nviTp31GLTH8&index=29)
        * most popular, easier syntax, quicker
        * CDN's :: [bootstrap,js,jq](https://getbootstrap.com/docs/4.1/getting-started/introduction/) + [Google Font](https://fonts.google.com/) + [Font Awesome](https://mdbootstrap.com/md-bootstrap-cdn/)
        * Use **Flexbox** with bootstrap for easy implementation
        * Notes:
            * **Trick:** `margin: 0 auto;` //fill the screen(top, bottom), auto readjust on sides
            * Multiple columns for responsive layout across all sizes `<div class="col-6 col-md-4">.col-6 .col-md-4</div>`
            * You can edit the default bootstrap classes as well(color,height etc)
            * order of linking bootstrap & own style.css: bootrstrap > style.css
            * Do `class= "container"` to use the magic of `Grids`
            * How not to make background image tiling on resizing the browser, use `html{ height: 100%;}`
            * [Spacing](https://getbootstrap.com/docs/4.3/utilities/spacing/) is very easy here! `class="mr-3` for right margin of 3%
            * `class="text-center"` , `class="justify-content-center"`and BOOM! *Man there is a class for evrything in bootstrap, just google it w/p even trying CSS.*
            * first include bootstrap link then your css
        * All the things:(**bold** ones are used more freq)
            * Layout
                * **Grid** : `.container` `.row` `.col`
                * Media
                * **Display** : notation, visibility
                * **Spacing** : margin(`m`), padding(`p`), Width (`w-25`)
            * Content:
                * **Typography**
                * images: `.img-fluid` makes images responsive(it's magic!)
                * figures
                * Tables
            * Components:
                * Alert
                * Badge
                * Breadcrumbs :show navigation path
                * **Buttons**, Button-groups
                * Card
                * Carousel
                * Collapse :show content when button click
                * Dropdowns
                * Forms
                * Jumbotron
                * Modal : click on button to open dialogue-box
                * **Nav**s & **Navbar**
                * Pagination
                * Popovers : click to show info on side
                * Progress bar
            * Utilities:
                * Background color: `bg-color`
                * Display : `.inline`, `.flex`
                * Embed: insert video/slideshow
                * Flex
                * Float
                * Shadows
                * **Text** : 
                    * Alignment: `.text-center`
                    * Transform: `.text-lowercase`
                    * Bold/Italics: `.font-weight-bold`
                    * Text Wraping
                * Vertical Alignment : `.align-baseline`
                * Visibility: `.visible` or `.invisible`
        
        * Icons: [FontAwesome](https://fontawesome.com/)


        > **TinyProject**: [@LandingPage](https://github.com/aayush4vedi/TinyProject-LandingPage) - for a Social Media app(Bootstrap:beginner)<br>
        > **TinyProject**: [@Bugsy](https://github.com/aayush4vedi/Bugsy) -(Bootstrap:medium)<br>
        > **MediumProject**: [@CakeWorld](https://github.com/aayush4vedi/Cake-World) -(Bootstrap:master)

    * Semantic UI:
        * **Very lighweight:** If you just want to syle a button, just include CDN for a button 
        > **Project:** Restful Blog App
    * Materialize: {based on google's material design}
        * looks better than all :wink:
        * [@youtube](https://www.youtube.com/watch?v=nqT8c5OFjEQ&list=PLillGF-RfqbYeckUaD1z6nviTp31GLTH8&index=32), [@doc](https://materializecss.com/)
        * [cheatsheet-CSS](https://github.com/aayush4vedi/The-Hitchhikers-Guide-to-the-Full-Stack-Developer/blob/master/Files/materialize_sandbox.zip),[cheatsheet:jQ+JS](https://github.com/aayush4vedi/The-Hitchhikers-Guide-to-the-Full-Stack-Developer/blob/master/Files/materialize_sandbox-JS.zip)
    * Foundation: {mobile first}
        * [@youtube](https://www.youtube.com/watch?v=DEu5xYEZx18&list=PLillGF-RfqbYeckUaD1z6nviTp31GLTH8&index=30), [@doc](https://foundation.zurb.com/)
        * @Foundation: [Building blocks](https://foundation.zurb.com/building-blocks/): already coded UI components for plug-n-play
        * more for advanced programming, more customizable, flatter=> easily recognizable
        * [cheatsheet](https://github.com/aayush4vedi/The-Hitchhikers-Guide-to-the-Full-Stack-Developer/blob/master/Files/foundation_sandbox.zip)
    * Bulma:{Flexbox based CSS}
        * [@youtube](https://www.youtube.com/watch?v=IiPQYQT2-wg&list=PLillGF-RfqbYeckUaD1z6nviTp31GLTH8&index=31), [@doc](https://bulma.io/documentation/)
        * [cheatsheet](https://github.com/aayush4vedi/The-Hitchhikers-Guide-to-the-Full-Stack-Developer/blob/master/Files/bulmasandbox.zip)

* **Project:** Build responsive-portfolio website(sass, jQ,JS): [@youtube septology](https://www.youtube.com/watch?v=gYzHS-n2gqU&list=PLillGF-RfqbYoGoCjKoMOkVznV6aSXKzU)


## 2. Basic Deployment(small scale)
* web-hosting for small websites: [@youtueb](https://www.youtube.com/watch?v=UN7S4zd8h-k): CPanel,inmotion, filezilla, wordpress
* netify(from github, gitlab), also free, comes with *npm-cli* : [@youtube](https://www.youtube.com/watch?v=bjVUqvcCnxM)
* github(**gh-pages**): [@youtube](https://www.youtube.com/watch?v=SKXkC4SqtRk)

## 3. JS (Vanilla JS)
### 3.1. Basic syntax :ballot_box_with_check:
* `slice()`
* `splice()`
* `forEach()`
* `map()`
* `var` v/s `let`
* `this`
### 3.2. DOM manipulation :white_check_mark:	
* [MDN doc](https://developer.mozilla.org/en-US/docs/Web/API/Document_Object_Model/Introduction)
* DOM Selection:
    * `var ele = document.getElementById('')`
    * `var ele = document.querySelector('`#id`/`.class`/`ele`')`
    * `var ele = document.querySelectorAll('')`
    * `var ele = document.getElementByClassName('')`
    * `var ele = document.getElementByTagName('')`
* DOM Manipulation: 
    * changing/adding/removing element's style ::
        * Single class: `ele.style.xxx` (color,border,margin etc)
        * Multiple classes: <br>
        `.new-class{color:red;size:10px;} //define the new class`<br>
        `ele.classList.add("new-class");  //apply it`
        * similarly `classList.remove()` & `classLsit.toggle()`
        
    * changing content of a tag
        * `ele.textContent = "blah";` //works only on **span**
        * `etc.innerHtml` //returns the whole element
    * changing attributes(src, href etc)
        * `img.setAttribute("src", "new uri")`
        * `img.getAttribute()`
* DOM Events :
    * `ele.addEventListener(type, functionToCall)` //don't write `()` if calling an already declared funtion
    * type: `click`, `change`, `mouseover` [MDN](https://developer.mozilla.org/en-US/docs/Web/Events)
* Notes
    * `var x = document.querySelector(h1);` returns an object
    * `x.style.color = "red;"`
    * `querySelector` vs `getElementById` :: prefer `querySelector` always as it can select anything(element/class/id)    

> **MiniProject:** Score Keeper [@ScoreKeeper](https://github.com/aayush4vedi/ScoreKeeper) <br>
> **Project:** [@ColorGame](https://github.com/aayush4vedi/Color-Game) ::BOOOYEAAAAAAAHH! Did myself mostly.Proud of me right now , :satisfied: :satisfied: 
### 3.3. API, AJAX(XHR)
### 3.4. ES6+
### 3.5 VanillaJS (=== JavaScript)
Using "VanillaJS" means **using plain JavaScript without any additional libraries like jQuery**.

People use it as a **joke** to remind other developers that many things can be done nowadays without the need for additional JavaScript libraries.

Here's a funny site that jokingly talks about this: http://vanilla-js.com/
* Vanilla in slang means: unexciting, normal, conventional, boring
* So VanillaJS is the same as pure Javascript.

## 4. JQuery
* [CDN](https://code.jquery.com/) to be included in **header**. Include your **`.js`** file in **body**
* **About**
    * is a JS lib to make DOM manipulation, event handeling, animation, AJAX(http requests) etc easier.
    * Why Use jQuery:
        * Fixes broken DOM API(`querySelector()` & etc didn't exist at it's inception)
        * Brevity & Clearlty
        * Ease of use
        * cross browser support(even on IE)
        * AJAX
        * A lot of people use it!
    * Why [YOU MIGHT NOT NEED JQUERY.com](http://youmightnotneedjquery.com/)
        * DOM API is no longer broken(`querySelector()` & etc exist now)
        * It doesn't do anything you can't do w/o it
        * It's an unnecessary dependecny
        * Performance
        * A lot of people are moving away from it!
* **Resources**
    * [DOC](https://api.jquery.com/)
    * Kaafi sahi(& exhaustive) tut-serise: [tutorialRepublic](https://www.tutorialrepublic.com/jquery-tutorial/) 
    * [@youtube](https://www.youtube.com/watch?v=2OMzGhlIZpg) 
    * from *css-tricks* : [tut](https://css-tricks.com/lodge/learn-jquery/)
* **Methods**
    * Selection: `$(selector)` : similar to `querySelectorAll()` // e.g. `$('#boobs')`
        * Specefic selection: `$(li ul .class-name)`
        * Select first of type: 
            * `$("div:first-of-type").css(styles)` //css style
            * `$("div:first").css(styles)` //jQuery style. Similar `-last`
        * [All Other Selectors](https://api.jquery.com/category/selectors/)
    * **[css()](https://api.jquery.com/css/)** 
        * gives style: `$(this).css('color')` gives color
        * manipulating Style: `$
        (selector).css(property, value)`
        * Multiple styles:<br> `var styles = {color: 'red', font: 'bold'};`<br> `$(#textie).css(styles);`
    * Common Methods/APIs: [complete list](https://api.jquery.com/) : all are both- get&set 
        * **[text()](https://api.jquery.com/text/)**: Get/Set
            * Stripes all html & gives complete text of selector
            * Updating: `$('h1').text("New Text!");`
        * **[html()](https://api.jquery.com/html/)**
        Get/ Set the HTML contents 
            * Updating: `$('ul').html('<li>I hacked into your system</li>')`
        * **[attr()](https://api.jquery.com/attr/)**  Get/Set the value of an attribute 
            * `$(#image).attr('src','new url');`
        * **[val()](https://api.jquery.com/val/)**  Get/Set the current value 
        * **addClass()**
        * **removeClass()**
        * **toggleClass()** : Never under-estimate me!
    * **[Events](https://api.jquery.com/category/events/)**
        * **click()**: 
            `$(#id).click(function(){alert("clicked");});`
        * **keypress()**:
            * **.which()** gives the keyCode
            * `$(#id).keypress(function(e){
                if(e.which === 13){
                    alert("You pressed Enter");
                    }
                });`
            * [Javascript **Key Codes**](https://www.cambiaresearch.com/articles/15/javascript-char-codes-key-codes)
            * `Enter = 13` (keycode)
        * **on()** :
            `$(#id).on('click', function(){})`
            * 'on()' v/s `click()`: 
                * `click()` adds listeners for exixting elements//wont function for the dynamically created `li`s:
                `$("li").click(function(){
                    $(this).toggleClass('completed');
                    });`
                * `on()` will add listeners for all potential future elements//add on parents(existing elements)
                `$("ul").on('click', 'li', function(){
                    $(this).toggleClass('completed');
                });`
        * Bubbling up : for a `div>ul>li>span`, when you click on `span`, all others are also get clicked.
            * To Prevent: `$("span").click(function(event){event.stopPropagation()l});` //Doesnt work on ES6 style function
        * Deleting someone's parent: `$(this).parent().remove();` 
            * `$(this).parent().fadeOut(500, ()=>{$(this ).remove();});`
    * **[Effects](https://api.jquery.com/category/effects/)**
        * fadeOut(timeInMillisec)
            * Passing Callback:
                 `$(#button).on('click', ()={` <br>
                    `$(.div).fadeout(1000, ()={`<br>
                                  `console.log('I'll be logged when fading out is complete.');`<br>
                                  `$(this).remove();` <br>
                    `});`<br>
                `});`
        * fadeToggle()
        * slideDown()/ slideUp() / slideToggle()
    * **[Manipulation](https://api.jquery.com/category/manipulation/)**
> **Project:** [@ToDoList](https://github.com/aayush4vedi/To-Do-list), a beautiful thing made with css, jq & love
<br>
> **Project:** `@KeyDJ` a [patatap](https://patatap.com/) clone, built using [PaperJS](http://paperjs.org) & [HowlerJS](https://howlerjs.com/), sounds taken from [here](https://github.com/jonobr1/Neuronal-Synchrony). <br>
    --->> TODO: add animations & more sounds like [patatap](https://patatap.com/)




---
**ACHIEVED:: Basic Front-End Developer**

---


## 5. JS Front-End Frameworks

### 1. React
### 2. Angular
### 3. Vue

## 6. JS-State Management
### 1.1. Redux
### 1.2. State API
### 2.1. NgRx
### 3.1. VueX

--- 

# III.  Back-End

## 1. NodeJS
To run JS on server-side(up until now, we were running JS on browser only).
* Install a package: `npm install <package_name>`
* Include a pacakge: `var pkg = require('package_name');`
* Start a project: `mkdir <project_name>` -> `cd->` -> `npm init`
* Export a variable: `module.exports = x;`
* Import a variable: `var x = require('./models/file_containing_x')`
## 2. Frameworks
### 1. **Express**
A light, most popular NodeJS Web Development framework.
* Installing: `npm install express --save`
* Using: <br>
    `var express = require('express');`<br>
    `var app = express();`<br>
    `app.get('/route', (req,res)=>{
        res.send('yo!');
    });`<br>
    `app.listen(3000,()=>{console.log('I love you 3000');});`
* Auto server restart: **Nodemon**   (*no-demon*)
    * Installing: `npm i -g nodemon`
    * Set ` 'main': 'index.js'` in `package.json`
    * Run: Use `nodemon` in-place of good ol' `node index.js`
* EJS(Embedded JavaScript)
    * `npm install ejs --save`
    * **HTML**:
        * Make views in `/views`
        * Rendering view: `res.render('file.ejs');`  (don't write `/views` here)
        * OR if you don't want to write `.ejs` : simply write `app.set('view engine','ejs');` at the top & render files like: `res.render('file');`
    * **CSS**:
        * Make `/public/stylesheets/main.css`
        * In `index.js` use: `app.use(express.static(__dirname+ '/public'));` 
        * Include into views as: `<link rel='stylesheet' type="text/css" href='stylesheets/main.css'>` (don't write `/public` here, **`/`** important hai babu: as it says to look in root dir)
    * **Dynamic routing**: <br>
        `app.get('/route/:x', (req,res)=>{`<br>
            `var x = req.params.x;`<br>
            `var data = [a,b,c];`<br>
            `res.render('file.ejs', {routeTyped: x , data:data });`<br>
        });`<br>
        where in `file.ejs:<h1 You typed: <%= routeTyped %>h1>`
    * `<%= %>`: to render HTML
    * `<% %>` : to write logical JS
    * **Partials** :(html snippets like header/footer) as separate `ejs` files:
        * write them inside `/views/partials`
        * include them in other ejs files: `<%  include partials/header %>` (no need to write `/view` or add `.ejs` to filename)
    * **Body Parser**: Use npm package `body-parser` while dealing with forms(POST ).Use:
        * `var bodyParser = require('body-parser');`
        * `app.use(bodyParser.urlencoded({extended: true})); `
    * **Redirecting**: `res.redirect('/route');`
    * **Error Handling:** `connect-flash `

### 2. **Koa**

### 3. APIs
## Data Formats
### A. XML
* Extended Markup Language
* Syntactically similar to HTML
* Doesn't describel presentation like HTML does
```
<person>
    <name>Me</name>
    <age>21</age>
    <gender>Male</gender>
</person>
```
### B. JSON
* Looks like Javascript objects
* Everything is a string
```
{
    'person': {
        'name': 'Me',
        'age':'21',
        'gender':'Male'
    }
}
```
## 3.2
* Making Request in node: Install package: `npm install request`, then:
```
var request = require('request');
request('http://www.google.com', function (error, response, body) {
  console.log('error:', error); // Print the error if one occurred
  console.log('statusCode:', response && response.statusCode); // Print the response status code if a response was received
  if(!error && response.statusCode==200){
    console.log('body:', body); // Print the HTML for the Google homepage.
  }
});
```

## 4. Server Rendered Pages
## 4.1. React: Next.JS
## 4.2. Vue: Nuxt.JS
## 4.3. Angular: Angular Universal

## 5. CMS
### 5.1. Ghost
### 5.2. Keystome

---

# IV. DataBase

## 1. Relational

### 1.1. MySQL
### 1.2. PostgreSQL
### 1.3. MS SQL

## 2. NoSQL

### 2.1. Mongo
* Most pouplar db with node.
* **MEAN**  Stack(**M:** mongo **E:** express **A:** angular **N: ** node)
* **Installation**: 
[here](https://treehouse.github.io/installation-guides/mac/mongo-mac.html)
* **Commands**:
    * `mongod` -Run mongo-deamon/server : Keep running in a separate tab
    * `mongo` -Run the shell
    * `quit()` -Exit shell
    * <kbd>command</kbd> + <kbd>c</kbd> -Stop deamon
    * `help`
    * (1)`show dbs` -display all dbs
    * (2)`use <db-name>`: create a new db &/OR switch to it
    * (3)`show collections` : see the details of "that db"
    * **Insert**  `db.<db-name>.insert({key:'value',...})`  //no `'` in key-name
    * **Find** `db.<db-bname>.find()` -view all entries in `<db-name>`
        * `db.<db-name>.find({name: 'sam', ...})` -finds specefic entries in `<db-name>`
    * **Update**  `db.<db-bname>.update({..find..},{..update..})`  
        * Just Update:` db.<db-bname>.update({name: 'sam'},{status: 'committed'})` //updates Sam's status but *deletes the name* 
        * Add New Property :`db.<db-bname>.update({name: 'sam'},{$set: {name: 'Mark',status: 'committed'}})` //Updates name & Adds a new property
    * **Delete**  `db.<db-name>.remove({name: 'sam', ...})` 
        * Delete first n entries: `db.<db-name>.remove({name: 'sam', ...}).limit(n)` 
         * Drop entire db: `db.<db-name>.drop()`
    * **Find By ID**(inside code): `<ModelName>.findByID(req.params.id, (err,found)=>{if(!err){res.render("template", {data:found})}})`
* **Mongoose** <br>
    is a npm package to interact with mongo inside node.
    * Import & Connect:<br> 
        `var mongoose = require('mongoose');`<br>
       `mongoose.connect('mongodb://localhost/car_db');` // if car_db doesn't exist, it makes  
    * Declare schema: // for new-commers <br>
        `var carSchema = new mongoose.Schema({`<br>
            `brand: String`,<br>
            `year: Number`<br>
        `});`<br>
    * Make model:<br>
        `var Car = mongoose.model('Car', carSchema);`
    * Use the model:<br>
        `var cross = new Car({brand: 'Toyota', year: 2016});`
    * Save it to make an entry:<br> 
        `cross.save();`
        * **Callback** to confirm:<br>
            `cross.save((err, car)=>{`<br>
                `if(err){console.log(""ERROR!);}`<br>
                `else{cosole.log(car);}`<br>
            `})`
* **Seeding** : See [here](https://github.com/aayush4vedi/YelpHotel/blob/master/seeds.js) in my **YelpHotel** project

### 2.2. Memcached

## 3. Cloud
### 3.1. AWS
### 3.2. GCD
### 3.3. Firebase

## 4. Lightweight
### 4.1. SQLite
### 4.2. Redis

---
# V. REST

The Seven Deadly Routes every CRUD app has to have(in the same url fashion):

| Name    |   API                 |   Purpose                                    | Mongoose Method          |
| :----   | :-------------------: | :-------------                               |:---------------:         |
| Index   |  GET /blogs           | List all entries                             |      Blog.find()         |                          
| New     |  GET /blogs/new       | Show a new blog form                         |          N/A             |
| Create  |  POST /blogs          |  Create a new blog & redirect somewhere      |      Blog.create()       |
| Show    |  GET /blogs/:id       |  Show details of a specefic blog             |     Blog.findById()      |
| Edit    |  GET /blogs/:id/edit  |  Show edit form for one blog                 |     Blog.findById()      |
| Update  |  PUT /blogs/:id       |  Update a specefic blog & redirect somewhere |  Blog.findByIdAndUpdate()|
| Destroy |  DELETE /blogs/:id    |  Delete a specefic blog & redirect somewhere |  Blog.findByIdAndRemove()|

## Exemplary Implementation

[RESTful Blog](https://github.com/aayush4vedi/RESTfulBlog)
**Learnings**
* `<p><%= blog.body.substring(0,10) %>... </p>` to display like `this is a bo...` 
* Date: `created:{type: Date,default: Date.now}`
* Simplify the date: `blog.created.toDateString()`
* Allow write HTML inside input(use `dash -`): `<p><%- blog.body %>... </p>` **Don't do it at all** for hackers `<script>alert('I hacked you!')</script>`
* npm install `express-sanitizer` => Allows good HTML(`<h1>`,`<p>`...) and removes bad HTML(`<script>`...) from input
* HTML forms just support GET & POST req.No PUT/DELETE.
    * (1) `npm install method-override`
    * (2) `var methodOverrid = require('method-override'); app.use(methodOverrid('_method'));`
    * (3) `<form action="/blogs/<%= blog._id %>?_method=PUT" method="post" class="ui form">`

# VI. Models & Data Association:
Add comments to a post:
1. Make `comments` model:
```
var commentSchema = mongoose.Schema({
    text   : String,
    author : String,
});
module.exports = mongoose.model('Comment', commentSchema);
```
2. Connect with post:
```
var hotelSchema = new mongoose.Schema({
    name          : String,
    image         : String,
    description   : String,
    comments      : [
        {
            type: mongoose.Schema.Types.ObjectId,
            ref : "Comment"
        }
    ]
});
```
3. In `index.js`
```
app.post('/posts/:id/comments',(req,res)=>{
    //lookup for post using id
    //create new comment
    //connect comment to post
    //redirect to show page
    Hotel.findById(req.params.id, (err, post)=>{
        if(err){
            console.log(err);
            res.redirect('/posts/'+req.params.id);
        }else{
            Comment.create(req.body.comment, (err, comment)=>{
                if(err){
                    console.log(err);
                }else{
                    post.comments.push(comment);
                    post.save();
                    console.log('Created comment!',comment);
                    res.redirect('/posts/' + post._id);
                }
            });
        }
    });
}); 
```
---
# VII. Authentication & Authorization
* ## Learn from here: [article](https://scotch.io/tutorials/easy-node-authentication-setup-and-local)
* PassportJS 
   * [doc](http://www.passportjs.org/)
   * Passport is authentication **middleware** for Node.js, can be used in any **Express-based** web application. 
   * **Authentication Strategies**: using local, Facebook, Twitter, and more.
   * How to Use: [doc](http://www.passportjs.org/docs/authenticate/)
* **Project** : @YelpHotel
    * Packages:
        * `express`
        * `ejs`
        * `body-parser`
        * `mongoose`
        * `passport`
        * `passport-local`
        * `passport-local-mongoose`
        * `express-session`
        * `password-hash`
    * Handeling REGISTRATION:
        1.  In User-model:
        ```
        var mongoose = require('mongoose');
            bcrypt   = require('bcrypt-nodejs');

        // define the schema for our user model
        var userSchema = mongoose.Schema({
            local            : {
                username        : String,
                password     : String,
            },
            facebook         : {
                id           : String,
                token        : String,
                name         : String,
                email        : String
            },
            google           : {
                id           : String,
                token        : String,
                email        : String,
                name         : String
            }

        });

        // methods ======================
        // generating a hash
        userSchema.methods.generateHash = function(password) {
            return bcrypt.hashSync(password, bcrypt.genSaltSync(8), null);
        };

        // checking if password is valid
        userSchema.methods.validPassword = function(password) {
            return bcrypt.compareSync(password, this.local.password);
        };

        module.exports =  mongoose.model('User', userSchema)
        ```
        2. Imports in `./config/passport.js`
        ```
       var LocalStrategy   = require('passport-local').Strategy;
            User            = require('../models/User');

        module.exports = function(passport) {
            // used to serialize the user for the session
            passport.serializeUser(function(user, done) {
                done(null, user.id);
            });
            // used to deserialize the user
            passport.deserializeUser(function(id, done) {
                User.findById(id, function(err, user) {
                    done(err, user);
                });
            });
            // LOCAL SIGNUP ============================================================
            passport.use('local-signup', new LocalStrategy({
                // by default, local strategy uses username and password, we will override with username
                usernameField : 'username',
                passwordField : 'password',
                passReqToCallback : true // allows us to pass back the entire request to the callback
            },
            function(req,username, password, done) {
                // asynchronous
                // User.findOne wont fire unless data is sent back
                process.nextTick(function() {
                // find a user whose username is the same as the forms username
                // we are checking to see if the user trying to login already exists
                User.findOne({ 'local.username' :  username }, function(err, user) {
                    if (err)
                        return done(err);
                    if (user) {
                        return done(null, false, req.flash('signupMessage', 'That username is already taken.'));
                    } else {
                        var newUser            = new User();
                        newUser.local.sername    = username;
                        newUser.local.password = newUser.generateHash(password);
                        newUser.save(function(err) {
                            if (err)
                                throw err;
                            return done(null, newUser);
                        });
                    }
                });    

                });

            }));
            // LOCAL LOGIN =============================================================
            passport.use('local-login', new LocalStrategy({
                usernameField : 'username',
                passwordField : 'password',
                passReqToCallback : true // allows us to pass back the entire request to the callback
            },
            function(req, username, password, done) { // callback with username and password from our form
                User.findOne({ 'local.username' :  username }, function(err, user) {
                    if (err)
                        return done(err);
                    if (!user)
                        return done(null, false, req.flash('loginMessage', 'No user found.')); // req.flash is the way to set flashdata using connect-flash
                    if (!user.validPassword(password))
                        return done(null, false, req.flash('loginMessage', 'Oops! Wrong password.')); // create the loginMessage and save it to session as flashdata
                    return done(null, user);
                });

            }));

        };


        ``` 
        3. AUTH ROUTES & MIDDLEWARE in `index.js`:
        ```
        //REGISTER
        app.get('/register',(req,res)=>{
            res.render('auth/register');
        });
        //SIGN-UP
        app.post('/register', passport.authenticate('local-signup', {
            successRedirect : '/hotels', 
            failureRedirect : '/register', 
            failureFlash : true 
        }));
        //LOGIN
        app.get('/login',(req,res)=>{
            res.render('auth/login');
        });
        app.post('/login', passport.authenticate('local-login', {
            successRedirect : '/hotels', 
            failureRedirect : '/login', 
            failureFlash : true 
        }));
        //LOGOUT
        app.get('/logout', function(req, res) {
            req.logout();
            res.redirect('/');
        });

        // ROUTE MIDDLEWARE to make sure a user is logged in
        function isLoggedIn(req, res, next) {
            if (req.isAuthenticated())
                return next();
            res.redirect('/');
        }
        ```

---

# VII. DevOps
## 1. Deployment:linux,ssh,gitlab, server-software(Ngnix,Apache)
## 2. Platforms: AWS,Azure,Google cloud,Heroku
## 3. Virtualization: docker
## 4. Testing
---


# VIII. Beyond Stack

## 0. GraphQL
## 0. TypeScript
## 0. App Dev: react-native, flutter,ionic
    >>Project-idea: unity app for auto daily booking cab/ordering food(Hackathon@Rzp)
## 0. Desktop apps: electron
## 0. Progressive Web Aps(PWA)
## 0. AI, ML, Data Science
## 1. Caching
## 2. Security
## 3. ElasticSearch
## 4. CDN
---
# IX. Concepts & Principles
* Design Principle:: **Separation of Concerns([SoC](https://softwareengineering.stackexchange.com/questions/32581/how-do-you-explain-separation-of-concerns-to-others)) :** Every separate(& changable) thing should be at separate place.To allow single point of change in entire code.


![Intro](https://github.com/aayush4vedi/The-Hitchhikers-Guide-to-the-Full-Stack-Developer/blob/master/Media/intro.png)
![FrontEnd](https://github.com/aayush4vedi/The-Hitchhikers-Guide-to-the-Full-Stack-Developer/blob/master/Media/frontend.png)
![BackEnd](https://github.com/aayush4vedi/The-Hitchhikers-Guide-to-the-Full-Stack-Developer/blob/master/Media/backend.png)
![Devops](https://github.com/aayush4vedi/The-Hitchhikers-Guide-to-the-Full-Stack-Developer/blob/master/Media/devops.png)


# Self-Project Ideas:
* [Personal Management System](https://github.com/Volmarg/personal-management-system): make recurrent/auto-tracking
* unity app for auto daily booking cab/ordering food
* Do Something about unsorted-but-important knowledge I'm gaining from HN, Quora etc.I don't know how & where to store it, but I'd sure as hell don't want it to go wasted.











































