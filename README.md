# **MinifyAll a extension for VSCode**

VSCode **minifier** for **JSON**, **JSONC**, **CSS**, **SCSS**, and **HTML**, you will love its simplicity!

You can minify the file and replace all the content with the new minified text, **or** you can preserve the original document and get the minified text in other document!

Not based in any minifier, made from scratch!

For more information check our: **[GitHub repository](https://github.com/Josee9988/MinifyAll)** and **[VisualStudio Marketplace](https://marketplace.visualstudio.com/items?itemName=josee9988.minifyall)**.

Want to help us improve the theme or you found a mistake?
**[Let us know](https://github.com/Josee9988/MinifyAll/issues)**.

Or contact **[me](jgracia9988@gmail.com)**.

Check our **[changelog](CHANGELOG.md)**.

How does it look? Look at our **[Screenshots](Screenshots/)**

---

<img src="https://i.imgur.com/mscnJe8.png" alt="logo" title="logo" style="border-radius:15px; box-shadow: 6px 6px  #282829; max-height: 500px; max-width:500px;margin-left: auto; margin-right:auto;display: block;margin-left: auto;margin-right:auto;width:45%;"/>

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

- **```Minify this document ⚡```**
- **```Minify this document and preserve the original ⛏```**

---

## **How does it looks with real code?** 📸 😁

- The two commands available. First directly minifies the actual document and replaces the original code with the modified one, the second keeps the original document and creates a file with the modified text:

<img src="https://i.imgur.com/wsqAcGS.png" alt="command" title="command" style="border-radius:15px; box-shadow: 6px 6px  #282829; max-height: 500px; max-width:500px;margin-left: auto; margin-right:auto;display: block;margin-left: auto;margin-right:auto;width:50%;"/>

- The output that you will find after you save your document:

<img src="https://i.imgur.com/vRF9IUQ.png" alt="output" title="output" style="border-radius:15px; box-shadow: 6px 6px  #282829; max-height: 500px; max-width:500px;margin-left: auto; margin-right:auto;display: block;margin-left: auto;margin-right:auto;width:50%;"/>

- The first and default command that replaces the actual code with the minified one:

<img src="https://i.imgur.com/bbAhxJj.gif" alt="Preview" title="preview" style="border-radius:15px; box-shadow: 6px 6px  #282829; max-height: 750px; max-width:750px;margin-left: auto; margin-right:auto;display: block;margin-left: auto;margin-right:auto;width:75%;"/>

- The second command that saves the minfied text to other file and preserves the original text:

<img src="https://i.imgur.com/RTyX0PZ.gif" alt="Preview2nd" title="preview2nd" style="border-radius:15px; box-shadow: 6px 6px  #282829; max-height: 750px; max-width:750px;margin-left: auto; margin-right:auto;display: block;margin-left: auto;margin-right:auto;width:75%;"/>

---

## **Languages available** 🧪🔥

- CSS
- SCSS
- HTML
- JSON
- JSONC

---

## **Examples**

From:

```css
.myClass {
    background-color: rgba(12, 12, 12, 0.8);
    background-color: rgb(12, 12, 12);
    background-color: #FAFAFA;
}
```

To:

```css
.myClass{background-color:#0C0C0CCC;background-color:#111;BACKGROUND-COLOR:#FFF}
```

- rgba is formatted to hexadecimal.
- rgb is formatted to 3 digit value hexadecimal.
- 6 digit hexadimal is formatted to 3 digit value hexadecimal
- There is no spaces
- There is only one line

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

- Save minified text to other file using json (second command in a json file) may cause some errors that may not be errors.

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

---

*Made with a lot of ❤️❤️ by **[@Josee9988](https://github.com/Josee9988)***
