# Salon Appointment Scheduler

This project is part of the freeCodeCamp Relational Database Certification.

## 📌 Description
This is a Bash-based interactive program that allows users to schedule appointments for a salon.  
It connects to a PostgreSQL database and performs operations such as:

- Displaying available services
- Accepting user input
- Checking existing customers
- Adding new customers
- Scheduling appointments

## 🛠️ Technologies Used
- Bash scripting
- PostgreSQL
- SQL

## 🗂️ Project Structure
- `salon.sh` : Main Bash script for user interaction
- `salon.sql` : Database dump file (schema + data)

## ▶️ How to Run
1. Start PostgreSQL
2. Restore database (if needed):
   ```bash
   psql -U postgres < salon.sql
