# Employee Form with Navigation and Control Buttons

## 📝 Description
This is a responsive web-based Employee Form application built using **HTML**, **CSS**, **Bootstrap**, and **JavaScript**. It uses **JsonPowerDB (JPDB)** as the backend to store and manage employee data records. The application allows users to:

- Add new employee details
- Save and persist records using JsonPowerDB
- Edit and update existing employee records
- Navigate records using First, Previous, Next, and Last buttons

---

## ⚡ Performance of JsonPowerDB
**JsonPowerDB** (JPDB) provides:
- Fast CRUD operations with minimal configuration
- Secure and lightweight NoSQL-style database
- Built-in support for primary keys and indexed queries
- High performance in single-page applications due to JSON-native responses

During this project, JPDB performed reliably with fast data fetch and update responses.

---

## 🧰 Ease of Use: jpdb-commons.js
The `jpdb-commons.js` library simplifies integration with JsonPowerDB by:
- Providing prebuilt request creator functions like `createPUTRequest()`, `createGET_BY_KEYRequest()`, etc.
- Handling AJAX requests and responses behind the scenes
- Managing asynchronous calls with jQuery

This enabled quicker development with clean and modular JavaScript code.

---

## 📷 Screenshots

![Screenshot 2025-06-20 200454](https://github.com/user-attachments/assets/b7d51f88-3765-4137-8511-e00ac139b664)

---


## 📦 Release History

### v1.1 - June 21, 2025
- 🚀 Added support for editing and updating employee records
- ✅ Improved navigation button state (disable on first/last record)
- 🎨 Background image and UI polish
- 🐞 Bug fixes for async parsing and error handling

### v1.0 - June 20, 2025
- 🌟 Initial release of Employee Form using JsonPowerDB
- ✅ Features: Add, Save, Navigation (First, Prev, Next, Last)

---


## 👩‍💻 Author
**Ishita Pathunda**
- [GitHub Profile](https://github.com/Ishitapathunda)

---

## 📄 License
This project is licensed under the MIT License.

---

## 🚀 How to Run and Install

### 📁 1. Clone the Repository
```bash
git clone https://github.com/Ishitapathunda/Employee-Form-with-Navigation-and-Control-Buttons.git
cd Employee-Form-with-Navigation-and-Control-Buttons
```

### 🌐 2. Open in Browser
You can simply open `index.html` in your browser:
- Double-click `index.html`
- Or use Live Server in VS Code


### ⚠️ Notes:
- Ensure the site is served over **HTTP** (not HTTPS), or use a CORS proxy if deploying publicly.
- Avoid sensitive data in code. Treat your JPDB token securely.

