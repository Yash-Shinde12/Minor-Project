# GPU Monitoring & User Management Dashboard

A Flask-based web dashboard for monitoring GPU and CPU stats, managing users, and analyzing GPU usage from CSV files.

---

## 🚀 Features

- **Live GPU & CPU Monitoring** (Linux)
- **User Management** (create, delete, list, search, inactive users)
- **CSV Analysis**: Upload and visualize GPU usage data
- **Downloadable Reports** (charts, inactive users)
- **Modern, Responsive UI** with loading indicators and interactive charts

---

## 🛠️ Setup Instructions

### 1. **Clone the Repository**
```bash
git clone <your-repo-url>
cd <your-repo-directory>
```

### 2. **Install Dependencies**
```bash
pip install -r requirements.txt
```

### 3. **Run the App**
```bash
python app.py
```
- The app will be available at [http://localhost:5000](http://localhost:5000)

### 4. **Login**
- Default credentials:  
  **Username:** `admin`  
  **Password:** `admin`

---

## 📂 Folder Structure

```
.
├── app.py
├── requirements.txt
├── utils/
│   └── shell_ops.py
├── static/
│   └── ... (CSS, images)
├── templates/
│   └── ... (HTML files)
```



## 🧑‍💻 Usage Examples

- **Monitor live GPU/CPU stats** on the dashboard.
- **Upload a CSV** on the CSV Analysis page to visualize GPU usage.
- **Manage users** (create, delete, list, search, view inactive).
- **Download** charts and inactive user lists as files.

---

## 🧩 Contributing

Pull requests and suggestions are welcome!


