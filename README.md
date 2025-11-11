

---
⚡ Electricity Consumption Dashboard

A fully interactive web dashboard for calculating and visualizing electricity consumption and billing.
Built with Flask (Python) for backend and HTML, CSS, and JavaScript for frontend, this dashboard features:

Slab-based electricity bill calculation

History tracking using localStorage

Real-time charts (powered by Chart.js)

Light/Dark theme toggle



---

🎯 Project Overview

This project calculates the electricity bill based on user input (units consumed) and displays:

Bill summary (name, units, total amount)

Bill history (previous calculations saved locally)

Reports (interactive charts)

Theme settings (light/dark mode)


It is designed to be mobile-friendly, colorful, and easy to use — perfect for demonstrations, ECET mini projects, and portfolio displays.


---

🧩 Features

Feature	Description

⚙️ Dashboard	Input customer name and units consumed, then calculate total bill
🧾 History	Automatically saves previous bill records using browser localStorage
📊 Reports	Displays a bar chart of bills using Chart.js
🎨 Settings	Toggle between light and dark themes
💻 Responsive UI	Works smoothly on both desktop and mobile browsers



---

🏗️ Tech Stack

Frontend: HTML5, CSS3, JavaScript (ES6)

Backend: Flask (Python)

Database: LocalStorage (for history)

Visualization: Chart.js

Design: Gradient theme and responsive cards



---

📂 Project Structure

ElectricityConsumptionDashboard_Pro/
│
├── app.py                   # Flask backend
├── requirements.txt          # Dependencies
│
├── templates/
│   └── index.html            # Frontend structure
│
└── static/
    ├── style.css             # Styling and layout
    ├── script.js             # Frontend logic
    └── chart.min.js          # Chart.js library


---

⚙️ Installation & Setup

1️⃣ Clone the repository

git clone https://github.com/your-username/ElectricityConsumptionDashboard.git
cd ElectricityConsumptionDashboard

2️⃣ Install dependencies

pip install -r requirements.txt

3️⃣ Run the Flask app

python app.py

4️⃣ Open in browser

Go to 👉 http://127.0.0.1:5000


---

🧮 Billing Logic

Units Range	Rate (₹/Unit)

0 – 100	₹1.50
101 – 200	₹2.50
201 – 500	₹4.00
> 500	₹6.00
Fixed Charge:	₹50


Example:

Input: 275 units
Output: ₹950 total (including fixed charge)


---

📸 Screenshots (Preview)

Dashboard View:

+-----------------------------------------------------+
| Customer Name: [Sathish]                            |
| Units Consumed: [275]                               |
| [⚡ Calculate Bill]                                  |
|------------------------------------------------------|
| Bill Summary: Total ₹950.00                         |
+-----------------------------------------------------+

Reports View:

Interactive chart showing previous bills


Settings View:

Toggle between light and dark mode instantly



---

🧠 Future Enhancements

Add database (SQLite) for persistent history

User authentication (Login/Signup)

Export bill as PDF

Add pie chart comparison between months



---

👨‍💻 Author

Sathish Chandra
🚀 Passionate about Python, Web Development & Problem Solving.


---

📜 License

This project is open-source and available under the MIT License.


---
