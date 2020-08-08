# Welcome to PostgreSQL Starter Package!

Hey this is Avishek Das and welcome to my PostgreSQL starter Pack. Here I will show a you step by step guide from the beginning to advance roadmap of PostgreSQL. Stay tuned.
<!--1. [Installation](#1-Installation)-->

# 1. Installation
Being a Windows user I will show the steps & all the hassles for **Windows** only. For MAC and Linux Installation I will refer to these sites -> [Mac](https://www.postgresqltutorial.com/install-postgresql-macos/) , [Linux](https://www.postgresqltutorial.com/install-postgresql-linux/) . Actually they are very straighforward so don't worry.

***Step1:*** Download the appropriate version from [here](https://www.enterprisedb.com/downloads/postgres-postgresql-downloads).

***Step2:*** Install normally , give a password when prompted & let the installation finish.

![enter image description here](https://i.ibb.co/x3xGPzb/1.png)

Notice that postgres is the default superuser here.

***Step3:*** From you Application menu pick the **PgAdmin4** and **SQL Shell** and drag them to your Desktop. 

<img src="https://i.ibb.co/bFFKpGQ/ins2.png" alt="drawing" width="450"/>

 - PgAdmin4 is the GUI version where you can manage all the works of Postgres
 - and SQL Shell is the CLI version(which we shall often use)
 
 ***Step4:*** Now just open you CMD or Any other windows CLI and type ***psql***
 
 <img src="https://i.ibb.co/JkvdNds/ins4-1.png" alt="drawing" width="550"/>
Command is not recognized!!! 😱 COOL DOWN i got you 🤓


## Environment variable setup
Goto installation directory and copy the **bin** location

> C:\Program Files\PostgreSQL\12\bin

Now simply add this to your system/user environment.  (You may go through [this](https://www.architectryan.com/2018/03/17/add-to-the-path-on-windows-10/) guide if you are new to environment variable setup)

OK, NOW AGAIN, open you CMD or Any other windows CLI and type _**psql**_

 <img src="https://i.ibb.co/thD7tst/ins3.jpg" alt="drawing" width="420"/>
Hola!!! Now the command is recognized. Enter the password.

<img src="https://i.ibb.co/BwBHG8h/ins4.png" alt="drawing" width="700"/>
GOT another one!! 😛 ... Again Got YOU.

## Set the Default username
Open you CLI and just type

     set PGUSER=postgres
  Finally type ***psql*** and enter the pass.
  
  <img src="https://i.ibb.co/1bpFZpM/ins5.png" alt="drawing" width="800"/>
  Congratulations!!! You have overcome all the hassles 🎉
