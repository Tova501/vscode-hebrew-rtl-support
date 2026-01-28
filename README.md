# Hebrew RTL Support for VS Code

Custom CSS for VS Code to display Hebrew text in RTL (Right-to-Left) direction, especially useful for IDE chats and integrated terminals.

## Installation Instructions

### Step 1: Install the Extension
1. Open VS Code
2. Go to Extensions (`Ctrl+Shift+X`)
3. Search for **"Custom CSS and JS"** (by Be5invis)
4. Click **Install**

### Step 2: Configure Settings
1. Open Settings JSON: `Ctrl+Shift+P` → "Preferences: Open Settings (JSON)"
2. Add this configuration:

```json
"vscode_custom_css.imports": [
  "file:///c:/url_to_your_file"
]
```

3. Save the settings file

### Step 3: Enable Custom CSS
1. **Close VS Code completely**
2. **Restart VS Code as Administrator** (right-click shortcut → "Run as administrator")
3. Run command: `Ctrl+Shift+P` → "Enable Custom CSS and JS"
4. Restart VS Code again

### Step 4: Reload (if needed)
- If you need to reload: `Ctrl+Shift+P` → "Reload Custom CSS and JS"
- Every time you update the CSS file, run this command

## Features

- ✅ RTL (Right-to-Left) text direction for Hebrew
- ✅ Proper text alignment for Hebrew content
- ✅ Support for Copilot Chat and IDE chats
- ✅ Preserves LTR direction for code editor
- ✅ Supports Hebrew comments in code

## References

- Extension: https://marketplace.visualstudio.com/items?itemName=be5invis.vscode-custom-css
- File URL Format: https://en.wikipedia.org/wiki/File_URI_scheme
