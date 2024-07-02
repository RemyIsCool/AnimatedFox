# ✨ AnimatedFox ✨
A minimal Firefox theme with a hidden URL bar and satisfying animations.

https://github.com/RemyIsCool/AnimatedFox/assets/97812130/7c1ea741-5b01-4e7f-892f-2bad5ad54362

## 🖥️ Requirements
 - 🦊 An up-to-date version of Firefox or LibreWolf. Other Firefox derivatives might work but I haven't tested them.
 - 🔤 [JetBrains Mono](https://www.jetbrains.com/lp/mono/) installed on your system.
 - 🎨 [Firefox Color extension](https://addons.mozilla.org/en-CA/firefox/addon/firefox-color/) added to your browser. (Optional)

## ⬇️ Installation
1. ✅ Make sure you have everything listed in Requirements.
2. ⚙️ Enable `toolkit.legacyUserProfileCustomizations.stylesheets` in [about:config](about:config).
3. 📁 Go to about:support and copy the profile directory path.
4. ⌨️ Clone this repository into a directory called `chrome` inside the profile directory you just copied:
```bash
cd the/path/you/just/copied
git clone https://github.com/RemyIsCool/AnimatedFox chrome
```
7. 📑 Hide the bookmarks toolbar by pressing Ctrl+Shift+B or right clicking and selecting "Never Show."
8. ❌ Right click the toolbar and select "Customize Toolbar." Remove everything except the back, forwards, reload, downloads, and unified extentions buttons.
10. 📎 Click [this link](https://color.firefox.com/?theme=XQAAAAJvAQAAAAAAAABBKYhm849SCia6aSqEGccwS-xMDPr79BBHlbukoJ1XpIq5hjxKu7S0U9lCpfLby_MuT9uV4fsIlHDN4w0iPOF2qkutG6LdQPflhViMuNpfMCNFmKDH2Qhyehu6MLzXNQVs0GY1r7ovoIKuXhztaOFq4FJioxA6R9vRCSJuYTYjMcrT3wBcJ_XdWHORl4vB5EsBIyfUdxh6pWun2gm3c5dZSWxgRjZgQNbYla1JkPdZXrRZJu4Yn_cR-hQmKENt0sT5rV-8_-VWOmA
) to install the Firefox Color theme. (Optional)
11. 🔄 Restart your browser for the theme to be applied.

If you would like your tabs to be centered, set the option `animatedFox.centeredTabs` to true in about:config.

## 🔃 Updating
1. 📁 Go to about:support and copy the profile directory path.
2. ⌨️ Run `git pull` in the `chrome` folder:
```bash
cd the/path/you/just/copied/chrome
git pull
```
3. 🎨 Re-install the Firefox Color theme if you installed it.

## 👾 Known Issues
 - Moving around tabs is very buggy. You should instead use the keyboard shortcuts ctrl+shift+page up/down.
 - Customizing the toolbar doesn't work with the theme applied.
 - Color themes with transparency usually don't work well.

If anyone knows how to fix these issues, feel free to submit a pull request.

---
For the new tab page, see https://github.com/RemyIsCool/New-Tab-Page.
