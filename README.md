## Introduction

This is a simple Todo application built off Django (including the Django REST Framework for API CRUD operations) and React. For a complete walkthrough, see [Build a To-Do application Using Django and React](https://www.digitalocean.com/community/tutorials/build-a-to-do-application-using-django-and-react)

## Requirements
* Python3
* Pipenv

## Getting started
1. Clone the project to your machine ```[git clone https://github.com/Jordanirabor/django-todo-react]```
2. Navigate into the diretory ```[cd django-todo-react]```
3. Source the virtual environment ```[pipenv shell]```
4. Install the dependencies ```[pipenv install]```
5. Navigate into the frontend directory ```[cd frontend]```
5. Install the dependencies ```[npm install]```

## Run the application
You will need two terminals pointed to the frontend and backend directories to start the servers for this application.

1. Run this command to start the backend server in the ```[backend]``` directory: ```[python manage.py runserver]``` (You have to run this command while you are sourced into the virtual environment)
2. Run this command to start the frontend development server in the ```[frontend]``` directory: ```[npm install]``` (This will start the frontend on the adddress [localhost:3000](http://localhost:3000))

## Built With

* [React](https://reactjs.org) - A progressive JavaScript framework.
* [Python](https://www.python.org/) - A programming language that lets you work quickly and integrate systems more effectively.
* [Django](http://djangoproject.org/) - A high-level Python Web framework that encourages rapid development and clean, pragmatic design.

## Creator Credit

This demo app was originally built for a scotch.io (acquired in 2020 by DigitalOcean) article by [Jordan Irabor](https://github.com/Jordanirabor/django-todo-react)



معرفی

این یک برنامه ساده Todo است که از جنگو (شامل چارچوب Django REST برای عملیات API CRUD) و React ساخته شده است. برای توضیح کامل، به ساخت اپلیکیشن To-Do با استفاده از Django و React مراجعه کنید
الزامات

    پایتون 3
    پیپنف

شروع شدن

    پروژه را روی دستگاه خود کلون کنید [git clone https://github.com/Jordanirabor/django-todo-react]
    به فهرست راهنما بروید [cd django-todo-react]
    منبع محیط مجازی [pipenv shell]
    وابستگی ها را نصب کنید [pipenv install]
    به دایرکتوری frontend بروید [cd frontend]
    وابستگی ها را نصب کنید [npm install]

برنامه را اجرا کنید

برای راه اندازی سرورهای این برنامه به دو پایانه نیاز دارید که به دایرکتوری های frontend و backend اشاره دارند.

    این دستور را اجرا کنید تا سرور باطن در قسمت راه اندازی شود [backend]فهرست راهنما: [python manage.py runserver](شما باید این دستور را در زمانی که در محیط مجازی منبع هستید اجرا کنید)
    این دستور را اجرا کنید تا سرور توسعه frontend در قسمت راه اندازی شود [frontend]فهرست راهنما: [npm install](با این کار قسمت ظاهری در آدرس localhost:3000 شروع می شود )

ساخته شده با

    React - یک چارچوب جاوا اسکریپت مترقی.
    پایتون - یک زبان برنامه نویسی که به شما امکان می دهد سریع کار کنید و سیستم ها را به طور موثرتر یکپارچه کنید.
    جنگو - یک چارچوب وب پایتون سطح بالا که توسعه سریع و طراحی تمیز و عملی را تشویق می کند.

اعتبار خالق

این برنامه آزمایشی در ابتدا برای مقاله scotch.io (در سال 2020 توسط DigitalOcean خریداری شد) توسط Jordan Irabor ساخته شد. 
