# HumanHealthStats
Health Awareness Project
 HumanHealthStats

Technologies Used: Python Programming • Data Visualization (Matplotlib, Pandas) • MySQL with AWS RDS

> Bridging technology and healthcare through data-driven cloud insights.
---
🌟 Overview
HumanHealthStats is a cloud-based healthcare analytics project that calculates a user’s Body Mass Index (BMI), analyzes lifestyle habits such as smoking and drinking, and provides data-driven visual insights using Python.
It integrates with AWS RDS (MySQL) to store and retrieve data securely, delivering an end-to-end cloud solution that promotes preventive healthcare and health awareness.
This project demonstrates how technology and cloud computing can work together to transform raw health data into meaningful insights for users.
---

⚙️ Features
🧮 Smart BMI Calculator – Computes BMI and classifies users as Underweight, Normal, Overweight, or Obese.

☁️ AWS RDS Integration – Connects with AWS MySQL Database to store user records automatically.

📊 Visual Analytics – Generates Bar and Pie charts using Matplotlib to show global death causes (smoking, drinking, obesity).

🔄 Automated Workflow – From data input to visualization and cloud storage — all in one flow.

💡 Healthcare Awareness – Helps users understand how lifestyle habits impact their health outcomes.

---
🛠️ Tech Stack

Programming Language: Python

Database: AWS RDS (MySQL)

Libraries: Matplotlib, Pandas, PyMySQL

Environment: AWS Cloud, Local Python IDE

---

🧩 How It Works

1. The user enters their name, age, weight, height, and lifestyle habits.
2. The program calculates BMI and classifies health status.
3. Global mortality data is visualized through bar and pie charts.
4. User data and BMI insights are stored in AWS RDS automatically.
---

📈 Example Output

Name: Mayank
Age: 26
BMI: 24.49
Status: Normal
Drinking Habit: Yes
Smoking Habit: No

Global Death Statistics:
Smoking: 35%
Drinking: 25%
Obesity: 30%
Healthy Lifestyle: 10%

✅ Data successfully saved to AWS RDS!

(Program generates bar and pie charts showing global health trends.)

---

🧱 Database Schema

CREATE TABLE users (
  id INT AUTO_INCREMENT PRIMARY KEY,
  name VARCHAR(50),
  age INT,
  weight FLOAT,
  height FLOAT,
  bmi FLOAT,
  status VARCHAR(20),
  drink VARCHAR(10),
  smoke VARCHAR(10)
);

---
🚀 Future Enhancements

Add a Flask-based web dashboard for browser visualization.

Use real-time health datasets from WHO or Kaggle for analytics.

Deploy full system on AWS EC2 for public access.

---
🤝 Contribution
Contributions are welcome!
Fork the repository, improve the features, and submit a pull request to collaborate.
---
👨‍💻 Author
Mayank Singh Rathore
💼 DevOps & Data Engineering Enthusiast
📧 cloudmayankdevops@gmail.com
