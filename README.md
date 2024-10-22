Here’s a README file tailored for Django CRM project that includes functionalities for adding records, displaying records, and providing feedback:


# Django CRM Project


## Introduction
This Django CRM (Customer Relationship Management) project is designed to help manage customer records efficiently. Users can add new customer records, view existing records, and provide feedback on customer interactions. The user-friendly web interface makes it easy to navigate through the functionalities.

## Features
- **Add Records**: Easily add new customer records with relevant details.
- **Show Records**: View a list of all customer records in a structured format.
- **Feedback System**: Users can provide feedback for each customer record, facilitating better communication and follow-up.

## Getting Started

Follow these steps to set up and run the Django CRM project locally:

### Prerequisites
- Make sure you have [Python](https://www.python.org/downloads/) installed on your computer.
- It is recommended to have [pip](https://pip.pypa.io/en/stable/) installed for package management.
- Install Django if it's not already installed:
  ```bash
  pip install django
  ```

### Installation
1. Clone this repository into a folder :
2. Navigate into the project directory:
   ```bash
   cd django-crm
   ```
3. Create a virtual environment:
   ```bash
   python -m venv venv
   ```
4. Set the execution policy (Windows PowerShell only):
   ```bash
   Set-ExecutionPolicy -Scope Process -ExecutionPolicy Bypass
   ```
5. Activate the virtual environment:
   ```bash
   .\venv\Scripts\Activate
   ```
6. Install the required packages:
   ```bash
   pip install -r requirements.txt
   ```
7. Run database migrations:
   ```bash
   python manage.py migrate
   ```
8. Start the local server:
   ```bash
   python manage.py runserver
   ```

### Accessing the App
Once the server is running, you can access the application by visiting `http://127.0.0.1:8000/` in your web browser.

## Default Admin Credentials
To log in as an admin and manage records, use the following credentials:

Username: admin
Password: admin12345

## Usage
- Navigate to the **Add Record** section to create a new customer record.
- View the **Records** section to see all the customer records.
- Provide feedback on each record to enhance customer relations.

## Screenshots
![2](https://github.com/user-attachments/assets/f0e5fb7a-65d5-4cdc-baab-c30d150ee3d0)
![3](https://github.com/user-attachments/assets/746f2091-aa4c-4ca4-bba1-ea105df0cef2)
![4](https://github.com/user-attachments/assets/dd0df3bc-ff39-436b-818f-af0d448a229a)
![5](https://github.com/user-attachments/assets/ef64358a-5106-45c8-b38f-f4b7a68222c2)
![6](https://github.com/user-attachments/assets/2a9c61b1-1fef-4d47-9d22-666d00d36197)
![1](https://github.com/user-attachments/assets/db9deccf-7e89-469d-a75d-8cee4750609f)

Feel free to contribute or raise issues if you encounter any bugs. Happy managing!
```
