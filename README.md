### 1.开发工具

推荐:VSCODE + 插件  tab 4空格

### 2.构建工具

gulp/webpack  gulp任务js有提供,根据需求自行修改

### 4.代码版本管理

git    git地址:code.iadmob.com

### 5.部署环境

流程:内网-预发布(可能无)-外网: 环境Nginx / TOMCAT

### 6.开发思维/代码规范

要求:组件化开发,模块化开发,模块注释

代码规范:http://alloyteam.github.io/CodeGuide/  希望规范点,养成习惯最好

### 7.代码测试/各种端调试 

①.fiddler抓包/chrome://inspect 等等

各种cli一般有代码测试,重点:不懂不会多问多问多问/别闷起来/互相之间多交流

### 8.常用插件CDN

zeptojs-ALL://rs3.uu08.net/iad/waph5/plugins/zepto_1.2_full.min.js

jquery://rs3.uu08.net/iad/waph5/plugins/jquery.min.js

其余待补充...


#### VSCODE常用插件

##### Auto Close Tag	
    自动添加HTML / XML关闭标签

##### Auto Rename Tag	
    自动重命名配对的HTML / XML标签

##### Beautify	
    HTML、CSS、JS、JSON SASS语法高亮,格式化代码的工具,ctrl+shift+p输入beautify就有提示。

##### Bracket Pair Colorizer	
    颜色识别匹配括号 对应括号显示同样的颜色，以防我们搞混括号配对。

##### Better Comments  
    不同的注释显示不同的颜色，*，？，！起头然后开始写，你可以看到注释的颜色是不同的

##### Bootstrap 3 Sinnpet 
    该插件配合Bootstrap框架使用，可以很便捷的生成类似于图片轮播等页面效果。


##### Code Runner	
    非常强大的一款插件，能够运行多种语言的代码片段或代码文件：C，C ++，Java，JavaScript，PHP，PythonPerl，Ruby，Go等等安装完成后，右上角会出现：▶  帮助我们运行代码的工具，比如你要运行一个js文件，打开这个文件，然后ctrl+alt+n就可以运行文件，系统自动调用node帮我们运行文件。

##### change-case	
    虽然 VSCode 内置了开箱即用的文本转换选项，但其只能进行文本大小写的转换。而此插件则添加了用于修改文本的更多命名格式，包括驼峰命名、下划线分隔命名，snake_case 命名以及 CONST_CAS 命名等

##### Chinese (Simplified) Language Pack for Visual Studio Code	
    中文简体语言包

##### Color Info	
    这个便捷的插件，将为你提供你在 CSS 中使用颜色的相关信息。你只需在颜色上悬停光标，就可以预览色块中色彩模型的（HEX、 RGB、HSL 和 CMYK）相关信息了

##### CSS Peek	
    使用此插件，你可以追踪至样式表中 CSS 类和 ids 定义的地方。当你在 HTML 文件中右键单击选择器时，选择“ Go to Definition 和 Peek definition ”选项，它便会给你发送样式设置的 CSS 代码

##### Debugger for Chrome	前端调试, [查看使用方法](https://www.jianshu.com/p/66033d4949bf)

##### ESLint	
    EsLint可以帮助我们检查Javascript编程时的语法错误。比如：在Javascript应用中，你很难找到你漏泄的变量或者方法。EsLint能够帮助我们分析JS代码，找到bug并确保一定程度的JS语法书写的正确性

##### filesize	
    在底部状态栏显示当前文件大小，点击后还可以看到详细创建、修改时间

##### Git History	
    以图表的形式查看 git 日志
##### GitLens — Git supercharged	
    显示文件最近的 commit 和作者，显示当前行 commit 信息

##### HTML Boilerplate	
    通过使用 HTML 模版插件，你就摆脱了为 HTML 新文件重新编写头部和正文标签的苦恼。你只需在空文件中输入 html，并按 Tab 键，即可生成干净的文档结构

##### HTMLHint	
    HTML 代码格式检测

##### HTML Snippets	
    代码自动填充

##### htmltagwrap	
    在选中HTML标签中外面套一层标签 ”Alt + W” (“Option + W” for Mac)

##### HTML CSS Support 
    让 html 标签上写class 智能提示当前项目所支持的样式 新版已经支持scss文件检索

##### Image Preview	
    鼠标移到路径里显示图像预览

##### Indenticator	
    突出目前的缩进深度

##### intelliSense for CSS class names in HTML	
    把项目中 css 文件里的名称智能提示在 html 中

##### Import Cost 
    引入包大小计算,对于项目打包后体积掌握很有帮助

##### Icon Fonts  
    这是一个能够在项目中添加图标字体的插件。该插件支持超过 20 个热门的图标集，包括了 Font Awesome、Ionicons、Glyphicons 和 Material Design Icons。

##### JavaScript (ES6) code snippets	
    es6代码片段

##### jQuery Code Snippets    
    jquery 重度患者必须品

##### jQuery Snippets 
    与HTML CSS Support类似，是一款支持jQuery的基础插件

##### Live Server	
    浏览器实时刷新

##### Node.js Modules Intellisense	
    可以在导入语句中自动完成JavaScript / TypeScript模块

##### npm Intellisense	
    require 时的包提示

##### Minify 
    这是一款用于压缩合并 JavaScript 和 CSS 文件的应用程序。它提供了大量自定义的设置，以及自动压缩保存并导出为.min文件的选项。它能够分别通过 uglify-js、clean-css 和 html-minifier，与 JavaScript、CSS 和 HTML 协同工作  

##### Path Intellisense	
    路径自动补全

##### Project Manager 
    在多个项目之前快速切换的工具

##### Prettier Prettier 
    是目前 Web 开发中最受欢迎的代码格式化程序。安装了这个插件，它就能够自动应用 Prettier，并将整个 JS 和 CSS 文档快速格式化为统一的代码样式。如果你还想使用 ESLint，那么还有个 Prettier – Eslint 插件，你可不要错过咯！

##### open in browser  
    顾名思义就是在浏览器中打开，不过在安装后需要配置快捷键。

##### Quokka.js	
    Quokka 是一个调试工具插件，能够根据你正在编写的代码提供实时反馈,它易于配置，并能够预览变量的函数和计算值结果。另外，在使用 JSX 或 TypeScript 项目中，它能够开箱即用。使用方法: ctrl+shift+p 输入 quokka 选择 new javascript 就可以了

##### Regex Previewer	
    这是一个用于实时测试正则表达式的实用工具。它可以将正则表达式模式应用在任何打开的文件上，并高亮所有的匹配项

##### SVG Viewer	
    此插件在 Visual Studio 代码中添加了许多实用的 SVG 程序，你无需离开编辑器，便可以打开 SVG 文件并查看它们。同时，它还包含了用于转换为 PNG 格式和生成数据 URI 模式的选项

##### Vetur	Vue 语法高亮显示, 语法错误检查, 代码自动补全(配合 ESLint 插件效果更佳)

##### VueHelper

##### vscode-fileheader	
    顶部注释模板，可定义作者、时间等信息，并会自动更新最后修改时间,快捷键: Ctrl+Alt+i   (默认信息可在 文件→首选项→设置 中修改)

##### vscode-icon  
    让 vscode 资源树目录加上图标，必备良品！



