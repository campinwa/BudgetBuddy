# BudgetBuddy

Final Project for Systems Development and Operations (B) course.

<p>The primary objective of this project is to immerse students in the practical aspects of DevOps, MLOps, or SecOps by providing them with hands-on experience. Students will gain expertise in automating and refining key processes such as software development, integration, testing, and deployment, as well as in the end-to-end development and deployment of machine learning models</p>

<p>The objective of this project is to empower students with a comprehensive understanding and practical skills in designing, implementing, and managing Continuous Integration and Continuous Deployment (CI/CD) pipelines. Through this hands-on experience, students will learn how CI/CD pipelines are instrumental in automating and streamlining the processes of building, testing, and deploying software and machine learning models. They will explore the critical role these pipelines play in accelerating the development lifecycle, ensuring that code changes are integrated and tested frequently, and deployed reliably. By mastering CI/CD practices, students will be equipped to create workflows that automate quality assurance and deployment processes, enabling rapid and safe delivery of updates and features. </p>

**Members :**
- Campin Waladsae Adiena - 5026221050
- Maurin Firsty Aulia - 5026211146
- Moh Atlomasiga Hasan Zahrandy - 5026211049

  ![image](https://github.com/campinwa/budgetbuddy/assets/166111616/83eca3e1-52b1-4c35-a5b3-098b6a5114c0)


**Roles :**
<ul>
<li>Campin :</li>
  <ul>
    <li>Building Code</li>
    <li>Code Review</li>
    <li>Testing</li>
    <li>All Initial Settings Tools</li>
    </ul>
<li>Maurin :</li>
  <ul>
    <li>Building Code</li>
    <li>Front End</li>
    <li>Code Review</li>
    <li>Testing</li>
    </ul>
  <li>Siga :</li>
  <ul>
    <li>Building Code</li>
    <li>Front End</li>
    <li>Back End</li>
    </ul>
</ul>

**ABOUT BUDGETBUDDY**

**BudgetBuddy is a comprehensive web application designed to empower individuals to manage their finances effectively.** 

**Key Features :**
- Expense Tracking: Record and monitor your daily expenses with ease.
- Income Tracking: Record and monitor your income sources.
- Daily Reports: Generate detailed Expense and Income reports with Total Balance.


**Requirements :**
- Flask>=2.0.0
- pytest==6.2.4
- Werkzeug>=2.0
- flask-mysqldb
- apscheduler

**CI : Github Action**
![image](https://github.com/campinwa/budgetbuddy/assets/166111616/dc790f1e-332f-46f8-90fa-f91c3cc94324)


**CD : Docker**
![image](https://github.com/campinwa/budgetbuddy/assets/166111616/8492baa9-7371-4a70-a4de-392ef67288ef)


**Cloud : Google Cloud Project**
![image](https://github.com/campinwa/budgetbuddy/assets/166111616/73520e7f-b2da-4a11-8a34-587123aba0be)

**Database : MySQL PHPmyadmin**

![image](https://github.com/campinwa/budgetbuddy/assets/166111616/16245329-8bf2-490d-8701-eac4a0efaa65)



To run locally:

Install docker and create account & username

Clone the repository

```bash
$ git clone https://github.com/campinwa/budgetbuddy.git
```

Open with Visual Code Studio or other tools that is similar

Change all "campinwaladsae" to your docker username then save all

Open terminal

Run

```bash
$ docker-compose up -d
```

**Note: Make sure that your docker desktop is running**

Go to your docker 

Click on the port for the app


To push to your docker hub repository:

Run in terminal 

```bash
$ docker build -t campinwaladsae:income-expense-app .

$ docker login

$ docker push <username>/income-expense-app

```

**Project Timeline:**


Week 1 : 28 Mei-31 Mei

<img width="1440" alt="Screenshot 2024-06-25 at 23 02 20" src="https://github.com/campinwa/budgetbuddy/assets/67356728/68aed2e3-15ec-4277-b618-2da4b066d235">

Week 2 : 1 Juni -7 Juni

<img width="1440" alt="Screenshot 2024-06-25 at 23 03 40" src="https://github.com/campinwa/budgetbuddy/assets/67356728/6cdff463-f604-491d-9fdf-958b24882874">

Week 3 : 8 Juni - 14 Juni

<img width="1440" alt="Screenshot 2024-06-25 at 23 05 46" src="https://github.com/campinwa/budgetbuddy/assets/67356728/04114fe0-8c67-40f0-8603-ac5027ef4921">

Week 4 : 15 Juni - 26 Juni

<img width="1440" alt="Screenshot 2024-06-25 at 23 07 25" src="https://github.com/campinwa/budgetbuddy/assets/67356728/72352d5f-a679-4039-aa9c-c2f6df293ccf">


