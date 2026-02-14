# 🚀 FastAPI Hello World API

A simple **Hello World API** built using FastAPI.
This project demonstrates basic route creation and API setup for beginners learning backend development with Python.

---

## 📌 Features

* FastAPI framework
* Simple GET endpoints
* Beginner-friendly structure
* Ready for extension into larger APIs

---

## 📂 Project Structure

```
fastapi-hello-api/
│
├── main.py            # FastAPI application
├── requirements.txt  # Project dependencies
└── .gitignore        # Ignored files/folders
```

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the repository

```bash
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
```

---

### 2️⃣ Create virtual environment (optional but recommended)

```bash
python -m venv myenv
source myenv/bin/activate     # Mac/Linux
myenv\Scripts\activate        # Windows
```

---

### 3️⃣ Install dependencies

```bash
pip install -r requirements.txt
```

---

## ▶️ Run the API

```bash
uvicorn main:app --reload
```

Server will start at:

```
http://127.0.0.1:8000
```

---

## 📖 API Endpoints

### 🔹 Home Route

**GET /**

Response:

```json
{
  "message": "Hello World"
}
```

---

### 🔹 About Route

**GET /about**

Response:

```json
{
  "message": "CampusX is an education platform where you can learn AI"
}
```

---

## 🧪 Interactive API Docs

FastAPI provides built-in Swagger UI:

```
http://127.0.0.1:8000/docs
```

---

## 🛠️ Tech Stack

* Python
* FastAPI
* Uvicorn

---

## 📌 Future Improvements

* Add POST endpoints
* Add database integration
* Implement authentication
* Deploy to cloud

---

## 👨‍💻 Author

**Vaibhav Singh**

---

⭐ If you found this helpful, consider starring the repo!
