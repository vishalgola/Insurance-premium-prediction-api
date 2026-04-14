# 🚀 Insurance Premium Prediction API & Web App



---

## 🌐 Live Demo

* 🔗 **Frontend (Streamlit UI):** https://insurance-premium-prediction-api-ui.onrender.com
* 🔗 **Backend API Docs:** https://insurance-premium-prediction-api-gywc.onrender.com/docs

---

## 🖼️ Project Preview

> Add a screenshot of your homepage UI below

<img width="789" height="443" alt="image" src="https://github.com/user-attachments/assets/337a2764-4a53-4c69-b0a0-a191ec592f97" />


---

## ⚙️ Tech Stack

* **Backend:** FastAPI
* **Frontend:** Streamlit
* **Machine Learning:** Scikit-learn
* **Containerization:** Docker
* **Deployment:** Render
* **Language:** Python

---

## 🧠 Features

* Predict insurance premium category based on user inputs
* Clean and interactive UI using Streamlit
* Fast and efficient API using FastAPI
* Dockerized for easy deployment
* Scalable architecture (separate frontend & backend)

---

## 📂 Project Structure

```
insurance-premium-prediction/
│── backend/
│   ├── app.py
│   ├── model/
│   │   ├── model.pkl
│   │   └── predict.py
│   ├── schema/
│   ├── config/
│   ├── Dockerfile
│   └── requirements.txt
│
│── frontend/
│   └── UI.py
│
│── .gitignore
│── README.md
```

---

## 🚀 How to Run Locally

### 1️⃣ Clone the repository

```
git clone https://github.com/vishalgola/Insurance-premium-prediction-api.git

```

### 2️⃣ Run Backend (FastAPI)

```
cd backend
pip install -r requirements.txt
uvicorn app:app --reload
```

### 3️⃣ Run Frontend (Streamlit)

```
cd frontend
pip install streamlit requests
streamlit run UI.py
```

---

## 🐳 Docker Setup (Backend)

### Build Image

```
docker build -t insurance-api .
```

### Run Container

```
docker run -p 10000:10000 insurance-api
```

---

## 📡 API Endpoint

### POST `/predict`

**Request Body Example:**

```json
{
  "age": 30,
  "income": 50000
}
```

**Response Example:**

```json
{
  "premium_category": "Medium"
}
```

---

## 📌 Deployment

* Backend deployed using **Docker on Render**
* Frontend deployed separately using **Streamlit on Render**
* Fully functional end-to-end system

---

## 🎯 Future Improvements

* Add authentication system
* Improve UI/UX
* Add more features & model optimization
* Store predictions in database

---

## 🤝 Contributing

Feel free to fork this repo and improve it!

---

## 📬 Contact

If you have any questions or suggestions, feel free to reach out.

---

⭐ If you like this project, don’t forget to star the repo!
