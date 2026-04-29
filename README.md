
# Employee Management System in Python (Tkinter Frontend & MySQL Backend)

**Frontend**: Tkinter based frontend.

**MySQL Integration**: Integrated MySQL as the database backend.

## Features

- **Add an Employee:** Easily add new employees to your database with this function. Input their details, and the system will store them in the database.

- **Delete an Employee:** Select the employee to delete, and with a click of a button, it will remove the employee details from the database.

- **Update an Employee:** Make changes to their information/details and save the updated data.

- **View All Employees**: Fetch all employees from the database in a single click.

## Screenshots

<img width="1347" height="795" alt="home_screeen" src="https://github.com/user-attachments/assets/6162c43a-e872-49b6-9dfd-b2b9d30627cb" />

<img width="1347" height="795" alt="add_an_employee" src="https://github.com/user-attachments/assets/0ed8baa3-4337-47e8-9713-092752c4c5c7" />

<img width="1347" height="795" alt="delete_an_employee" src="https://github.com/user-
attachments/assets/d71f3dc4-41b9-4a0f-8df0-8154e2050be9" />

<img width="1347" height="795" alt="delete_an_employee_2" src="https://github.com/user-attachments/assets/ba10f754-865f-4b57-adf3-4d6af7704776" />

<img width="1347" height="795" alt="update_an_employee" src="https://github.com/user-attachments/assets/68cca01d-22bc-4ab5-a099-658641829753" />

<img width="1347" height="795" alt="update_an_employee_2" src="https://github.com/user-attachments/assets/d2622f56-0186-4182-81b4-f52dd7cb9b6e" />

<img width="1347" height="795" alt="view_all_employee" src="https://github.com/user-attachments/assets/d82d7e9c-48ae-403a-92e9-6a78ab3524ab" />

## Setup
- Fork this repo
- Clone repo
```sh
git clone https://github.com/OnkarSagare27/employee-management-mysql.git
```
- Configure stuff in ``config.json``
```json
{
    "pass": "DATABASE PASSWORD",
    "user": "root",
    "host": "localhost",
    "database": "employees"
}
```
- Install requirements
```sh
pip install -r requirements.txt
```
- Run ``main.py``
```sh
python main.py
```
