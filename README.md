![picture alt](https://github.com/aayush4vedi/The-Hitchhikers-Guide-to-the-Full-Stack-Developer/blob/master/Media/wallpaper.jpg)


# Useful Things:
* **DRY**: Don't Repeat Yourself
* [This](https://studywebdevelopment.com/freelancing.html) guy is selling *Freelancing bundle.*
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
        * Markdown Preview <kbd>command</kbd> + <kbd>shift</kbd> + <kbd>V</kbd>
        * Find/Replace <kbd>control</kbd> + <kbd>F</kbd>/<kbd>H</kbd>
        * Split Editor <kbd>control</kbd> + <kbd>Front-\Slash</kbd>
        * Open Next <kbd>control</kbd> + <kbd>tab</kbd>
        * Previous <kbd>control</kbd> +<kbd>shift</kbd>+ <kbd>tab</kbd>
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
* **.gitignore**
    * `/folder-name` : `/node_modules'    '/build`
    * `.filename`    : `.test.js`
* Anatomy of Good Commit Messages:
    * when you write a commit message you are writing it as if it’s **about to be applied**, rather than *about what you just did*.
    * Provide as much context as you can: the 6 months rule-will you get it after 6 months? If no, it's not a good commit message.
    * For long commits: use [templates](https://medium.com/sitewards/git-tips-template-your-commit-messages-187d8a2051b8)
* **Markdown**
    * Add Badges: `<a href="url"><img src="https://img.shields.io/badge/<label>-<text>-<hexcolor(f39f37)>" alt="label"></a>`
    * Align to center: `<p align="center"></p>`
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
    * **@media** : [Article](https://medium.com/@banuriwick/min-width-max-width-media-queries-994e2ec5fca3)
    
    <hr>

     * **Notes:** 
        * `background-color` is for background & `color` is for text.
        * Make alternate `li`'s color different:<br> 
            `li{background: white;}`<br>
            `li:nth-child(2n){background: black;}`
        * `box-sizing: border-box;`
        * `margin: 10% auto;` is a life-savor: puts the div/id/class in centre
        * `::placeholder { color: blue;}`
        * `* {margin:0; padding:0; box-sizing: border-box;}` // avoid inconsistencies across browsers


* CSS3: 
    * box-model: [doc](https://cssreference.io/box-model/)
    * **grid**(2D & preferred): [@youtube](https://www.youtube.com/watch?v=jV8B24rSN5o), [doc](https://cssreference.io/css-grid/), [css-tricks:doc](https://css-tricks.com/snippets/css/complete-guide-grid/)
    * **flexbox**(1D): [@youtube](https://www.youtube.com/watch?v=JJSoEo8JSnc&list=PLillGF-RfqbYeckUaD1z6nviTp31GLTH8&index=23), [doc](https://cssreference.io/flexbox/)  >> aligh items man-makfik inside a div
        * See down for more
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
* **CSS: Animation**
    * **Tricks:**
        * `ease-in-out`: slow start & end
        * `filter: grayscale(100%)` : make image BnW
        * `animation: jiggle 4s;` is awesome
    * Links:
        * Cool Website built using css: [30species-30pieces](http://www.species-in-pieces.com/#)
        * Why Animation is necessary: [Article](https://medium.com/bridge-collection/improve-the-payment-experience-with-animations-3d1b0a9b810e):Improve payment experience with animation
    * **Pseudo-class**: is a keyword added to a selector that specifies a special state of the selected element
        * [MDN](https://developer.mozilla.org/en-US/docs/Web/CSS/Pseudo-classes) list 
        * `:hover` 
            ```css
            button:hover {
                color: blue;
            }
            ```
        * `:focus` for input fields majorly
            ```css
            input:focus {
                color: red;
            }
            ```
        * `:active`
            ```css
            a:active {
            color: red;
            }
            ```
    * **Transform**: modifies the coordinate space of elemet: rotate, scale, skew, or translate
        * Move: `transform: translate(120px, 50px);` //`(-50%, -50%)`: to bring it in center
        * Scale: `transform: scale(2, 0.5);`
        * Rotate: `transform: rotate(0.5turn);`
        * Multiple: `transform: scale(0.5) translate(-100%, -100%);`
    * **Transition:** is a shortcut property for `transition-property`, `transition-duration`, `transition-timing-function`, and `transition-delay`.
        * [MDN](https://developer.mozilla.org/en-US/docs/Web/CSS/transition)
        ```css
        /* property name | duration | timing function | delay */
        transition: margin-right 4s ease-in-out 1s; 
        ```
    * [List](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_animated_properties) of Animatable Properties in CSS.
    * What should be Animated?(*for faster performance*)
        * `transform:` `translate`. `scale`, `rotate`, `opacity`
    * **Keyframe Animation** : 
        * controls the intermediate steps in a CSS animation sequence by defining styles for keyframes along the animation sequence. 
        * This gives more control over the intermediate steps of the animation sequence than *transitions*.
        * [MDN](https://developer.mozilla.org/en-US/docs/Web/CSS/@keyframes)
        * `<p>HELLO!</p>`
        ```css
            p {
                animation-name: rainbowtext;
                animation-duration: 5s;
                animation-timing-function: linear;
                animation-delay: 0s;
                animation-iteration-count: infinite;
            }
            @keyframes rainbowtext {
                0%{
                    color:red;
                    font-size: 20px;
                }
                25%{
                    color:orange;
                }
                50% {
                    color:yellow;
                    font-size: 40px;
                    transform: translateX(200px);
                }
                75%{
                    color: green;
                }
                100% {
                    color: purple;
                    font-size:20px;
                }
            }
        ```
        * Cool Animation Examples(**Must Get Inspiration**): [Walking Cat](https://codepen.io/SoyEva/full/LRjWzZ/) | [Xmas Tree](https://codepen.io/aayush4vedi/pen/QWLvOMy) | [Mr Jello](https://codepen.io/FabioG/full/QjLreK/) | [Clock](https://codepen.io/iliadraznin/full/JcqbE/) | [Loading Icons](https://codepen.io/RRoberts/pen/pEXWEp) | [Codepen-Home](https://codepen.io/): search yours
    * **Flexbox:**(`Abse flexbox hi use karna hai`)
        * Docs: [CSS-Tricks](https://css-tricks.com/snippets/css/a-guide-to-flexbox/) | [CSS-Reference](https://cssreference.io/flexbox/) | [Find-froggy](http://flexboxfroggy.com/)
        * **Flex-Container Properties:**
            * `display: flexbox;`
            * `flex-direction: ` `row`(default) | `row-reverse` | `column` | `column-reverse`
            * `flex-wrap: wrap;` : makes each item go till max width/height, if reqd in multiple lines
            * `justily-content: ` `flex-end` | `center` | `space-between` | `space around`
                * justifies how space b/w items is distributed in flex container **along main axis**
            * `align-items:` `flex-start` | `flex-end` | `center` | `baseline` | `stretch`(default value)
                * justifies how space b/w items is distributed in flex container **along cross axis**
            * `align-content:` `flex-start` | `flex-end` | `center` | `baseline` 
                * defines space destributin b/w **rows** in flex-container **along cross axis**
        * **Flex-Item Properties**
            * `order` : making items  inside container in wanted order
            * `flex`  : defines how a flex item will grow/shrink to fit the available space in containere
                * `flex-grow:1\2\3; `  : how unused space should be spread among flex items
                * `flex-shrink:1\2`: how item should shrink when there isn't enough space in container
                * `flex-basis` : like width, but only for `flex-direction: row` (useless for `column`)
            * `align-self` : override `align-items` on individual flex items
        * Examples:
            * [Sidebar](https://codepen.io/Colt/pen/qXOqyN) | [Navbar](https://codepen.io/Colt/pen/WEQQwq) | [Polygon Widget](https://codepen.io/Colt/pen/oexwvb) | [Holy Grail Layout](https://codepen.io/Colt/pen/pryaJr?editors=1100) 
        * **Browser Support Articles:** [Flexbox-Mixing old & new](https://css-tricks.com/using-flexbox/) | [How to deal with older browsers](https://medium.com/css-mine/flexbox-how-to-deal-with-older-browsers-fbf6eb8c7a65)
        * [Startup website-full](https://demo.tutorialzine.com/2016/06/freebie-landing-page-template-with-flexbox/) -using Flexbox
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

## 3. Testing
* Jasmine(JS) -BDD, Unit Testing
    * [Starter Code](https://codepen.io/eschoppik/pen/ZybNdo) for Jasmine
    * Essential Keywords:
        * **describe** : "let me describe ______ to you."
        * **it**       : "let me tell you about _____."
        * **expect**   : "here is what I expect."
    * Demo:
        ```js
            var earth = {
                isRound: true,
                numberFromSun: 3
            }
            describe("Earth", function(){
                it("is round", function(){
                    expect(earth.isRound).toBe(true)
                });
                it("is the third planet from the sun", function(){
                    expect(earth.numberFromSun).toBe(3)
                });
            });
                //2 specs, 0 failures
        ```
    * **Matchers:** are the functions we attach to the result of expect function
        * `toBe`/`not.toBe`, `toBeCloseTo`, `toBeDefined`,  `toBeFalsy/toBeTruthy` ,`toBeGreaterThan/toBeLessThan`, `toContain`, `toEqual` ,`jasmine.any()`
        * Implementation:
            ```js
                describe("Jasmine Matchers", function() {
                    it("allows for === and deep equality", function() {
                        expect(1+1).toBe(2);
                        expect([1,2,3]).toEqual([1,2,3]);
                    });
                    it("allows for easy precision checking", function() {
                        expect(3.1415).toBeCloseTo(3.14,2);
                    });
                    it("allows for easy truthy / falsey checking", function() {
                        expect(0).toBeFalsy();
                        expect([]).toBeTruthy();
                    });
                    it("allows for easy type checking", function() {
                        expect([]).toEqual(jasmine.any(Array));
                        expect(function(){}).toEqual(jasmine.any(Function));
                    });
                    it("allows for checking contents of an object", function() {
                        expect([1,2,3]).toContain(1);
                        expect({name:'Elie', job:'Instructor'}).toEqual(jasmine.objectContaining({name:'Elie'}));
                    });
                });
                //5 specs, 0 failures
            ```
    * Pending Specs: [code](https://codepen.io/eschoppik/pen/gRaNgg)
    * Spies: [doc](https://blog.codeship.com/jasmine-spyon/)
    * Clock: `jasmine.clock().install()`
* **TDD**
    * *Test Driven Development*
    * Red -> Green -> Refactor -> Repeat
    * Steps:
        1. Write the tests 
        2. See all the tests fail
        3. Write code to pass the tests
        4. Refactor code as necessary
        5. Repeat
* **BDD**
    * *Behavior Driven Development*
    * is a subset of TDD
    * involves being verbose with our style & describing behavior of functionality
* Other Types of Testing:
    * Unit Tests - testing pieces of functionality: **what Jasmine Does**
    * Integration Tests(built on unit tests)
    * Acceptance Tests
    * Stress Tests
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

### 3.3. ES5++
## ES5(2015)
* **BABEL:** :is a *transpiler*,  Tasks:
    * (older)ES6+  => older ES5(supported by all browsers)
    * (curr) JSX   => VanillaJS
* **~~var~~ let+const:**
    * `let`    : declares a local variable in a block scope(between `{ }`)(even in `if`)
    * `const`  :  values can be assigned once and they cannot be reassigned<br>
               : const `obj`'s values can be reassigned, but now the obj.
    * ~~`var`~~: is now the weakest signal available when you define a variable in JavaScript. The variable may or may not be reassigned, and the variable may or may not be used for an entire function, or just for the purpose of a block or loop.
* **Destructuring**
    * simply implies breaking down a complex structure into simpler parts. 
    * allows you to assign the properties of an array or object to variables using syntax that looks similar to array or object literals
    * [Nice Article](https://codeburst.io/es6-destructuring-the-complete-guide-7f842d08b98f)
    * Obj Destructuring: 
    ```js
        const obj = {
            name        : "John Show",
            pet         : "ghost",
            firstName   : "Targaryen"
        }
        const {name, pet} = obj;
        let {firstName} = obj;

        const student = {
            name: 'John Doe',
            age: 16,
            scores: {
                maths: 74,
                english: 63
            }
        };
        // We define 3 local variables: name, maths, science
        const { name, scores: {maths, science = 50} } = student;
        console.log(`${name} scored ${maths} in Maths and ${science} in Elementary Science.`);
        // John Doe scored 74 in Maths and 50 in Elementary Science.
    ```
    * Array Destructuring:
    ```js
        let f1 = a[0], f2 = a[1], f3 = a[2];
        let {f1,f2,f3} = a;

        var [foo, [[bar], baz]] = [1, [[2], 3]];
        console.log(foo);// 1
        console.log(bar);// 2
        console.log(baz);// 3

        const rgb = [200, 255, 100];
        const [,, blue] = rgb;
        console.log(`Blue: ${blue}`); // Blue: 100

        var [head, ...tail] = [1, 2, 3, 4];
        console.log(tail);// [2, 3, 4]
    ```
* **String**
    * ~~`const msg = "hello "+name+", you are "+ age+ "years old."`~~
    * Template String: ```const msgBetter = `hello $(name), you'll be $(age+10) after 10 years.`   ```
* Data Type: **Symbol()**
    * Every symbol value returned from Symbol() is **unique**. 
    * A symbol value may be used as an *identifier* for object properties.
    * ```js
        var sym1 = Symbol();
        var sym2 = Symbol('foo');
        var sym3 = Symbol('foo');
        Symbol('foo') === Symbol('foo'); // false
        ```
* **Advance Functions:** 
    * New way of writing: `const c = (a,b)=> a+b`
    * **Closure:** 
        * A function ran.The function executed.It's never going to execute again.
        * BUT it's going to remember that there are refrences to those variables.
        * SO, the child scope always has access to the parent scope.
        * Closures don't remember everything from outer function- just the *variables they need.*
    ```js
        // see how second() has access to var greet
        const first() => {
            const greet = 'hi';
            return function second(){
                console.log(greet + ' there ');
            }
        }
        first()(); //'hi there'
    ```
    * **Currying Fn:**
    ```js
    curryedMultiply = (n) => (m) => n * m
    curryedMultiply(3)(4) === 12 // true
    ```
    * **Compose Fn:**
    ```js
    const fOg = (f,g) => (a) =>f(g(a));
    const sum = (num) => num+1;
    fOg(sum, num)(5); //7
    ```
* Keyword **this**
    * a reversed keyword in JS
    * usually determined by *execution context*
    * Can be determined using 4 rules:
        * **Global** : when `this` is not inside declared object.<br>
            =====> returns *window* object
            ```js
             console.log(this);  // window
            ```
            ```js
            function f(){
                return this;
            }
            f(); // window
            ```
            * To avoid this, use: `"use strict"` in begining
        * **Object/Implicit Binding** : when `this` is inside declared object<br>
            =====> Returns value obj of *the closest parent*
        * **Explicit Binding:** Choose what we want the context of `this` using `call`, `apply` or `bind`
        * **New**

* **Advance Arrays:**
    * **`forEach`** iterates & just performs some action 
    ```js
    const arr = [1,2,3];
    const arr2;
    const tmp = arr.forEach((num)=>{
        arr2.push(num*2);
    });
    console.log(arr2); //(3)[2,4,6]
    ```
    * **`map`** iterates through an array & **returns** a value each time, which gets stored in the Map-Array i.e. creates a new array
    ```js
    const mapArray = arr.map((num)=>{
        return num*2;
    })
    ORRRR(shorter syntex)
    const mapArray = arr.map(num => num*2;)
    console.log(mapArray);//(3)[2,4,6]
    ```
    * **`filter`** iterates, filter elements & pushes them to a new(ly created array).
    ```js
    const filterArray = arr.filter( num =>{ return num<=2});
    ORRRR(shorter syntex)
    const filterArray = arr.filter(num => num<=2;)
    console.log(filterArray); //(2)[1,2];
    ```
    * **`reduce`** is map+accumulater(`i`):
    ```js
    const reduceArray = arr.reduce((i,num)=>{
        return i+num;
    },0);//0 is starting value of i
    console.log(i);//6
    ```
* **Advance Objects:**
    * Context: `this`
        * In browser: `console.log(this)` => `Window` object , `this.alert('hello')` => pops an alert because attribute of Window obj
        * ```js
            const ob = {
                a: ()={console.log(this);}
            }
            ob.a() //returns object {a}
    * Instantiation:
        * `Constructor` is the first thing to run when you make a copy
        ```js
            class Player{
                constructor(name, game){
                    this.name = name;
                    this.game = game;
                }
                introduce(){
                    console.log(`hello, I'm $(this.name) playing $(this.game)`)
                }
            }
        ```
        * `Extends`: when use it, need to call `super()` with the properties we want to pass to constructor 
        ```js
        class Wizard extends Player{
            constructor(name,game){
                super(name, game)
            }
            play(){
                console.log(`WEEEE, I'm a $(this.game)`);
            }
        }
        const wizard1 = new Wizard('Harry', 'Seeker');
        wizard1.introduce();
        const wizard2 = new Wizard('Cedric', 'Chaser');
        ```
* **Passed by value v/s Reference**
    * Primitve data types(*string, number, boolean, null, undefined, symbol*) are passed by value.
    * Objects are passed by reference.
        ```js
        let obj1 = { name: "Dwight Kurt Shrute"};
        let obj2 = obj1;
        obj2.name = "Dwight Fart Shrute";
        console.log(obj1);//{name: "Dwight Fart Shrute"}
        ```
    * Since **arrays are objects**, they are passed by reference TOO.
* **Type Coercion:**
    * when comparing two things of diff data types using `==`, one of them will be converted to the other's type by JS engine.
        * ```js 1 == '1'; //true;```
        * `1=== '1'; //false`
    * Nice JS Equality table: [website](https://dorey.github.io/JavaScript-Equality-Table/) | [MDN Sameness Comparisons](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Equality_comparisons_and_sameness)
## ES7(2016)
* Includes `trailing comma` in objects: {a:'a'`  , ` }
* `.includes()`
    * `'hello.includes('o')' ;//true`
* Exponantial Operator: `x**2 //x*x `

## ES8(2017)
* String Padding:`.padStart()` , `.padEnd()`
    * `'aayush'.padStart(4);  // "    aayush"` => appends 4 spaces in start of string
* Iterating Objects like arrays: `Object.values`  , `Object.entries`:
    * Before ES8, we had `Object.keys`
    ```js
    let obj ={
        a: 'aa',
        b: 'bb'
    }
    Object.keys(obj).forEach((key,index)=>{
        console.log(key,obj[key]); 
        // a aa
        // b bb
    })
    Object.values(obj).forEach(value =>{
        console.log(value);
        // aa
        // bb 
    })
    Object.entries(obj).forEach(value =>{
        console.log(value);
        // (2)['a' : 'aa')]
        // (2)['b' : 'bb')]
    })
    ```
## ES9(2018)
* **Promises:**
    * Promises save you from **callback hell**.
    * JavaScript is a synchronous programming language, but because of callback functions we can make it work like an Asynchronous Programming language.
    * **Def:** The Promise object represents the eventual completion (or failure) of an asynchronous operation, and its resulting value.
    * Methods
        1. Promise Creation 
            ```js
            let p1 = new Promise(function(resolve, reject) {
                if({condition})
                resolve("done");
                else
                reject(new Error("…---…"));
            });
            ```
        2. Handling( Callback)
            * Resolve
            ```js
            p1.then((data)=>{
                console.log(data); //done
            })
            ```
            * Reject
            ```js
            p1.then((data)=>{
                console.log(data)
            })
            .catch((err)=>{
                console.log(err);
            })
            ```
        3. Wrapping `setTimeout` with Promise
        ```js
        let p1 = new Promise((ressolve,reject)=>{
            setTimeout(()=>{
                console.log("2 seconds mei chalta ho toh chal!");
            },2000);
        })
        ```
        4. Promise Chaining: `//pehle poora hone ke baad hi agla chalega`
        ```js
        p1.then(()=>{…})
        .then(()=>{…})
        .then(()=>{…})
        .then(()=>{…})
        ```
        E.g. **Lesson**: `ek ki return values is passed on to the next.`
        ```js
        let p2 = Promise((resolve,reject)=>{
            resolve(5);
        })
        p2.then((data)=>{
            return data+1;
        })
        .then((data)=>{
            return data+1;
        })
        .then((data)=>{
            return data+1;
        })
        //returns 8
        ```
* **Async Foundation**
    * **Callback Function** : that is passed into other function as parameter then invoked by other function.
        * ```js   
            function cb(){console.log('calling from cb');}
            function higherOrder(g){
                console.log('a');
                g();
                console.log('b');
            }
            higherOrder(cb);
            //'a'
            //'calling from cb'
            //'b'
            ```
        * Higher order function:<br>
            A fn that accepts a callback as its parameter (see above e.g. )
        * Callbacks are used for:
            * Code Reuse
            * Advance Array Methods
            * Browser Event
            * AJAX Request
            * React Development
    * **setTimeout:** runs after t(*milliseconds*) time
    ```js
    let a = setTimeout(()={
        console.log("I'll run after 2 sec");
    },2000)
    ```
* **Async Await**
    * Async
        * enable us to write promise based code as if it were synchronous, but without blocking the execution thread. 
        * It operates asynchronously via the event-loop. 
        * Async functions will always return a value. 
        ```js
        async function firstAsync() {
        return 27;
        }
        firstAsync().then(alert); // 27
        ```

    * Await
        * The await operator is used to wait for a Promise. 
        * It can be used inside an Async block only.
        *  The keyword Await makes JavaScript wait until the promise returns a result. 
        * It has to be noted that it only makes the async function block wait and not the whole program execution.
        ```js
            async function firstAsync() {
                let promise = new Promise((res, rej) => {
                    setTimeout(() => res("Now it's done!"), 1000)
                });
                // wait until the promise returns us a value
                let result = await promise; 
                // "Now it's done!"
                alert(result); 
                }
            };
            firstAsync();
        ```
    
### 3.4 VanillaJS (=== JavaScript)
Using "VanillaJS" means **using plain JavaScript without any additional libraries like jQuery**.

People use it as a **joke** to remind other developers that many things can be done nowadays without the need for additional JavaScript libraries.

Here's a funny site that jokingly talks about this: http://vanilla-js.com/
* Vanilla in slang means: unexciting, normal, conventional, boring

### 3.5 AJAX: XHR, jQuer+AJAX, Axios
## AJAX:
* About:
    * AJAX = **A**synchronous **JA**vaScript & **X**ML (not a great name)
    * AJAX is not:
        * A lib
        * A framework
        * A tech
    * AJAX is...an **approach**(that's it)
    * term was coined in 2005. [That historic article](https://immagic.com/eLibrary/ARCHIVES/GENERAL//ADTVPATH/A050218G.pdf)
    * with AJAX we can build a website that loads w/o refreshing the page(send, receive req in background & update w/o disturbing current page )called=>**Single Page Apps**
    * Can be seen on Facebook, Pinterest
* Methods of making request with JS:
    1. XHR
    2. Fetch API
    3. 3rd party lib: `jQuery` & `Axios`
* **XHR**(XML Http Request):
    * Can be seen in Chromes Dev Tool menu(Network > All | `XHR` | JS)
    * Format: 
    ```js
    var XHR = new XMLHttpRequest();
    XHR.onreadystatechange = function(){
        if(XHR.readyState ==4 && XHR.status == 200 ){
            console.log(XHR.responseText); //"Random Zen Quote"
        }
    };
    XHR.open("GET","https://api.github.com/zen"); //Fun Fact: this api gives new random **ZEN** quote each time.
    XHR.send();
    ```
    * CodeExample: [Random Image Generator](https://codepen.io/Colt/pen/PKbVxM) | [Bitcoin Price Exercise](https://api.coindesk.com/v1/bpi/currentprice.json)
    * **Problems with XHR**
        * Ugly, bulky syntax
        * created 16 years ago
        * No streaming(large data)
        * Returns string(not JSON), so need to run `JSONParse()` every time
    * **Solution:** Fetch API
* **Fetch API**: Upgraded XHR
    * General Method:(default method: `GET`)
        ```js
        fetch(url)
        .then((res)=>{.
            return res.json(); //returns json obj
        })
        .then((data)=>{...})
        .catch((err)=>{...});
        ```
    * `POST` in fetch:
        ```js
        fetch(url, {
            method: POST,
            body: JSON.stringify{
                name: 'meep',
                age : 24,
            }
        })
        .then((data)=>{...})
        .cathc((err)=>{...})
        ```
    * [MDN doc](https://developer.mozilla.org/en-US/docs/Web/API/WindowOrWorkerGlobalScope/fetch) for other things: `header`, `credentials` etc
    * **Problems with Fetch:**
        * Support compatibility with multiple browsers for diff things
        * IE doesn't support Fetch *at all.*
* **jQuery with AJAX:**
    * **Methods:**
        * `.$.ajax`
            * rest 3 methods are shorthand methods for this one
            * ```js
                $.ajax({
                    method   : 'GET',
                    url      :  'some.api.com',
                    dataType : 'json'
                })
                .done((res)=>{..log(res)..})
                .fail((err)=>{console.log(err)})
              ```
            * [Doc](https://api.jquery.com/jQuery.ajax/)
        * Shorthand methods for `.$.ajax`:
            * `.$.get`
            * `.$.post`
            * `.$.getJSON` 
* **Axios:** A lightweight HTTP request lib
    * [Doc-github](https://github.com/axios/axios)
    * ```js
        axios.get(url)
        .then(function(res){
        console.log(res.data.results[0].question);
        })
        .catch(function(){
        console.log("ERR");
        })
      ```
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
## 5 Data Visualisation Libraries(JS)

### 5.1 D3js 
* (*Data-Driven Documents*) is a JS library for producing dynamic, interactive **data visualizations** in web browsers.
* Include in HTML-body bottom: `<script src="https://d3js.org/d3.v4.js"></script>`
#### D3 Methods For DOM Manipulation
- *if nothings is paased in, these methods will act as GETTERS*
* Select Elements
    * `d3.select(x)`    - single element
    * `d3.selectAll(x)` - multiple elements
    * `d3.node(x)` / `d3.nodes(x)` - returns *array* of matching HTML elements
* Set attr, prop, styles
    * `.style()` - set on existing elements
    ```js
    d3.select('#title')
        .style('color','#ffffff')
        .attr('class', 'new-class')
        .text('new title');
    ```
    * `.append(tagName)` - adds a new element of type `tagName` on every element in selection
* Get attr, prop on selections
    * same as above
* Chain D3 methods
    * shown in the above example
* Passing callback functions
    * Format: `function(_, index){//.......}`
    * E.g.
    ```js
    d3.selectAll('li')
        .style('background-color',(_,index)=>{
            return index % 2 == 0 ? 'white' : 'black';
        })
    ```
* Add Event Listerners
    * Format: `selection.on(eventType, callback)`
    * E.g.(**Adding** Event Listener):   `d3.select('h1).on('click',()=>{console.log('you have been clicked')})`
    * E.g.(**Removing** Event Listener):   `d3.select('h1).on('click',null)`
* Access event object inside listerners
    * Format: `selection.property(name, newValue)` 
        * Access a property(e.g. input value) which is not accessible as element attr
* Add & Remove DOM elements
* **Data Joins**: Appending all moivies as li(`id='#quotes'`)
    ```js
    let data = [
        {
            quote: "fsaf",
            movie: "efwaef",
            rating: "efs",
        },
        {....}
    ]
    d3.select('#quotes')
        .style('list-style', 'none')
        .selectAll('li')
        .data(data)
        .enter()
        .append('li')
            .text(d => '"' + d.quote + '" = '+d.movie)
            .style('margin', '20px')
            .style('padding', '20px')

    ```
* Remove DOM elements:
**e.g.** Delete all 'R' rated movies from list
```js
    let nonRQuotes = quotes.filter(movie=> movie.rating != 'R');
    d3.selectAll('li')
        .data(nonRQuotes, (d)=>{
            return d.quote;
        })
        .exit()
        .remove()
```
* General Update Pattern in D3
#### SVG & D3
* **SVG**:
    * Scalable Vector Graphics(SVG) -> scalable images(unlike .jpg/.png)
    * Vector vs Raster graphics: [GfG](https://www.geeksforgeeks.org/vector-vs-raster-graphics/)
    * E.g.: [Rectangle](https://codepen.io/mmmaaatttttt/pen/MoJKQr?editors=1100) , [Smiley-Star](https://codepen.io/mmmaaatttttt/pen/jLLbPJ?editors=1100), [Flags](https://codepen.io/mmmaaatttttt/pen/GvMZMq?editors=1100)
//TODO: not liking & getting D3 right now.**TBDL**
//TODO: get this project: [D3-emission](https://github.com/aayush4vedi/Emission-Data)

## 5.2 


## 6. JS Front-End Frameworks
* What & How:
    * is (JS) lib that handles DOM manipulation.
    * Handles navigation(using HTML5 push state): allows to  change address bar w/o refreshing the page
    * State Management:
        * in *jQuery*, we have to keep track of all data either in DOM or in some object
        * *Front-End Framework*: provides tools for it
    * is always run on **client side**, back-end mei NodeJS
### 6.1. React
* About:
    * Released by Facebook in 2013
    * is a view lib that uses *composable components*
    * other libs used with React:
        * **React Router** - deals with navigation in app
        * **Redux** - single place to store states in app 
* Why React?
    * To minimise DOM manipulation(which increases load on browser & makes app/website slow & increases bugs )
    * **Structure:** Atoms->Molecules->Organisms->Template->Pages
    * Maintains tree-like structure of keeping record of changes.i.e. if any component gets changed, only its children need to know.
* **CLI**:
    * `sudo npm install -g create-react-app`
    * In project directory: `create-react-app appname`(name can't contain CAPITAL LETTERS)
    * Run Server: `cd appname` -> `npm start`
    * Chrome Extension: [React Dev Tools](https://chrome.google.com/webstore/detail/react-developer-tools/fmkadmapgofadopljbjfkapdkoienihi?hl=en)
* **Components**
    * Format:
        ```js
            import React, {Component} from 'react'; //React is default export & Component isn't(hence got {})
            ...
            class Xxx extends Component{
                render(){
                    return(
                        <div className= 'xxx-class'>
                            <h1>XXX</h1>
                            <h3 style = {{fontSize: '3em', margin: '2px'}}>Nobody Does it better!</h3>
                        </div>
                    )
                }
            }
            export default Xxx;
        ```
* **Props**(Dumb-components): 
    * Def:
        * are immutable data passed to a component **from its parent**
        * are accessible in your component as an object called: `this.props`
    * props are simply things that come out of state.
    * parent feeds state to its child component and for child comp, it becomes a prop
    * E.g.
        ```js
        //parent
        class RecipeApp extends Component {
        render() {
            return (
            <div className="App">
                <Recipe
                    title="pasta"
                    ingredients={['flour', 'water']}
                    instructions="Mix ingredients"
                    img="spaghetti.jpg"
                />
            </div>
            );
          }
        }
        ```
        ```js
        //child component
        class Recipe extends Component {
            render() {
                const {title, img, instructions} = this.props;
                const ingredients = this.props.ingredients.map((ing, index) => (
                     <li key={index}>{ing}</li> 
                ));
                return (
                <div className="recipe-card">
                    <div className="recipe-card-img">
                        <img src={img} alt={title} />
                    </div>
                    <div className="recipe-card-content">
                        <h3 className="recipe-title">{title}</h3>
                        <h4>Ingredients:</h4>
                        <ul>
                            {ingredients}
                        </ul>
                        <h4>Instructions:</h4>
                        <p>{instructions}</p>
                    </div>
                    
                </div>
                );
            }
        }
        ```
    * **defaultProps:** to give props a default value
        ```js
        //parent
            class RecipeApp extends Component {
                static defaultProps = [
                    {
                        title: 'pasta';
                        ingredients : ['flour', 'water']
                        instructions : "Mix ingredients"
                        img : "spaghetti.jpg"
                    },
                    {...}
                ];
                render() {
                    return (
                    <div className="App">
                        {this.props.recipes.map((r, index)=>{
                            <Recipe
                                key             = {index} 
                                //--->
                                title           = {r.title}
                                ingredients     = {r.ingredients}
                                instructions    = {r.instructions}
                                img             = {r.img}
                                //<--
                                //OR
                                {...r} // will pass all properties of r
                            />
                        })}
                        />
                    </div>
                    );
                }
            }
            ```
    * **propType:** to specify what props a component is expecting
        * are used only in *development mode*
        * **Installation:** `npm install --save prop-types`
        * E.g.:
            ```js
                import PropTypes from 'prop-types';
                ...
                class IngredientList extends Component {
                    static propTypes = {
                        ingredients: PropTypes.arrayOf(PropTypes.string)
                                              .isRequired
                    }
                    render() {
                        return (
                        <ul>
                            {this.props.ingredients.map((ing, index) => (
                            <li key={index}>{ing}</li>
                            ))}
                        </ul>
                        );
                    }
                }
            ```
    * **props.children**
        * is a collection of children inside a component
        * E.g. Make a `Row` component
        ```js
        class App extends Component {
            render() {
                return (
                <Row>
                    <p>Timothy</p>
                    <div>Moxie</div>
                    <h1>React</h1>
                </Row>
                );
            }
        }
        class Row extends Component {
            render() {
                return (
                <div style={{
                    display: 'flex',
                    flexDirection: 'row',
                    justifyContent: 'space-around',
                }}>
                    {this.props.children}
                </div>
                )
            }
        }
        ```
* **State**
    * Stateful data
    * Data in our application that can change
    * **Passing:**
        * Passed from *parent to child* as **prop** : downwards
        * Should not be passed to parent(~~upwards~~) or sibling(~~lateral~~)
        * State should be owned by one component
    * Format:
    ```js
        class App extends Component {
            constructor(props) {
                super(props);
                this.state = { favColor: 'red' };
            }
            render() {
                return (
                <div>
                    My favorite color:
                    {this.state.favColor}
                </div>
                );
           }
        }
    ```
    * **setState** : The correct way to change state in your application
        * accepts an object with new properties and values for `this.state`
        * E.g.:
        ```js
        class App extends Component {
            constructor(props) {
                super(props);
                this.state = { favColor: 'red' };

                setTimeout(() => {
                this.setState({favColor: 'blue'})
                }, 3000);
            }
            render() {
                return (
                <div>
                    My favorite color:
                    {this.state.favColor}
                </div>
                );
            }
        }
        ```
        * setState that depends on *previous* state: use a function parameter
        ```js
        this.setState((prevState, props) => {
            return {
                counter: prevState.counter + 1
            };
        });
        ```
    * Purity: All changes to `this.state` should be pure(see [pure functions](https://hackernoon.com/javascript-and-functional-programming-pt-3-pure-functions-d572bb52e21c))
    
* **React Component Architecture**



### 6.2. Angular
### 6.3. VueJS

## 7. JS-State Management
### 7.1. Redux
### 7.2. State API
### 7.1. NgRx
### 7.1. VueX

--- 

# III.  Back-End

## 1. NodeJS
To run JS on server-side(up until now, we were running JS on browser only).
* Install a package: `npm install <package_name>`
* Include a pacakge: `var pkg = require('package_name');`
* Start a project: `mkdir <project_name>` -> `cd->` -> `npm init`
* Export a variable: `module.exports = x;`
* Import a variable: `var x = require('./models/file_containing_x')`
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
* Fake Dummy Data(for testing): [json placeholder](https://jsonplaceholder.typicode.com/)
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
# VII. Python
# 1. Basics
# 2. Data Analysis
# 3. Web Scraping
# 4. Task Automation


---

# VIII. DevOps
## 1. Deployment:linux,ssh,gitlab, server-software(Ngnix,Apache)
## 2. Platforms: AWS,Azure,Google cloud,Heroku
    Heroku does free deployment for light-traffic websites.
## 3. Virtualization: docker
## 4. Testing
---


# IX. Beyond Stack

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
* **PKMS** (Personal Knowledge Management System)Do Something about unsorted-but-important knowledge I'm gaining from HN,Youtube, Quora etc, terms & things I'm learning.I don't know how & where to store it, but I'd sure as hell don't want it to go wasted.
    * Temporary Fix: [Evernote](https://www.evernote.com/client/web?login=true#?anb=true&b=c0d68e64-d147-44ee-bf87-5619bf7a2821&n=9f12bf86-0009-4a76-bc83-df23282a0be7&s=s381&)
    * [Article](https://medium.com/@axtonliu/how-to-build-an-efficient-personal-knowledge-management-system-355332ae5991) listing the problem statement good, no solution
    * [Article](https://medium.com/@stangarfield/personal-knowledge-management-how-to-do-it-with-25-resources-and-10-books-on-pkm-2adce0e1d05c) listing resources
    * [askHN](https://news.ycombinator.com/item?id=20819478)
    * [askHN-2](https://news.ycombinator.com/item?id=17892731)
    * [This](https://dnote.io/blog/how-i-built-personal-knowledge-base-for-myself/) guy has build *something*



![picture alt](./Media/imready.gif)







































