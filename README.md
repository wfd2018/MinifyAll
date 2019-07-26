# **MinifyAll a extension for VSCode**

VSCode **minifier** for *JSON*, *CSS*, *HTML*, *LESS*, *SASS*, *SCSS*, and *JSONC*. you will love its simplicity!

You can minify the file and replace all the content with the new minified text, **or** you can preserve the original document and get the minified text in other document!

Not based in any minifier, made from scratch!

For more information check our: **[GitHub repository](https://github.com/Josee9988/MinifyAll)** and **[VisualStudio Marketplace](https://marketplace.visualstudio.com/items?itemName=josee9988.minifyall)**.

Want to help us improve the extension or you found a mistake?
**[Let us know](https://github.com/Josee9988/MinifyAll/issues)**.

Or contact **[me](jgracia9988@gmail.com)**.

Check our **[changelog](CHANGELOG.md)**.

How does it look? Look at our **[Screenshots](Screenshots/)**

---

<img src="https://i.imgur.com/mscnJe8.png" alt="logo" title="logo" style="border-radius:15px; box-shadow: 6px 6px  #282829; max-height: 500px; max-width:500px;margin-left: auto; margin-right:auto;display: block;margin-left: auto;margin-right:auto;width:40%;"/>

---

[![Version](https://vsmarketplacebadge.apphb.com/version-short/josee9988.minifyall.svg?style=for-the-badge&logo)](https://marketplace.visualstudio.com/items?itemName=josee9988.minifyall)
[![Downloads](https://vsmarketplacebadge.apphb.com/downloads/josee9988.minifyall.svg?style=for-the-badge&logo)](https://marketplace.visualstudio.com/items?itemName=josee9988.minifyall)
[![Rating](https://vsmarketplacebadge.apphb.com/rating-star/josee9988.minifyall.svg?style=for-the-badge&logo)](https://marketplace.visualstudio.com/items?itemName=josee9988.minifyall)
[![GitHub commit activity](https://img.shields.io/github/commit-activity/y/Josee9988/minifyall.svg?style=popout-square)](#minifyall-for-vscode)

---

## **Installation** 🔩⚙️

- Open the command Palette of VSCode with *Ctrl+P* or *⌘P*
- And type:➡️
**```ext install josee9988.minifyall```**

### **Commands** 📐

- **```Minify this document ⚡``` Or ```CTRL+ALT+M```**
- **```Minify this document and preserve the original ⛏```  Or ```CTRL+ALT+N```**

---

## **How does it looks with real code?** 📸 😁

- The two commands available. First directly minifies the actual document and replaces the original code with the modified one, the second keeps the original document and creates a file with the modified text:

<img src="https://i.imgur.com/mBABVUM.png" alt="command" title="command" style="border-radius:15px; box-shadow: 6px 6px  #282829; max-height: 500px; max-width:500px;margin-left: auto; margin-right:auto;display: block;margin-left: auto;margin-right:auto;width:50%;"/>

- The output that you will find after you save your document:

<img src="https://i.imgur.com/oYztqCE.png" alt="output" title="output" style="border-radius:15px; box-shadow: 6px 6px  #282829; max-height: 500px; max-width:500px;margin-left: auto; margin-right:auto;display: block;margin-left: auto;margin-right:auto;width:50%;"/>

- The first and default command that replaces the actual code with the minified one:

<img src="https://i.imgur.com/bbAhxJj.gif" alt="Preview" title="preview" style="border-radius:15px; box-shadow: 6px 6px  #282829; max-height: 750px; max-width:750px;margin-left: auto; margin-right:auto;display: block;margin-left: auto;margin-right:auto;width:75%;"/>

- The second command that saves the minfied text to other file and preserves the original text:

<img src="https://i.imgur.com/RTyX0PZ.gif" alt="Preview2nd" title="preview2nd" style="border-radius:15px; box-shadow: 6px 6px  #282829; max-height: 750px; max-width:750px;margin-left: auto; margin-right:auto;display: block;margin-left: auto;margin-right:auto;width:75%;"/>

---

## **Languages available** 🧪🔥

- CSS
- HTML
- JSON
- JSONC
- LESS
- SASS
- SCSS

---

## **Configuration**

- If you want MinifyAll to **stop shortening colors**, such as rgb to 3 digit hex, or rgba to hex, or 6 digit hex to 3 digit hex. (*True for disabling hexadecimal shortener*.) Default = false

``` json
"MinifyAll.disableHexadecimalShortener": true|false
```

- If you want MinifyAll to stop showing a **status bar** with information about the compression after you minify a file. (True for disabling.) Default = false

``` json
"MinifyAll.disableStatusbarInformation": true|false
```

- Priority of the status bar. 0 Is the greatest. Default = 0

``` json
"MinifyAll.statusbarPriority": integer
```

- Aligns the status bar indicator to the left or right.

``` json
"MinifyAll.statusbarAlignment": Left|Right
```

- Disables warning and information mensages

``` json
"MinifyAll.disableMessages": true|false
```

- Minify on save (Default command, which will minify your actual code)

``` json
"MinifyAll.minifyOnSave": true|false
```

- Minify on save (Second command, which will minify your actual code into a new file)

``` json
"MinifyAll.minifyOnSaveToNewFIle": true|false
```

### **Disabling languages configuration**

- Disables html minimization

``` json
"MinifyAll.disableHtml": true|false
```

- Disables css minimization

``` json
"MinifyAll.disableCss": true|false
```

- Disables scss minimization

``` json
"MinifyAll.disableScss": true|false
```

- Disables less minimization

``` json
"MinifyAll.disableLess": true|false
```

- Disables sass minimization

``` json
"MinifyAll.disableSass": true|false
```

- Disables json minimization

``` json
"MinifyAll.disableJson": true|false
```

- Disables jsonc minimization

``` json
"MinifyAll.disableJsonc": true|false
```

---

## **Examples**

### **Css**

*From:*

```css
.myClass {
    background-color: rgba(12, 12, 12, 0.8);
    background-color: rgb(12, 12, 12); /* my comment
    */
    background-color: #FAFAFA;
}
```

*To:*

```css
.myClass{background-color:#0C0C0CCC;background-color:#111;BACKGROUND-COLOR:#FFF}
```

- rgba is formatted to hexadecimal.
- rgb is formatted to 3 digit value hexadecimal.
- 6 digit hexadimal is formatted to 3 digit value hexadecimal
- There are no spaces
- There is only one line
- No single line comments
- No multiline comments

---

### **Json**

*From:*

``` json
{
"contributes": {
"commands": [{
"title": "Minify this document ⚡"
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

- Only one line
- No unnecesary spaces
- 6 Digit hex to 3 digit hex
- No single line comments
- No multiline comments

---

### **Html**

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

- Only one line
- Only neccessary spaces
- No tabs
- No single line comments
- No multiline comments

---

## **Known bugs:** 🛑

- Css classes or ids don't support *px* or *keyframes* as a **name**.

**Don't** do this

``` css
.myPxClass{
    margin-left:0px;
}
#myPxId{
    margin-left:0px;
}
```

- Save minified text to other file using json (second command in a json file) may cause your vscode linter or intellisense to show some errors that are actually *not errors*.

- If the file you are trying to minify is **not saved** or is an Untitled default vscode file may cause errors.

---

## **Built with** 🛠️🔧

- [Virtual Studio Code](https://code.visualstudio.com/)
- [Yo code](https://code.visualstudio.com/api/get-started/your-first-extension)
- [vsce](https://code.visualstudio.com/api/working-with-extensions/publishing-extension)

---

### Did you enjoyed the minifier? Help us raise these numbers up

[![Donate](https://img.shields.io/badge/Donate-Patreon-green.svg)](https://www.patreon.com/bePatron?u=22162331)
[![Github followers](https://img.shields.io/github/followers/Josee9988.svg?style=social)](#languages-primarily-tested)
[![Github stars](https://img.shields.io/github/stars/Josee9988/MinifyAll.svg?style=social)](#languages-primarily-tested)
[![Github watchers](https://img.shields.io/github/watchers/Josee9988/MinifyAll.svg?style=social)](#languages-primarily-tested)
[![Github forks](https://img.shields.io/github/forks/Josee9988/MinifyAll.svg?style=social)](#languages-primarily-tested)

[Check my theme](https://marketplace.visualstudio.com/items?itemName=josee9988.black-garnet-theme)

---

*Made with a lot of ❤️❤️ by **[@Josee9988](https://github.com/Josee9988)***
