# 📊 Database Analyzer with Streamlit & Paramiko

A Streamlit-based application that allows users to:

- **Connect to a MySQL database via SSH**  
- **Run SQL queries in real-time**  
- **Visualize data** in both table and chart formats  
- **Interact through an intuitive Streamlit interface**

---

## 🔧 Key Features

- ✅ **Connect to remote MySQL server via SSH (no direct DB exposure)**  
- 🧠 **Execute SQL queries in real-time**  
- 📊 **Interactive data visualization using Seaborn & Matplotlib**  
- 🖥️ **Responsive UI with Streamlit**  
- 🛡️ **Secure credential entry from sidebar**

---

## 🛠️ Technologies Used

- **Python 3.x**  
- [Streamlit](https://streamlit.io/) – Interactive web interface  
- [Paramiko](https://www.paramiko.org/) – SSH connection handling  
- [Pandas](https://pandas.pydata.org/) – Data manipulation  
- [Seaborn](https://seaborn.pydata.org/) & [Matplotlib](https://matplotlib.org/) – Data visualization  

---

## ⚙️ Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/genta-bahana-nagari/Database_Analyzer_Project.git
   cd Database_Analyzer_Project
   ```

2. **(Optional) Create a virtual environment:**
   ```bash
   python -m venv venv
   source venv/bin/activate     # macOS/Linux
   venv\Scripts\activate        # Windows
   ```

3. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

4. **Run the Streamlit app:**
   ```bash
   streamlit run database-analyzer.py
   ```

---

## 🎯 How to Use

1. The app will open in your browser automatically.  
2. In the sidebar, input the following:
   - **SSH Server IP**
   - **SSH Username & Password**
   - **MySQL Username & Password**
   - **Target Database Name**
3. Choose a table to analyze from the dropdown.  
4. Write and execute a SQL query to retrieve data.  
5. Visualize the output as a table or bar chart.  
6. You can reset or reconfigure anytime via the sidebar.

---

## 📁 Project Structure

```
📁 database-analyzer/
├── database-analyzer.py     # Main Streamlit application
├── requirements.txt         # Python dependencies
└── README.md                # This documentation file
```

---

## 💡 Notes

- Make sure your **MySQL server allows access from the specified SSH user**.  
- If connection errors occur, verify that both **SSH and MySQL services are running**.  
- If charts do not display, ensure the queried data includes appropriate columns (e.g., `stock`, `title`).  

---

## 🤝 Contributing

Contributions are always welcome!  
Feel free to fork this repo and submit a pull request, or clone and build locally before proposing changes.

---

## 👤 Author

- **Genta Bahana Nagari** – [LinkedIn](https://www.linkedin.com/in/genta-bahana-nagari/) | [GitHub](https://github.com/genta-bahana-nagari)

---

## 🌟 Show Your Support

If you find this tool helpful, please ⭐ the repo and share it with others!

---

## 📜 License

This project is licensed under the **MIT License**. See the [LICENSE](LICENSE) file for full details.

---
