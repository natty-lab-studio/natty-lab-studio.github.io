# T-todo public site

This repository contains static pages served by GitHub Pages. Keep the root homepage and `app-ads.txt` at their existing paths.

| File | Public URL | Use |
|---|---|---|
| `dailytodo/index.html` | `https://natty-lab-studio.github.io/dailytodo/` | App homepage |
| `dailytodo/privacy.html` | `https://natty-lab-studio.github.io/dailytodo/privacy.html` | Privacy Policy, including `#delete` |
| `dailytodo/terms.html` | `https://natty-lab-studio.github.io/dailytodo/terms.html` | Terms of Service |
| `dailytodo/delete-data.html` | `https://natty-lab-studio.github.io/dailytodo/delete-data.html` | Existing app URL for deletion guidance |
| `dailytodo/config/ads.json` | `https://natty-lab-studio.github.io/dailytodo/config/ads.json` | Remote ad setting |

Policy pages provide full English and Korean text. Keep the existing URLs, language anchors and deletion links working when editing. Review the text and effective date before publishing policy changes. Check the live URLs after deployment because GitHub Pages may take time to update.

Legacy `/privacy/` and `/terms/` URLs use static HTML refresh redirects to the corresponding `/dailytodo/` policy pages, with direct links as a fallback.

## macOS release checklist

1. Attach `T-todo.dmg` to a public release in this repository.
2. Use the `releases/latest/download/` URL in both buttons while this repository's latest release is reserved for T-todo. If this repository also releases other products, use the T-todo DMG's versioned asset URL in both buttons and update both URLs for each new T-todo release.
3. Open the chosen URL in a signed-out browser and confirm it downloads `T-todo.dmg`.
