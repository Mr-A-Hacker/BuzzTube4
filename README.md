# 🎬 BuzzTube4  
A lightweight, container‑ready HTML video player designed for simple deployments using Docker.

BuzzTube4 is a minimal project that serves a clean `index.html` page through a Docker container.  
It’s perfect for quick demos, testing environments, or embedding a simple video player inside a containerized setup.

---

## 📁 Project Structure
```
BuzzTube4/
│
├── index.html      # Main webpage (video player or UI)
└── Dockerfile      # Container build instructions
```

---

## 🚀 Features
- **Simple static HTML interface**
- **Dockerized for easy deployment**
- **Fast, lightweight, and portable**
- **Zero dependencies — pure HTML + Docker**

---

## 🐳 Running with Docker

### 1. Build the image
```bash
docker build -t buzztube4 .
```

### 2. Run the container
```bash
docker run -p 8080:80 buzztube4
```

### 3. Open in your browser
```
http://localhost:8080
```

---

## 🧱 Dockerfile Overview
The included Dockerfile:

- Uses a lightweight base image  
- Copies `index.html` into the container  
- Serves it through a minimal web server  

This makes the project extremely easy to deploy on any Docker‑compatible platform.

---

## 🌐 Use Cases
- Hosting a simple video player  
- Embedding a static webpage inside a container  
- Quick demos or prototypes  
- Lightweight front‑end testing  
- Local or LAN‑only media tools  

---

## 📌 Future Improvements
Potential upgrades you can add:

- Custom CSS styling  
- JavaScript controls  
- Playlist support  
- Dark mode  
- Mobile‑friendly UI  
- Volume + playback controls  

---

## 🤝 Contributing
Pull requests are welcome!  
Feel free to improve the UI, add features, or enhance the Docker setup.

---

## ⭐ Support the Project
If you like this project, consider starring the repo — it helps a lot!
