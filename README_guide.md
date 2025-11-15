  
# Sales and Inventory Management System
[![License](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/license/mit)
[![Python Version](https://img.shields.io/badge/Python-3.12-green)](https://www.python.org/downloads/)

## Overview
This project is a Django-based application designed to help manage business operations in a simple and efficient way. It includes user profiles, vendors, customers, invoices, billing, and inventory tracking. The frontend uses Bootstrap, and Ajax is included for smoother and faster sales operations.

## Repository
To link your local project to this repository, run:

```bash
git remote add origin https://github.com/M-sahoo2007/sales_and_invontary_management_System.git
````

## Table of Contents

* [Overview](#overview)
* [Repository](#repository)
* [Prerequisites](#prerequisites)
* [Installation](#installation)

  * [Clone the Repository](#clone-the-repository)
  * [Using Docker](#using-docker)
  * [Without Docker](#without-docker)

    * [Linux Setup](#linux-setup)
    * [Windows Setup](#windows-setup)
* [Screenshots](#screenshots)
* [Authors](#authors)

## Prerequisites

* Python installed. Download it from: [https://www.python.org](https://www.python.org)
* Basic understanding of Python and Django.

## Installation

### Clone the Repository

```bash
git clone https://github.com/M-sahoo2007/sales_and_invontary_management_System.git
cd sales_and_invontary_management_System
```

---

## Using Docker

### Build the Image

```bash
docker build -t sales-and-inventory-management:1.0 .
```

### Run the Container

```bash
docker run -d -p 8000:8000 sales-and-inventory-management:1.0
```

---

## Without Docker

### Linux Setup

1. Create and activate a virtual environment:

   ```bash
   python3 -m venv venv
   source venv/bin/activate
   ```

2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Apply migrations and start the server:

   ```bash
   python manage.py migrate
   python manage.py runserver
   ```

---

### Windows Setup

1. Create and activate a virtual environment:

   ```bash
   python -m venv venv
   venv\Scripts\activate
   ```

2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Apply migrations and start the server:

   ```bash
   python manage.py migrate
   python manage.py runserver
   ```

---

## Screenshots

(Add your screenshots here)

## Authors

* **Maheswar Sahoo**

---

**Happy coding! 🚀**

 
```
