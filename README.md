# **MinifyAll an extension for VSCode**

VSCode **minifier** for  **CSS**, **HTML** ,**JSON**, **Typescript**(testing), **JavaScript**(beta), **JavaScriptReact**(beta), **LESS**, **SASS**, **SCSS**, and **JSONC**. you will love its simplicity!

You can minify the file and replace all the content with the new minified text, **or** you can preserve the original document and get the minified text in another document!

Go to the extension *settings* and make it as you want, enable or disable: **minify on save**, **languages**, **hexadecimal shortener**, **messages**, and much more.

For more information check our: **[GitHub repository](https://github.com/Josee9988/MinifyAll)** and **[VisualStudio Marketplace](https://marketplace.visualstudio.com/items?itemName=josee9988.minifyall)**.

Do you want to help us improve the extension or did you found a bug?
**[Let us know](https://github.com/Josee9988/MinifyAll/issues)** or contact **[us](jgracia9988@gmail.com)**.

Check our **[changelog](CHANGELOG.md)**.

> We support up to **10** languages!

---

[![Version](https://vsmarketplacebadge.apphb.com/version-short/josee9988.minifyall.svg?style=for-the-badge&logo)](https://marketplace.visualstudio.com/items?itemName=josee9988.minifyall)
[![Downloads](https://vsmarketplacebadge.apphb.com/downloads/josee9988.minifyall.svg?style=for-the-badge&logo)](https://marketplace.visualstudio.com/items?itemName=josee9988.minifyall)
[![Rating](https://vsmarketplacebadge.apphb.com/rating-star/josee9988.minifyall.svg?style=for-the-badge&logo)](https://marketplace.visualstudio.com/items?itemName=josee9988.minifyall)
[![GitHub commit activity](https://img.shields.io/github/commit-activity/y/Josee9988/minifyall.svg?style=popout-square)](#minifyall-an-extension-for-vscode)

---

## **Installation** 🔩⚙

- Open the **Command Palette** of VSCode with **Ctrl+P** or **⌘P**
- And type:➡️
**```ext install josee9988.minifyall```**

### **Commands** 📐🛡

- **```Minify this document ⚡``` Or ```CTRL+ALT+M```**
- **```Minify this document and preserve the original ⛏```  Or ```CTRL+ALT+N```**

---

## **How does it look with real code?** 📸 😁

- The two commands available. First directly minifies the actual document and replaces the original code with the modified one, the second keeps the original document and creates a file with the modified text:

<img src="https://i.imgur.com/mBABVUM.png" alt="command" title="command" style="border-radius:15px; box-shadow: 6px 6px  #282829; max-height: 500px; max-width:500px;margin-left: auto; margin-right:auto;display: block;margin-left: auto;margin-right:auto;width:50%;"/>

- The output that you will find after you save your document:

<img src="https://i.imgur.com/oYztqCE.png" alt="output" title="output" style="border-radius:15px; box-shadow: 6px 6px  #282829; max-height: 500px; max-width:500px;margin-left: auto; margin-right:auto;display: block;margin-left: auto;margin-right:auto;width:50%;"/>

- The first and default command that replaces the actual code with the minified one:

<img src="https://i.imgur.com/bbAhxJj.gif" alt="Preview" title="preview" style="border-radius:15px; box-shadow: 6px 6px  #282829; max-height: 750px; max-width:750px;margin-left: auto; margin-right:auto;display: block;margin-left: auto;margin-right:auto;width:75%;"/>

- The second command that saves the minified text to other file and preserves the original text:

<img src="https://i.imgur.com/RTyX0PZ.gif" alt="Preview2nd" title="preview2nd" style="border-radius:15px; box-shadow: 6px 6px  #282829; max-height: 750px; max-width:750px;margin-left: auto; margin-right:auto;display: block;margin-left: auto;margin-right:auto;width:75%;"/>

- Also, minify when right-clicking on the code!

<img src="https://i.imgur.com/fXMQTc0.png" alt="rightclick" title="rightclick" style="border-radius:15px; box-shadow: 6px 6px  #282829; max-height: 750px; max-width:750px;margin-left: auto; margin-right:auto;display: block;margin-left: auto;margin-right:auto;width:75%;"/>

- Minify when right-clicking on a file of the menu without opening it!

<img src="https://i.imgur.com/UsO2dbn.gif" alt="rightclickMenu" title="rightclickMenu" style="border-radius:15px; box-shadow: 6px 6px  #282829; max-height: 750px; max-width:750px;margin-left: auto; margin-right:auto;display: block;margin-left: auto;margin-right:auto;width:75%;"/>

---

## **Languages available** 🧪🔥

- **CSS**
- **HTML**
- **JSON**
- **JavaScript**(beta)
- **JavaScriptReact**(beta)
- **JSONC**
- **LESS**
- **SASS**
- **SCSS**

---

## **Configuration settings** ⚙️⛓

<!-- markdownlint-disable no-inline-html-->

<details>
<summary>Click to see more info about the configuration settings</summary>

- If you want MinifyAll to **stop shortening colours**, such as RGB to 3 digit hex, or RGBA to hex, or 6 digit hex to 3 digit hex. If you enable it you might see some loss in colour accuracy

``` json
"MinifyAll.disableHexadecimalShortener": true|false //default 'true' (by default it is disabled)
```

- If you want MinifyAll to stop showing a **status bar** with information about the minimization after you minify a file. (True for disabling.)

``` json
"MinifyAll.disableStatusbarInformation": true|false //default 'false' (by default it is enabled)
```

- The Priority of the status bar. 0 Is the greatest.

``` json
"MinifyAll.statusbarPriority": integer //A number: default '0'
```

- Align the status bar indicator to the left or right.

``` json
"MinifyAll.statusbarAlignment": Left|Right //default 'left'
```

- Disables warning and information messages

``` json
"MinifyAll.disableMessages": true|false //default 'false' (by default it is enabled)
```

- Minify on save (Default command, which will minify your actual code)

``` json
"MinifyAll.minifyOnSave": true|false //default 'false' (by default it is enabled)
```

- Minify on save (Second command, which will minify your actual code into a new file)

``` json
"MinifyAll.minifyOnSaveToNewFIle": true|false //default 'false' (by default it is enabled)
```

### **Disabling languages configuration**

- Disables **html** minimization

``` json
"MinifyAll.disableHtml": true|false //default 'false' (by default it is enabled)
```

- Disables **css** minimization

``` json
"MinifyAll.disableCss": true|false //default 'false' (by default it is enabled)
```

- Disables **scss** minimization

``` json
"MinifyAll.disableScss": true|false //default 'false' (by default it is enabled)
```

- Disables **less** minimization

``` json
"MinifyAll.disableLess": true|false //default 'false' (by default it is enabled)
```

- Disables **sass** minimization

``` json
"MinifyAll.disableSass": true|false //default 'false' (by default it is enabled)
```

- Disables **json** minimization

``` json
"MinifyAll.disableJson": true|false //default 'false' (by default it is enabled)
```

- Disables **jsonc** minimization

``` json
"MinifyAll.disableJsonc": true|false //default 'false' (by default it is enabled)
```

- Disables **JavaScript** minimization //default 'true' (by default it is disabled because it is not on a stable version yet)

``` json
"MinifyAll.disableJavascript": true|false //default 'true' (by default it is disabled)
```

- Disables **JavaScriptReact** minimization //default 'true' (by default it is disabled because it is not on a stable version yet)

``` json
"MinifyAll.disableJavascriptReact": true|false //default 'true' (by default it is disabled)
```

- Disables **Typescript** minimization //default 'false' (by default it is enabled but it is not on a stable version yet)

``` json
"MinifyAll.disableTypescript": true|false //default 'true' (by default it is enabled)
```

</details>

---

## **Examples**

### **Css less sass scss**

<details>
<summary>Click to see an example of how the extension minifies CSS</summary>

*From:*

```css
.myClass {
    background-color: rgba(12, 12, 12, 0.8);
    background-color: rgb(12, 12, 12);
    background-color: #FAFAFA;
    /*other comment*/
    content: url("https://github.com/Josee9988/MinifyAll");
    margin-right: 0px;
}/* my comment
    */
```

*To:*

```css
.myClass{background-color:#0C0C0CCC;background-color:#111;background-color:#FFF;content:url("https://github.com/Josee9988/MinifyAll");margin-right:0}
```

- RGBA is formatted to hexadecimal.
- RGB is formatted to 3 digit value hexadecimal.
- 6 digit hexadecimal values are formatted to 3 digit value hexadecimal.
- There are no spaces.
- There is only one line.
- Multiline comments removed.
- Url '//' is not detected as a comment and can be perfectly placed.
- From 0px to 0

---

</details>

### **Json jsonc**

<details>
<summary>Click to see an example of how the extension minifies JSON</summary>

*From:*

``` json
{
"contributes": {
"commands": [{
"title": "Minify this document ⚡",
},
{
"color": "#FAFAFA", // comments
}/* multiline comment
*/
]
}
}
```

*To:*

``` json
{"contributes":{"commands":[{"title":"Minify this document ⚡"},{"color":"#FFF",}]}}
```

- Only one line.
- No unnecessary spaces.
- 6 Digit hex to 3 digit hex.
- No single-line comments.
- No multiline comments.
- Removed trailing comma before '}'.

---

</details>

### **JavaScript**

<details>
<summary>Click to see an example of how the extension minifies JavaScript</summary>

*From:*

```javascript
"use strict";
const {
    commands,
    window
} = require('vscode');
const FileSaver = require('fs')
const StringWithComments = "// not a comment /*" //this is my comment
if ((window.activeTextEditor.document.languageId == "css" && disableCss == false) || //myComment
    (window.activeTextEditor.document.languageId == "scss" && disableScss == false)) {
    const {
        document
    } = window.activeTextEditor;
    switch (window.activeTextEditor.document.languageId) {
        case "css":
            /*
            multi-line comments
            */
            console.log("Love this minifier !!!")
            break;
        default:
            break;
    }
}
```

*To:*

```javascript
"use strict";const{commands,window}=require('vscode');const FileSaver=require('fs')
const StringWithComments="// not a comment /*"
if((window.activeTextEditor.document.languageId=="css"&&disableCss==false)||(window.activeTextEditor.document.languageId=="scss"&&disableScss==false)){const{document}=window.activeTextEditor;switch(window.activeTextEditor.document.languageId){case"css":console.log("Love this minifier !!!")
break;default:break;}}let myString="hello//";myString.replace(/\/\//g,'');
```

- Only changes line if, at the end of a declaration or an import, that line does not end in ';' (So adding more ';' at the end of every line will help you minimize more your code).
- All irrelevant spaces removed.
- Spaces left are only within quotes (Strings) and variable declarations.
- If 'OR' and 'AND' are without spaces, the same as if condition or switch cases.
- All single line and multiline comments removed.
- Single line comments inside of a String will not be removed. (hello//) (// not a comment).
- Multi-line comments inside of a String will not be removed. (// not a comment **/\***).
- Regex expression with single-line comments will not be removed.
- No tabs.

---

</details>

### **Html**

<details>
<summary>Click to see an example of how the extension minifies HTML</summary>

*From:*

```html
<!DOCTYPE html>
<html lang='es'>

<head>
    <title></title>
    <meta charset='utf-8'>
    <link rel='stylesheet' href=''>
    <script type='text/javascript' src=''></script>
    <!-- test -->
</head>

<!-- ~~~~~✦✦✦✦✦ B O
 D Y ✦✦✦✦✦~~~~~ -->
<body>

</body>

</html>
```

*To:*

```html
<!DOCTYPE html><html lang='es'><head><title></title><meta charset='utf-8'><link rel='stylesheet' href=''><script type='text/javascript' src=''></script></head><body></body></html>
```

- Only one line.
- Only the necessary spaces.
- No tabs.
- No single-line comments.
- No multiline comments.

---

</details>

---

## **Known bugs:** 🛑🗑

- ⚠️ If the file you are trying to minify is **not saved** or is an Untitled default VSCode file *might* cause errors.
- ⚠️ If you are doing a regex without scaping the '//' it might be deleted as it must be scaped (\/\/).

---

## **Upcoming features?** ✅💡

- [x] Enable multiline comments inside a String or a path as single-line comments are.
- [ ] Optimize, comment and clean all the .replaces in src/langDefaultMinifiers/
- [ ] Right-click in a file of the menu will minify to another document.
- [ ] Right-click on a folder will minify all supported files.
- [ ] Path of the minify to another document (new file with minified text) customizable.

## **Built with** 🛠️🔧

- [Virtual Studio Code](https://code.visualstudio.com/)
- [Yo code](https://code.visualstudio.com/api/get-started/your-first-extension)
- [vsce](https://code.visualstudio.com/api/working-with-extensions/publishing-extension)

---

### Did you enjoyed the minifier? Help us raise these numbers up 🥰 🎉

[![Donate](https://img.shields.io/badge/Donate-Patreon-green.svg)](https://www.patreon.com/bePatron?u=22162331)
[![Github followers](https://img.shields.io/github/followers/Josee9988.svg?style=social)](#did-you-enjoyed-the-minifier-help-us-raise-these-numbers-up--)
[![Github stars](https://img.shields.io/github/stars/Josee9988/MinifyAll.svg?style=social)](#did-you-enjoyed-the-minifier-help-us-raise-these-numbers-up--)
[![Github watchers](https://img.shields.io/github/watchers/Josee9988/MinifyAll.svg?style=social)](#did-you-enjoyed-the-minifier-help-us-raise-these-numbers-up--)
[![Github forks](https://img.shields.io/github/forks/Josee9988/MinifyAll.svg?style=social)](#did-you-enjoyed-the-minifier-help-us-raise-these-numbers-up--)

[Check my VSCode theme](https://marketplace.visualstudio.com/items?itemName=josee9988.black-garnet-theme) 🧲

[Check my VSCode Markdown and Changelog snippets](https://marketplace.visualstudio.com/items?itemName=josee9988.changelog-and-markdown-snippets) 🌟

---

> ⚠️Remember that this extension does not guarantee a 100% effectiveness and may have some issue at some point. Use it at your own risk and always do backups of your code.⚠️

*Made with a lot of ❤️❤️ by **[@Josee9988](https://github.com/Josee9988)***
