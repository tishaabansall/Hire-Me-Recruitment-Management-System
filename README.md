  

# HireMe – Recruitment Management System (DBMS Project)

This project is a database-driven Recruitment Management System developed as part of a DBMS mini project. It focuses on designing a structured relational database and implementing core recruitment workflows such as managing recruiters, candidates, job postings, and applications.

<img src="screenshots/HireMe.png" width="800">

## Tech Stack
- Python
- MySQL
- mysql.connector
- Tkinter (for UI)

## Features
- Recruiter and Client panels
- Candidate data management
- Job posting and application tracking
- Structured database schema with proper relationships
- Simple and interactive desktop UI

## Glimpse
<img src="screenshots/001_login.png" width="500">
<img src="screenshots/006_login_recruiter_mainscreen.png" width="500">
<img src="screenshots/011_client_availablejobs.png" width="500">

## Setup

1. Clone or download the repository.
```bash
git clone https://github.com/karan0805/Hire-Me.git
```
2. Move to the desired folder

```bash
cd Hire-ME
```
3. Make sure MYSQL is running on your System . Now move to `creds.py` inside modules folder and replace the value of `user_pwd`
```
 user_pwd = "your mysql password"
```
4. Now we're almost done so to create the required schema in your machine simply run 
```bash
python db_init.py
```
5. After setting up the schema, to run simply write
```bash
python main.py
```

## Learning Outcomes
- Relational database design and normalization
- Writing SQL queries and constraints
- Integrating Python with MySQL
- Understanding real-world DBMS use cases

## License 
This project is licensed under the MIT License.


