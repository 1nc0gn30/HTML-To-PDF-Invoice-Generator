# HTML-To-PDF-Invoice-Generator

A project by Neal Frazier

## Overview
This repository is part of Neal Frazier project collection.

## Tech Stack
- Netlify (deployed)

## Project Structure
```
HTML-To-PDF-Invoice-Generator/
  - 
  (5 files total)
```

## Getting Started

### Usage
Open index.html in your browser or serve locally.
Use: npx serve .

## Original README
<details>
<summary>Click to expand original README</summary>

# 🧾 Invoice Generator (HTML + PDF Export)

Create beautiful, branded invoices directly in your browser and export them as PDFs — no frameworks, no backend, no dependencies beyond a single script.

**Live Demo →** [https://invoice-generator-html-to-pdf.netlify.app](https://invoice-generator-html-to-pdf.netlify.app)

---

## 📦 Features

- ✅ Fully editable invoice fields (contenteditable + textarea)
- ✅ Upload and embed your logo
- ✅ Itemized entries with auto total calculation
- ✅ One-click PDF download with exact layout
- ✅ Optimized for print (8.5 x 11in PDF)
- ✅ 100% offline / client-side
- ✅ Responsive layout
- ✅ SEO & accessibility friendly
- ✅ No frameworks or build tools

---

## 🚀 Getting Started

### 🔗 Deploy on Netlify

> If you're using [Netlify](https://netlify.com):

1. Fork this repo or upload `index.html` to a GitHub repo.
2. Go to Netlify → **"Add New Site"** → **"Import from GitHub"**.
3. Set:
   - **Build command**: *(leave blank)*
   - **Publish directory**: `.`
4. Deploy and go live 🎉

### 🖥 Local Preview

Just open `index.html` in your browser.

No dependencies. No CLI. No nonsense.

---

## 🧠 How It Works

- Built in pure **HTML**, **CSS**, and a little **JavaScript**
- Uses [html2pdf.js](https://github.com/eKoopmans/html2pdf) to generate PDF from the DOM
- Auto-calculates totals as you type
- Keeps logo embedded in the PDF (via Base64)

---

## 📁 File Structure

#### invoice-generator/
#### ├── index.html # Main app
#### ├── .gitignore # Clean deploys
#### └── README.md # You're here


---

## ✍️ Customization Ideas

- Add invoice numbers & due dates
- Add tax/discount fields
- Auto-save to localStorage
- Export/import invoices as JSON
- Add authentication (Firebase/Auth0)
- Multi-page PDF support

---

## 🧾 Example Use Cases

- Freelancers & contractors
- Small businesses
- Digital product vendors
- Offline-first invoice archiving

---

## 🧑‍💻 Author

Built by [Neal Frazier](https://nealfrazier.tech)  
GitHub: [@1nc0gn30](https://github.com/1nc0gn30)  
Twitter: [@inc0gn30](https://twitter.com/inc0gn30)

---

## 📄 License

MIT — free for personal and commercial use.

> Drop a star ⭐ if you find this useful or fork to customize it for your team or business!

</details>

## TODO / Roadmap
- [ ] Add unit tests
- [ ] Add LICENSE file
- [ ] Add CI/CD pipeline
- [ ] Add contribution guidelines (CONTRIBUTING.md)
- [ ] Improve error handling and edge cases
- [ ] Add environment variable documentation
- [ ] Add code comments and inline documentation

## Deployment
This project is deployed on Netlify. See netlify.toml for configuration.

## Author
**Neal Frazier** - [@AshAmplifies](https://github.com/1nc0gn30)

## Links
- GitHub: https://github.com/1nc0gn30/HTML-To-PDF-Invoice-Generator

---
*This README was enhanced as part of the neals-projects-2026 batch update.*
