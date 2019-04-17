![picture alt](https://github.com/aayush4vedi/The-Hitchhikers-Guide-to-the-Full-Stack-Developer/blob/master/Media/wallpaper.jpg)

# I. Basic Tools
## 1. Text Editor
* **VSCode**<br/>
    * Linux Shortcuts
        * Show Command Palette <kbd>control</kbd> + <kbd>shift</kbd> + <kbd>P</kbd>
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

    * Useful Extensions

        **>> Style:**
        * My fav theme: Gruvbox Dark(medium)
        * Material Icon Theme
        * vscode-pdf

        **>> HTML/CSS:**
        * Emmet( ```life-savior```): [cheatsheet](https://docs.emmet.io/cheat-sheet/), lorem30
        * HTML Boilerplate
        * Beautify css/sacss
        * Color Highlight
        * CSS Peek
        * IntelliSense for CSS class names

        **>> Others**
        * Live Server
            


## 2. Design

   * Creation: Adobe Photoshop, XD(not in Linux yet :grimacing: )
   * Tickling: [photopia](https://www.photopea.com/) 


## 3. Terminals

* **Linux** >> Guake
* **MacOS** >> iTerm2
* **Windows** >> :thumbsup:

## 4. Browser Tools

* HTTP response status codes: [MDN doc](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status)
* **Chrome Dev Tools**
    * [Google Doc](https://developers.google.com/web/tools/chrome-devtools/beginners/html)
    * [Crash Course @Youtube](https://www.youtube.com/watch?v=x4q86IjJFag) :Kafi cool intro to all tabs
    * [for CSS @Youtube](https://www.youtube.com/watch?v=Z3HGJsNLQ1E): Steal other website's styles


## 5. Git
## 5. Postman

---

# II. Front-End 

## 1. HTML & CSS

* Semantic HTML5 elements
* Basic CSS
* CSS3: 
    * box-model: [doc](https://cssreference.io/box-model/)
    * **grid**(2D & preferred): [@youtube](https://www.youtube.com/watch?v=jV8B24rSN5o), [doc](https://cssreference.io/css-grid/), [css-tricks:doc](https://css-tricks.com/snippets/css/complete-guide-grid/)
    * **flexbox**(1D): [@youtube](https://www.youtube.com/watch?v=JJSoEo8JSnc&list=PLillGF-RfqbYeckUaD1z6nviTp31GLTH8&index=23), [doc](https://cssreference.io/flexbox/)
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
        * [&youtube](https://www.youtube.com/watch?v=5GcQtLDGXy8&list=PLillGF-RfqbYeckUaD1z6nviTp31GLTH8&index=29), [doc](https://getbootstrap.com/docs/4.3/layout/overview/)
        * most popular, easier syntax, quicker
        * [cheatsheet](https://github.com/aayush4vedi/The-Hitchhikers-Guide-to-the-Full-Stack-Developer/blob/master/Files/bootstrap_cheatsheet.zip)
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

## 2. JQuery
* Kaafi sahi(& exhaustive) tut-serise: [tutorialRepublic](https://www.tutorialrepublic.com/jquery-tutorial/) 
* [@youtube](https://www.youtube.com/watch?v=2OMzGhlIZpg) 
* from *css-tricks* : [tut](https://css-tricks.com/lodge/learn-jquery/)

## 4. Basic Deployment(small scale)
* web-hosting for small websites: [@youtueb](https://www.youtube.com/watch?v=UN7S4zd8h-k): CPanel,inmotion, filezilla, wordpress
* netify(from github, gitlab), also free, comes with *npm-cli* : [@youtube](https://www.youtube.com/watch?v=bjVUqvcCnxM)
* github(**gh-pages**): [@youtube](https://www.youtube.com/watch?v=SKXkC4SqtRk)

## 5. JS
### 1. Basic syntax
### 2. DOM manipulation
### 3. API, AJAX(XHR)
### 4. ES6+


## 6. JS Front-End Frameworks

### 1. React
### 2. Angular
### 3. Vue

## 7. JS-State Management
### 1.1. Redux
### 1.2. State API
### 2.1. NgRx
### 3.1. VueX

--- 

# III.  Back-End

## 1. NodeJS

## 2. Frameworks
### 1. **Express**
### 2. **Koa**

## 3. Server Rendered Pages
## 3.1. React: Next.JS
## 3.2. Vue: Nuxt.JS
## 3.3. Angular: Angular Universal

## 3. CMS
### 3.1. Ghost
### 3.2. Keystome

---

# IV. DataBase

## 1. Relational

### 1.1. MySQL
### 1.2. PostgreSQL
### 1.3. MS SQL

## 2. NoSQL

### 2.1. MongoDB
### 2.2. Memcached

## 3. Cloud
### 3.1. AWS
### 3.2. GCD
### 3.3. Firebase

## 4. Lightweight
### 4.1. SQLite
### 4.2. Redis


---

# V. DevOps
## 1. Deployment:linux,ssh,gitlab, server-software(Ngnix,Apache)
## 2. Platforms: AWS,Azure,Google cloud,Heroku
## 3. Virtualization: docker
## 4. Testing
---


# VI. Beyond Stack

## 0. GraphQL
## 0. TypeScript
## 0. App Dev: react-native, flutter,ionic
## 0. Desktop apps: electron
## 0. Progressive Web Aps(PWA)
## 0. AI, ML, Data Science
## 1. Caching
## 2. Security
## 3. ElasticSearch
## 4. CDN


![Intro](https://github.com/aayush4vedi/The-Hitchhikers-Guide-to-the-Full-Stack-Developer/blob/master/Media/intro.png)
![FrontEnd](https://github.com/aayush4vedi/The-Hitchhikers-Guide-to-the-Full-Stack-Developer/blob/master/Media/frontend.png)
![BackEnd](https://github.com/aayush4vedi/The-Hitchhikers-Guide-to-the-Full-Stack-Developer/blob/master/Media/backend.png)
![Devops](https://github.com/aayush4vedi/The-Hitchhikers-Guide-to-the-Full-Stack-Developer/blob/master/Media/devops.png)






















































