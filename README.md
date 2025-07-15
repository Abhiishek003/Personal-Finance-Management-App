# Personal-Finance-Management-App
Overview
The Personal Finance Management System is an application developed using Java Swing on Apache NetBeans IDE and MySQL for Database Management. This system enables users to monitor their financial habits, track previous transactions, and visualize monthly financial data using charts.

##  Software Used
IDE: Apache NetBeans
# Database: MySQL
Java UI Framework: Java Swing
Chart Library: XChart
# Features
Account Management: Users can create and manage multiple accounts to meet their financial needs.
Summarized Display: Provides users with a clear overview of their financial status, including current savings and spending habits.
Income and Expense Tracking: Dedicated tabs allow users to conveniently record their income and expenses, facilitating efficient management of finances.
Interactive Charts: Visualize monthly expenditure and savings through interactive charts, offering users insightful graphical representations of their financial data.
Transaction History: Easily access and review the latest transactions, enabling users to track their financial activity over time.
Savings Target: Set savings targets with a progress bar indicating the progress towards the goal for the current month, empowering users to stay focused on their financial objectives.
# Additional Libraries Used
JDBC Driver (MySQL Connector): Connects Java applications to MySQL databases.
JCalendar: Provides Date-related components for user-friendly date selection.
XChart: Generates interactive charts for visualizing financial data.
AbsoluteLayout: Facilitates precise positioning of UI components.
# Project Structure
📦src
┣ 📂Chart
┃ ┗ 📜IncomeExpenseChart.java
┣ 📂Database
┃ ┣ 📜DatabaseManager.java
┃ ┗ 📜UserSession.java
┣ 📂Home
┃ ┣ 📜HomePage.form
┃ ┗ 📜HomePage.java
┣ 📂Icon
┃ ┗ 📜icons.png...
┣ 📂Login
┃ ┣ 📜Login.form
┃ ┣ 📜Login.java
┃ ┣ 📜SignUp.form
┃ ┗ 📜SignUp.java
┗ 📂personalfinancemanagement
┗ 📜PersonalFinanceManagement.java
# Screenshots
# Login

<img width="1002" height="665" alt="image" src="https://github.com/user-attachments/assets/a73944e8-e4c8-4cd4-a9f7-569e32ca89fd" />



Signup

<img width="1000" height="666" alt="image" src="https://github.com/user-attachments/assets/3fd1e7a7-5008-4102-89b8-603d61b09265" />


Home
<img width="1034" height="651" alt="image" src="https://github.com/user-attachments/assets/29ef4c7e-3a56-4257-8ad6-a3801f7121d0" />

Accounts
<img width="1036" height="652" alt="image" src="https://github.com/user-attachments/assets/ba46d21d-daeb-4855-884f-f7492d869e66" />


Income
<img width="1039" height="649" alt="image" src="https://github.com/user-attachments/assets/98f833bc-ec19-4853-a911-ccd1fa23b625" />

Expense
<img width="1037" height="650" alt="image" src="https://github.com/user-attachments/assets/7f9eb4c0-5c48-41f8-b6cb-50be47e83cbe" />


Budget
<img width="1038" height="655" alt="image" src="https://github.com/user-attachments/assets/1a15b59f-6ae0-46ff-826f-a2e0790009e8" />


# Installation
Clone the repository.
Open the project in Apache NetBeans.
Set up the MySQL database according to the provided schema.
Navigate to the database_setup folder and follow the instructions in the README.md file to set up the database.
Run the project.
# Usage
Sign up for an account or log in if you already have one.
Add accounts and set up your financial details.
Record your income and expenses.
Monitor your financial status through the provided charts and summaries.
