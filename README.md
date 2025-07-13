
# 🌐 AutoBill Frontend

This is the frontend application for the **AutoBill** system, built with **React** and **Vite**. It serves as the user interface for interacting with the backend APIs to perform automated billing tasks, such as uploading receipts and viewing extracted invoice data.

## ✅ Live Demo

You can access the live version of the app here:

🔗 **[AutoBill Frontend Live App](https://autobill-frontend07.onrender.com/)**

Make sure the backend API is up and accessible for full functionality.

## 📂 Project Structure

```
autobill-frontend/
├── public/
├── src/
│   ├── assets/
│   ├── components/
│   ├── data/
│   ├── styles/
│   ├── App.jsx
│   ├── index.jsx
│   ├── main.jsx
│   └── SocketConnection.jsx
├── .env
├── .gitignore
├── index.html
├── package.json
├── vite.config.js
└── README.md
```

## 🧰 Features

- ⚡️ Blazing-fast development with Vite  
- ⚛️ Built with React  
- 💅 Styled using modern CSS (CSS Modules / plain CSS)  
- 📦 Axios for API communication  
- 🔁 Modular and reusable components  

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/<your-username>/autobill-frontend.git
cd autobill-frontend
```

### 2. Install dependencies

```bash
npm install
```

### 3. Configure environment variables

Create a `.env` file with the following (example):

```
VITE_API_URL=https://krrishcoder07-autofill-backend.hf.space
```

### 4. Run the development server

```bash
npm run dev
```

> The app will be available at `http://localhost:5173`

## ⚙️ Build for Production

```bash
npm run build
```

> Output will be in the `dist/` folder (used as the **publish directory** on Render)

## 🐳 Docker (Optional)

### Build and run with Docker:

```bash
docker build -t autobill-frontend .
docker run -d -p 5173:80 autobill-frontend
```

> Requires a Dockerfile and static server (e.g., Nginx or `serve`)

## 🔗 Connect to Backend

Ensure your backend API is running and the `VITE_API_URL` is correctly set in your `.env`.

## 🛠 Tech Stack

- **React** – UI library  
- **Vite** – Frontend tooling  
- **Axios** – API calls  
- **JavaScript (ES6+)**  
- **CSS Modules / Vanilla CSS**  

## 📌 Future Enhancements

- [ ] Authentication integration  
- [ ] Dashboard analytics  
- [ ] Improved error handling and UX  

## 🤝 Contributing

Contributions are welcome!

1. Fork the repository  
2. Create a new branch (`git checkout -b feature/your-feature`)  
3. Commit your changes (`git commit -m 'Add feature'`)  
4. Push to the branch (`git push origin feature/your-feature`)  
5. Open a pull request  

## 📝 License

This project is licensed under the MIT License.


---

<p align="center">
  Made with ❤️  <a href="https://github.com/krrishcoder07" target="_blank"></a>
</p>

<p align="center">
  <a href="https://github.com/krrishcoder07/autobill-frontend" target="_blank">
    <img src="https://img.shields.io/badge/View%20on-GitHub-24292e?logo=github" alt="View on GitHub" />
  </a>
</p>
