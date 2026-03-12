🚔 Crime Record Database Management System

A Crime Record Database Management System (CRDMS) is a software application designed to efficiently manage and maintain crime-related records. This system helps law enforcement agencies store, retrieve, and analyze crime data such as criminal records, case details, FIR reports, and investigation status in a structured database.

The project aims to simplify crime data management by replacing manual paperwork 📄 with a secure digital system 💻.

✨ Features

➕ Add new crime records

✏️ Update existing crime data

❌ Delete records when required

👤 Manage criminal details

📝 Register FIR (First Information Report)

🔍 Search crime records quickly

📊 Track case status and investigation progress

🗂️ Maintain police officer records

🔐 Secure and organized database storage

🧩 System Modules
👨‍💼 Admin Module

Manage police officer accounts

View all crime reports

Update case status

Maintain database records

🚨 Crime Records Module

Add new crime reports

Store crime type, location, and date

Assign investigation officer

🧑‍⚖️ Criminal Records Module

Maintain criminal profiles

Store criminal history

Link criminals with cases

🔎 Search Module

Search records using:

Criminal Name

Case ID

Crime Type

Date of Crime

🛠️ Technologies Used
Technology	Purpose
💻 Programming Language	Java / Python / PHP / etc.
🗄️ Database	MySQL / PostgreSQL
🎨 Frontend	HTML, CSS, JavaScript
⚙️ Backend	Node.js / Django / Flask / PHP
🌐 Version Control	Git & GitHub
🗃️ Database Design

The system includes the following tables:

👤 Criminal

🚨 Crime

📝 FIR

👮 Police Officer

📂 Case Details

🔬 Evidence

Relationships between tables are maintained using Primary Keys 🔑 and Foreign Keys 🔗.

⚙️ Installation
1️⃣ Clone the repository
git clone https://github.com/your-username/crime-record-dbms.git
2️⃣ Navigate to the project folder
cd crime-record-dbms
3️⃣ Install required dependencies
npm install

or

pip install -r requirements.txt
4️⃣ Setup the database

Import the SQL file into MySQL

Configure database credentials in the project files

5️⃣ Run the application
npm start

or

python app.py
🚀 Usage

1️⃣ Login as Admin 👨‍💼 or Police Officer 👮
2️⃣ Register a new FIR 📝
3️⃣ Add Crime and Criminal details 🚨
4️⃣ Update Case progress 📊
5️⃣ Search records when required 🔍

📁 Project Structure
crime-record-dbms
│
├── 📂 database
│   └── crime_db.sql
│
├── ⚙️ backend
│   └── server files
│
├── 🎨 frontend
│   └── HTML / CSS / JS
│
├── 📸 screenshots
│
└── 📄 README.md
🔮 Future Improvements

🤖 Face recognition for criminal identification

📊 Crime analytics dashboard

🗺️ Crime location mapping using GIS

🔐 Role-based authentication system

📱 Mobile application support
