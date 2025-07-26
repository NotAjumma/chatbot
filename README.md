# 🇲🇾 RISDA FAQ Search Assistant

This is a lightweight, bilingual (Bahasa Melayu & English) FAQ suggestion tool for helping users quickly find information about RISDA (Rubber Industry Smallholders Development Authority). It provides fuzzy search functionality and instant suggestions while typing.

Built using [Fuse.js](https://fusejs.io), a powerful open-source fuzzy search library — no AI, no backend needed, and no cost to use.

---

## ✨ Features

✅ **Real-Time Search**  
Suggestions appear as the user types, even if the input has spelling errors or short forms.

✅ **Bilingual Support (BM & EN)**  
Supports both Bahasa Melayu and English questions and answers.

✅ **Excludes Unwanted Entries**  
Custom logic can exclude certain items (e.g., “Apa RISDA?”) from showing in the dropdown.

✅ **Dropdown Display Above Input**  
By default, the suggestions dropdown appears **above** the input field, which is ideal for bottom-aligned chat inputs.

✅ **Minimal & Fast**  
Uses a single JavaScript file with no external dependencies beyond Fuse.js.

---

## 📦 Requirements

- No build tools or frameworks needed.
- Just include one external script:
```html
<script src="https://cdn.jsdelivr.net/npm/fuse.js@6.6.2"></script>
