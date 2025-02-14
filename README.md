# Gif Expert App

## 🖼️ Description
Gif Expert App is a web application built with **React** and **Vite**, enabling users to search and display animated GIFs using the **Giphy API**.

---

## 🚀 Installation
### 1️⃣ Clone the Repository
```bash
git clone https://github.com/aclement/gif-generator-app.git
cd gif-expert-app
```

### 2️⃣ Create the `.env` File
Copy the `.env.template` file and rename it to `.env`:
```bash
cp .env.template .env
```
Fill the `.env` file with your **Giphy API key**:
```env
VITE_GIPHY_API_KEY=your_api_key_here
```

### 3️⃣ Install Dependencies
```bash
npm install
```

### 4️⃣ Start the Development Server
```bash
npm run dev
```
Access the app at `http://localhost:5173`

---

## 🛠️ Environment Variables
- `.env.template`: Template for environment variables.
- `.env`: Actual environment file (excluded from version control).

### `.env.template` Example:
```env
VITE_GIPHY_API_KEY=your_api_key_here
```

---

## 🗂️ Project Structure
```
📂 src
 ┣ 📂 components
 ┃ ┣ 📜 AddCategory.jsx
 ┃ ┣ 📜 GifGrid.jsx
 ┃ ┗ 📜 GifItem.jsx
 ┣ 📂 helpers
 ┃ ┗ 📜 getGifs.js
 ┣ 📂 hooks
 ┃ ┗ 📜 useFetchGifs.js
 ┣ 📜 GifExpertApp.jsx
 ┣ 📜 main.jsx
```

---

## ✨ Features
✅ Search for GIFs using the Giphy API  
✅ Display results dynamically  
✅ Add multiple search categories  
✅ Use custom hooks for efficient state management  

---

## 💻 Technologies Used
- 🟦 **React 18**
- ⚡ **Vite**
- 🌐 **Giphy API**
- 💅 **CSS**
<!-- - 🧪 **Jest** (for testing) -->

---

## 🤝 Contributing
Contributions are welcome! 😊  
1. Fork the repository 🍴  
2. Create a new branch: `git checkout -b feature/new-feature`  
3. Make your changes and commit: `git commit -m 'Add new feature'`  
4. Push to the branch: `git push origin feature/new-feature`  
5. Open a Pull Request 🚀


