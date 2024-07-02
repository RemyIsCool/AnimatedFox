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
9. 📎 Click [this link](https://color.firefox.com/?theme=XQAAAAKGAQAAAAAAAABBKYhm849SCia73laEGccwS-xMDPr5iE6wEt17lnFu4uAqMsdEr66zA4hyQFpjnIdIqexC6jk0ujxh3YezY5q8Yibz3vKnXSdVRwFGs8MGkNcRmXXkVBYSSb5AZytOH-ZH-2fJHXOM2cMauhgxI-owK6hf70XV6B-CNgSQ8ezEFHnV3IYDQizRHgzyz4-QTV3e2qMGHFZQ86mhpKNfHjKK6Ay7Rw6VO4ffFxgcOJhEOGZegOZPzluYPS3grJZyeCZz6Y1js48jUOlOXyXnJ9VOUhG__2C1sgA) to install the Firefox Color theme. (Optional)
10. 🔄 Restart your browser for the theme to be applied.

If you would like your tabs to be centered, set the option `animatedFox.centeredTabs` to true in about:config.

If you want to use this theme with the [Adaptive Tab Bar Colour](https://github.com/easonwong-de/Adaptive-Tab-Bar-Colour) extension instead of Firefox Color, set the option `animatedFox.adaptiveTabBarColourSupport` to true in about:config.

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
 - Items to the right of the search bar overlap when the window is too narrow.
 - Customizing the toolbar doesn't work with the theme applied.

---
For the new tab page, see https://github.com/RemyIsCool/New-Tab-Page.
