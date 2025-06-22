# 🌐 MetaML: Intelligent JSON Page Structure Generator

🔗 **Live Demo**: [Click to Try Now](https://famous-alfajores-a0c7cd.netlify.app/)

## 💡 Overview

MetaML is a powerful web-based tool that intelligently converts web page structures into structured JSON using smart parsing techniques and component-based logic. This helps front-end developers, low-code builders, and auto-layout engines to convert raw HTML into a reusable structured format.

Built for the **CSI Anvesis 2025 Hackathon** under Problem Statement PS5: *"MetaML: Intelligent JSON Page Structure Generator."*

---

## 🚀 Features

- 🧠 Intelligent parsing of semantic HTML → JSON
- 🧾 Real-time JSON output with component hierarchy
- 🧩 Modular interface (Input / Output / Preview / Stats Panels)
- 📦 Clean folder structure and scalable TypeScript logic
- 💡 Pluggable ML logic for future improvements
- 🌐 Fully responsive deployed web app on Netlify

---

## 🛠️ Tech Stack

| Layer       | Tech Used                     |
|-------------|-------------------------------|
| Frontend    | React + TypeScript + Vite     |
| Styling     | Tailwind CSS                  |
| Logic Layer | Custom ML/Parsing logic in TS |
| Tooling     | ESLint, PostCSS               |
| Deployment  | Netlify                       |

---

## 📁 Folder Structure

```
MetaML-JSON-Generator/
│
├── index.html
├── package.json
├── tailwind.config.js
├── vite.config.ts
│
└── src/
    ├── App.tsx
    ├── main.tsx
    ├── index.css
    │
    ├── components/
    │   ├── Header.tsx
    │   ├── InputPanel.tsx
    │   ├── OutputPanel.tsx
    │   ├── PreviewPanel.tsx
    │   └── StatsPanel.tsx
    │
    ├── services/
    │   └── mlService.ts
    │
    └── types/
        └── index.ts
```

---

## 🧪 How to Run Locally

```bash
# 1. Clone the repo
git clone https://github.com/YOUR-USERNAME/metaML-json-generator.git
cd metaML-json-generator

# 2. Install dependencies
npm install

# 3. Run dev server
npm run dev
```

---

## 🚀 Deployment on Netlify

The application was deployed using [**Netlify**](https://www.netlify.com/) for easy one-click continuous deployment.

### ✅ Steps Followed:

1. **Built the app** using:
```bash
npm run build
```

2. **Created a Netlify account** and connected it with GitHub.

3. **Selected the repository**, set the **build command** as:
```
npm run build
```
and **publish directory** as:
```
dist
```

4. Netlify automatically deployed the site at:  
🔗 [`https://famous-alfajores-a0c7cd.netlify.app/`](https://famous-alfajores-a0c7cd.netlify.app/)

---

## 🔮 Future Scope

- 🧠 Integrate ML/NLP backend to auto-detect layout & components
- 🧾 Accept file-based HTML input and process it
- 🔄 JSON → UI reverse builder mode
- 🔗 Export schema to low-code/no-code tools
- 📊 Add drag-and-drop visual JSON editor

---



---

## 🛡️ License

Licensed under the MIT License.



