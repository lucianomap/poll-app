# 🗳️ Poll App

A polling web application where users can create polls, vote on them, and review real-time results. Built with Python, PostgreSQL for database and psycopg2 to handle the database connection.

---

## 🚀 Features

- 📝 Create, view and update polls  
- ➕ Add, edit, and remove multiple choices per poll  
- ✅ Navigate on the user menu and cast votes on active polls with your username
- 🎲 Randomly select a winner for a poll

---

## 🛠️ Tech Stack

- **Database**: PostgreSQL 
- **Environment**: Python 3.x  


## ⚙️ Quickstart

1. **Clone the repo**

    ```bash
    git clone https://github.com/lucianomap/poll-app.git
    cd poll-app
    ```

2. **(Optional) Create a virtual environment**

    ```bash
    python3 -m venv .venv
    source venv/bin/activate  # Windows: venv\Scripts\activate
    ```

3. **Install dependencies**

    ```bash
    pip install -r requirements.txt
    ```

4. **Rename the `.env.example` file**

    ```bash
    mv .env.example .env
    ```

5. **Write your PostgreSQL database credentials in the `.env` file**
6. 
   ```bash
    HOST = "(your host)"
    DATABASE_NAME = "(your database name)"
    USER = "(your username)"
    PASSWORD = "(your password)"
    ```

6. **Run the app**

    ```bash
    python app.py
    ```

---

## 📄 License

This project is released under the MIT License. See the [LICENSE](LICENSE) file for details.