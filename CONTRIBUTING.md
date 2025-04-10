# Contributing to Lumon

_Thanks for your interest in contributing! Before you dive in, check out the [VS Code Theme Color Reference](https://code.visualstudio.com/docs/getstarted/theme-color-reference) — it’s super helpful for understanding how theming works._

## 🚀 Quick Start

1. **Fork this repository** on GitHub.
2. **Clone your fork** locally and navigate into the project folder:
   ```bash
   git clone https://github.com/YOUR_USERNAME/lumon.git
   cd lumon
   ```
3. **Install dependencies:**
   ```bash
   npm install
   ```
4. **Package the theme:**
   ```bash
   vsce package
   ```
   This creates a `.vsix` file you can use to install the theme locally.

5. **Open the project in VSCode or Cursor.**

6. Open the Command Palette with <kbd>Cmd/Ctrl+Shift+P</kbd> and run:
   ```
   Extensions: Install from VSIX...
   ```

7. Select the `.vsix` file you just created.

8. **Activate your theme** via the **Color Theme** picker in Command Palette.

9. Make changes in `themes/Lumon-color-theme.json`.

10. To test in a fresh window, go to the Debug panel (`View > Run`), select **Launch Extension**, and click the green play button ▶️. A new VSCode window will open with your theme loaded.

11. After making changes, press the **🔄 refresh button** in the original window to reload the extension in the test window.

12. Once your changes look great, **commit** them and push to your fork.

13. Submit a **Pull Request** with a clear description of what you changed and why.

---

## 🌱 Ideas for Contributions

- [ ] Add new syntax token support for other languages
- [ ] Tweak contrast for better accessibility (e.g. high contrast variant)
- [ ] Suggest layout or spacing improvements for readability
- [ ] Help maintain Cursor-specific compatibility
- [ ] Refactor or clean up unused token definitions

---

## 🤝 Need Help?

Got stuck or have a question? Feel free to open an issue or reach out on [𝕏](https://x.com/conner_luzier) — happy to help!
