# vscode-md-preview-light

Light theme CSS for VS Code / Cursor markdown preview. Forces light mode even when using a dark editor theme.

## Usage

Add to your VS Code/Cursor `settings.json`:

```json
"markdown.styles": [
  "https://cdn.jsdelivr.net/gh/yoonholee/vscode-md-preview-light@main/style.css"
]
```

Note: `markdown.styles` only accepts https URLs or workspace-relative paths (not absolute local paths).

## Updating the CSS

```bash
# Clone
gh repo clone yoonholee/vscode-md-preview-light
cd vscode-md-preview-light

# Edit style.css, then push
git commit -am "Update"
git push

# Purge jsdelivr cache
curl https://purge.jsdelivr.net/gh/yoonholee/vscode-md-preview-light@main/style.css
```
