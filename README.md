<div align="center">

<h1>📁 Files</h1>

<p>
  <img src="https://img.shields.io/github/repo-size/nulswa/files?style=for-the-badge&color=2ea043&labelColor=1a1a2e" alt="Repo Size">
  <img src="https://img.shields.io/github/last-commit/nulswa/files?style=for-the-badge&color=blueviolet&labelColor=1a1a2e" alt="Last Commit">
  <img src="https://img.shields.io/github/stars/nulswa/files?style=for-the-badge&color=ff69b4&labelColor=1a1a2e" alt="Stars">
</p>

<p><i>A multi-purpose collection of utilities, assets, and files for your projects.</i></p>

<hr style="border: 1px solid #30363d;">

</div>

> **💡 Note:** This repository is primarily dedicated to ***Kron***, a bot available on *WhatsApp*. However, anyone can use these files in different projects—not just for WhatsApp bots, but also for Telegram, Discord, or any other platform. 
> 
> **⚠️ Disclaimer:** This repository is not intended for large-scale development or usage. It might be deleted in the future if the owner decides so.

---

### 📂 `folders` / `categories`

<table width="100%">
  <tr>
    <td width="50%" align="center">
      <h3>📦 JSON</h3>
      <p>Contains multiple JSON files inside subfolders, organized in a specific order so you can easily understand which one to call.</p>
      <a href="#">
        <img src="https://img.shields.io/badge/Go_to_Folder-JSON-blue?style=for-the-badge&logo=json&logoColor=white" alt="JSON Folder">
      </a>
    </td>
    <td width="50%" align="center">
      <h3>🧩 Packs</h3>
      <p>Contains various files and JSONs, each organized accordingly so you can easily understand which one to call.</p>
      <a href="#">
        <img src="https://img.shields.io/badge/Go_to_Folder-Packs-blueviolet?style=for-the-badge&logo=files&logoColor=white" alt="Packs Folder">
      </a>
    </td>
  </tr>
  <tr>
    <td colspan="2" align="center">
      <h3>🖼️ Categories</h3>
      <p>A folder containing several subfolders with their own domain, organized internally. It includes images, GIFs, and other utilities.</p>
      <a href="#">
        <img src="https://img.shields.io/badge/Go_to_Folder-Categories-ff69b4?style=for-the-badge&logo=folder&logoColor=white" alt="Categories Folder">
      </a>
    </td>
  </tr>
</table>

---

### ⚙️ Usage & Installation

You can use these files in three different ways:

1. **Direct Download:** Just browse the repository and download the PNG, JPG, GIF, or JSON files you need.
2. **Fetch / Raw URL:** Use the raw GitHub URL to fetch the files directly in your code.
3. **NPM Import:** Install it directly in your project using the GitHub repository.

To install it via npm, run:

```bash
npm install github:nulswa/files
```

Or add it manually to your `package.json`:

```json
{
  "dependencies": {
    "@nw-files": "github:nulswa/files"
  }
}
```

Then, you can import and use it in your Node.js project:

```javascript
const nwFiles = require('@nw-files');

// Get the path to a specific image
const thumbPath = nwFiles.getPath('categories/thumb/your-image.png');

// Get the raw URL for fetching
const gifUrl = nwFiles.getRawUrl('categories/gif/your-gif.gif');
```

---

<div align="center">

<br>

<img src="https://kajabi-storefronts-production.kajabi-cdn.com/kajabi-storefronts-production/themes/284832/settings_images/rjzl0u12j1hd2dvdo1j6_File.png" width="150">

### ⭐ Support & Requests

If you use this repository, consider giving it a **star** ⭐! 

You can also request to add more useful content for your project or others by opening an [Issue](../../issues).

<hr style="border: 1px solid #30363d;">

<p><i>Made with 💜 for Kron & the community</i></p>

</div>
