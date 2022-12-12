
# Backend for an E-Commerce website



## Objective
This project consists of a D-jango based backend designed for an E-Commerce website


## Features
- Defined categories for orders 

- Session tokken for each session

- Seperate user login for superuser/admin and for customers

- Place orders and edit order details such as cost,stock,etc. efficiently

- You can add more details in orders by simply editing api\order\views and then serializing it in serializers.Payment

- Custom model created for Payment Gateway using BrainTree


## Installation
Get Python ready to use and install pip (if you don't have)
```bash
  curl https://bootstrap.pypa.io/get-pip.py -o get-pip.py
  python get-pip.py

```

Install requirements.txt from the main file
```bash
 pip install requirements.txt

```
Then fire URL using
```bash
 python manage.py runserver

```

Access admin page from the link


```bash
http://127.0.0.1:8000/admin/
```

Your back_end is ready to go
