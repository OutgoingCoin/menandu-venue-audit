# 🍔 Me&U Menu Audit Chrome Extension

A powerful Chrome extension designed to audit **Me&U menus** across multiple venues — perfect for consultants, operators, and QA teams.

---

## ✨ Features

- ✅ Automatically checks for:
  - Missing upsell groups
  - Daily specials
  - Price overrides
  - "Popular" tags per category (max 3 recommended)
  - Marketing opt-in toggle
  - Tipping enabled
  - Table booking settings
  - Table group presence
  - Feedback toggle
  - Batching group configuration

- 🔁 Remembers the last audit and re-displays the results on re-open.
- 🧠 Detects URL changes and re-runs the audit on new pages.
- 🧹 Includes a manual "Force Re-Audit" button.
- 📊 Prints an audit summary to the browser console.
- 🍔 Uses a hamburger icon for the toolbar UI.

---

## 🚀 Installation (Unpacked)

1. Download this repository.
2. Go to `chrome://extensions/` in your browser.
3. Enable **Developer mode** (top right).
4. Click **Load Unpacked**.
5. Select the folder containing the extension (e.g., `meandu-menu-audit-v1.2`).

---

## 🛠 How to Use

1. Navigate to a Me&U venue menu page.
2. Click the **🍔 Me&U Audit** toolbar icon.
3. Wait for the audit to complete — results will show in the console.
4. To re-run the audit, click the **Force Re-Audit** button in the popup.

> 💡 Use the browser **Console (F12)** to view detailed results.

---

## 📦 Packaging Format

ZIP archives follow the versioning pattern:  
`meandu-menu-audit-v1.x.zip`

---

## 🧑‍💻 Developer Notes

- Built to support **multiple venues**, not hardcoded to any specific one.
- DOM selectors are flexible and resilient to UI variations.
- Outputs categorized results: ✅ Passed, ⚠️ Warnings, ❌ Failed.

---

## 📄 License

MIT — use, modify, and share freely!

---

