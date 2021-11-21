# Expense-Reimbursement-System

Project Description: The Expense Reimbursement System (ERS) will manage the process of reimbursing employees for expenses incurred while on company time. All employees in the company can login and submit requests for reimbursement and view their past tickets and pending requests. Finance managers can log in and view all reimbursement requests and past history for all employees in the company. Finance managers are authorized to approve and deny requests for expense reimbursement. 

Technologies Used: Java, JavaScript, HTML, CSS, JDBC, PostgreSQL, Javalin, Maven, JUnit4, Log4J

Features: 
  Create a new Employee in the database. An Employee can submit a reimbursement with an amount and a reason, login to see their own reimbursements, past and pending
  Create a new Manager in the database. A Manager can view all reimbursements past and pending, can appove or deny any reimbursement 
  
Getting Started: 
  git remote add origin https://github.com/tcollins-bu/Expense-Reimbursement-System.git
  Start and configure AWS RDS PostgreSQL database
  Run App.java in IDE
  Navigate web-browser to http://localhost:7000/
  
Usage: Open http://localhost:7000/ and log in as either an Employee or a Manager. As an Employee, view and submit Reiumbursement requests with amounts and reasons. As a Manager, view and approve or deny Reimbursement requests with additional note to requesting Employee.
