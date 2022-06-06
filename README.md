# Vaccination-Esther-Project


 
# <Esther Vaccination Form>

## Description

I have created a website that is composed mainly by a form to get people of third world countries vaccinated against COVID , the user should introduce all the personal details in each checkbox . Once all the details have been introduced successfully the information of the user will be saved in the database using the backend technology.

In order to add the information of each patient we have used the following programs : Django, sqlite and all the data is written in Pycham for the backend

For the frontend  I’ve used react and the library of MIU for the table of all the data.

I have used many application of the react library for example react component countries in order to access the list of all countries in the world without needed to do any fetch for it

I’ve used axios promise in order to acesss all the data of the database.

When we fill the for we can get 2 possible messages either the patient was added successfully or the patient wasn’t added if there has been an error or the user has not introduce any of the data correctly

Once the POST request have been accepted from the database it will get added to the list and the list is on the table page in the website but it could be access through the sql database or though the console log of json.

I’ve used the postman app to check that all request of GET AND POST worked successfully.
Luckily enought that helped a lot amount the proccess  fixing some errors along the way till we got the 200 response. 
Ive implemented the library MIU for the table since it offers a wide range of options of filtering every patient , organizing and much more different options that helps the user to go through the information of each patient improving the user interface experience.



## Table of Contents 



- [Installation](#installation)

FrontEnd:
    • Firstly we ought open in terminal `after install` nodejs LTS version 16.15.1
    • install `npm install` command
    `npm start` will start the frontend project

BackEnd:
• Open Backend/settings.py change SECRET_KEY with your own key or a key from this site for example: 1234
• Change POSTGRSSE NAME and PASSWORD for your own postgrase sever configs,
• Once we have changed we have to run python manage.py makemigrations VaccinationApp
• Python manage.py migrate VaccinationApp
• At last we have to run the server: python manage.py runserver


## Usage
![FormExample](/assets/images/im2.png)
![TableExample](/assets/images/im3.png)
![formExample](/assets/images/im1.png)
![TableExample](/assets/images/im4.png)
 ![TableExample](/assets/images/im5.png)
 ![TableExample](/assets/images/im6.png)


## Credits


For the BackEnd I have used the following video: Python Django + PostgreSQL | REST API Tutorial:

https://www.youtube.com/watch?v=Pwwz4_AvHDU


---



## Features

Export to excel file (CSV)

React countries in order to obtain a list of all the countries in the whole world.

Fect data to refresh list.



Framework frontend: React, Node.Js, Bootstrap, MIU, React router,

Framework Backend:  
• Django 
• Psycopg2( npi install psycopg2)
• Djangorestf (pip install djangorestframework)
• Django-cors-headers(python -m pip install django-cors-headers)
• Asgiref, Whell, python-sqlparse - Parse SQL statements
• Pytz - World Timezone Definitions for Python
• Setupstools


