# BudgetBuddy

Final Project mata kuliah Pengembangan Sistem dan Operasi (B).

Plan : Membuat aplikasi Budgetting

Anggota :
- Campin Waladsae Adiena - 5026221050
- Maurin Firsty Aulia - 5026211146
- Moh Atlomasiga Hasan Zahrandy - 5026211049

  ![image](https://github.com/campinwa/budgetbuddy/assets/166111616/83eca3e1-52b1-4c35-a5b3-098b6a5114c0)



  BudgetBuddy adalah aplikasi web yang dirancang untuk membantu pengguna mengelola keuangan mereka.


Requirements :
- Flask>=2.0.0
- pytest==6.2.4
- Werkzeug>=2.0
- flask-mysqldb
- apscheduler

CI : Github Action
![image](https://github.com/campinwa/budgetbuddy/assets/166111616/dc790f1e-332f-46f8-90fa-f91c3cc94324)


CD : Docker
![image](https://github.com/campinwa/budgetbuddy/assets/166111616/8492baa9-7371-4a70-a4de-392ef67288ef)


Cloud : Google Cloud Project
![image](https://github.com/campinwa/budgetbuddy/assets/166111616/0d7b09bd-cb11-40ee-8f53-df255184d05c)

Monitoring : Prometheus

Database : MySQL PHPmyadmin

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

