<h1 align="center">🌐 Python Web Server</h1>

<p align="center">
  A simple web server built from scratch in Python to understand how HTTP, sockets, and backend systems work internally.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Language-Python-blue?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Concept-HTTP-orange?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Networking-Sockets-green?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Purpose-Learning-lightgrey?style=for-the-badge" />
</p>

---

## 📌 Overview

This project is a **custom-built web server** developed in Python to explore:

- How HTTP requests & responses work  
- How sockets handle client-server communication  
- How static content is served from a backend  

It focuses on **learning core backend fundamentals**, not replacing production-grade servers.

---

## ✨ Features

- 🔌 Socket-based client-server communication  
- 🌐 Custom HTTP request & response handling  
- 📄 Static file serving (HTML, images, etc.)  
- ❌ Error handling (404 Not Found)  
- 🧩 Modular architecture with separate handlers  
- ⚡ Lightweight and dependency-free  

---

## 🏗️ Architecture

```

Client → Socket Handler → HTTP Handler → File Handler → Response

```id="arch1"

---

## 📂 Project Structure

```

server/
├── modules/
│   ├── http_handler/     # Handles HTTP parsing & response
│   ├── socket_handler/   # Manages connections
│   └── file_handler/     # Serves static files
├── src/                  # Static web content
│   ├── index.html
│   ├── about.html
│   ├── projects.html
│   └── 404.html
└── webserver.py          # Main server entry point

````id="struct1"

---

## 🚀 Usage

### ▶️ Run the Server

```bash id="run1"
python3 server/webserver.py
````

---

### 🌐 Access in Browser

```id="url1"
http://localhost:8080
```

---

## 🔍 Supported Features

* ✅ Handles basic **GET requests**
* ✅ Serves static HTML pages
* ✅ Returns **404 error page** for missing files
* ❌ No POST/advanced routing (intentionally minimal for learning)

---

## 🎯 Learning Outcomes

This project helped in understanding:

* Low-level networking using sockets
* HTTP protocol basics
* Request parsing and response building
* File handling in backend systems
* Modular backend architecture design

---

## ⚠️ Limitations

* Supports only basic HTTP methods (GET)
* Not optimized for production use
* No concurrency handling (single-threaded)

---

## 💡 Why This Project?

Instead of using frameworks, this project focuses on:

> “Understanding how things work under the hood”

It builds a strong foundation for:

* Backend development
* Networking concepts
* Server architecture

---

## 📜 License

MIT License © PevinKumar A

---

## 💬 Final Note

This project was built as part of my backend learning journey.

If you're exploring low-level systems or web servers, this is a great place to start 🚀
