# OSTAD0000BIT# 🚀 Prompt Database App

A powerful, full-featured application for managing, analyzing, and searching AI prompts — optimized for performance, accessibility, and offline use.

## ✨ Features

- 🧠 **Prompt Management**: Create, edit, delete, and organize prompts
- 🔍 **Advanced Fuzzy Search** with filters by category, subcategory, date range, and keyword
- 📊 **Interactive Analytics**: Donut charts, time-based trends, and drill-down views using Chart.js
- 💾 **Offline Storage**: Persist data using IndexedDB (`idb`), with localStorage fallback
- 🗃 **Bulk Actions**: Multi-select prompts to delete or reassign in batch
- 🔄 **Import/Export**: JSON-based prompt import/export (CSV optional)
- 🌙 **Dark Mode**: Fully responsive layout with theme switching
- ♿ **Accessibility**: WCAG 2.1 AA compliant — full keyboard navigation, ARIA, and semantic HTML
- 🛡 **Security**: Input sanitization, XSS protection, data validation
- 🧪 **Testing**: High coverage with Jest, React Testing Library, and Cypress
- ⚙️ **CI/CD**: Auto-deploy via Vercel or Netlify with full lint/test/build pipelines

---

## 📦 Tech Stack

- React (with Hooks)
- Redux Toolkit
- TypeScript
- IndexedDB via `idb`
- Chart.js
- React Router
- CSS Modules
- Framer Motion (animations)
- Axios (for API integration)
- Jest + Cypress (testing)

---

## 📁 Folder Structure

```bash
├── src/
│   ├── components/
│   ├── features/         # Redux slices
│   ├── db/               # IndexedDB wrapper
│   ├── utils/            # Fuzzy search, validation
│   └── styles/           # CSS Modules
├── public/
├── tests/
└── build/
