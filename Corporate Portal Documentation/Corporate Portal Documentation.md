![](https://portal.mawarid.com.sa/System/assets/images/mawarid-logo-2.png)

## Mawarid Corporate Portal (BCP) Documentation

### Corporate (BCP) Application

This Mawarid Corporate (BCP) application has 2 type of login access:

> 1. Corporate Portal
> 2. Corporate Administration

### Corporate Portal

> ### Introduction

A corporate portal is a centralized online platform used by organizations to provide employees, partners, and stakeholders with access to a wide range of resources and tools. It typically includes features like document management, communication tools, project tracking, and employee services. By integrating various functions into a single interface, corporate portals streamline workflows, enhance collaboration, and improve efficiency within a company.

![](./Assets/Login%20page.png)

* After created the Corporate Portal user in the Corporate Administration Portal, the username and password will generated for the new user to access the corporate portal.

* At the same time, an admin should add and assign customers and projects for that user.

* While creating the new corporate portal user in the corporate administration portal, the admin can't add or update the user's mobile number while creating the new user only the user can do.

* When an admin creating a new user in the Corporate administration portal, the same user will also create in the ERP automatically.

* When the new user is going to login the corporate portal for the first time, he wants to register his mobile number in the login page to get the otp message while login the portal.

* Only the user can register his mobile number or update the mobile number, admin can't do it.

<br>

![](./Assets/Welcome%20page.png)

This Welcome page shows the tiles with menu shortcuts of `Dashboard, Create Request, Iqama Expiry, Requests, Reports, Time Sheet, Interview Process Flow, Security and Admin Reports`. 

> ### Create Request

Create Request has a 2 types of requests,

> 1. Return Request Process
> 2. Admin Request

<br>

**Retrun Request Process**

* Return Request Process includes 3 requests, `Leave Request, Final Exit Request, Return Request`.

* This Return Request Process has a 6 types of create requests, 

> 1. Failed to pass professional exams
> 2. Requesting the worker's resignation and final exit
> 3. Internal/external leave
> 4. Assault on the worker/mistreatment of the worker
> 5. Exit and re-entry visa application
> 6. Request emergency leave

<br>

**Admin Request**

* Admin Request page has a 3 types of create requests page, `Renew Employee Contract, Admin Request, Letter Requests for Labour`.

* These requests were able to create here, but the created requests are listed in the ERP system.

<br>

> ### Iqama Expiry

* This Iqama Expiry menu shows the list of data of employee's iqama renewal by stages.

* There are 5 stages of employee's iqama renewal process,

> 1. New Request (New)
> 2. Customer Approval (InProgress)
> 3. Supervisor Approval (InProgress)
> 4. Iqama Renewal (InProgress)
> 5. Completed (Closed)

> ### Requests

![](./Assets/Request%20Menu.png)

This Requests menu has 9 sub-menus,

> 1. Admin Requests
> 2. Leave & Termination
> 3. Bulk Request Queue
> 4. Leave Request Approval
> 5. Termination Requests Approval
> 6. Other Requests Approval
> 7. Contract Renewal Request Approval
> 8. Admin Request Approval
> 9. Letter Request Approval

**Requests > Admin Requests**

* The Admin Request page shows the lists of data admin requests with request details, request status and employee details.

* These datas are not created in this portal, just we are showing these datas from erp.

* The user can download this list of data as a excel file.

**Requests > Leave and Termination**

* Leave and Termination page shows the lists of Employee's Leave and Termination requests with Employee details, Project name and Request details.

* These list of datas are not created here, it is created in the erp and we showing here for the users.

* The user can also download this list of data as a excel file.

**Requests > Bulk Request Queue**

* This is Bulk Request Queue shows the list of datas of bulk requests which means multiple requests.

* It shows with the status of the requests.

* Also here the create request button is available to create the request of `Return Request Process > Leave, Termination, Leave Multiple, Return Request` and `Admin Request > Renew Contract, Admin Request, Letter Request.`

* The user can also download this list of data as a excel file.

**Request > Leave Request Approval**

* Leave Request Approval page has the lists of datas of leave request approvals by stages.

* This page shows 4 stages list of Leave Request Approval,

> 1. Show Pending (Pending)
> 2. Draft
> 3. Approved
> 4. Reject 

* This page has details of the `Project, Customer, Leave Start and End date, Ticket details and Status.`

* The user can take actions to Approve or Reject the request here.

**Request > Termination Request Approval**

* Termination Request Approval page shows the lists of Termination Requests by stages.

* This page shows 4 stages list of Termination Request Approval,

> 1. Show Pending (Pending)
> 2. Draft
> 3. Approved
> 4. Reject 

* This page has details of the `Project, Customer, Leave Start and End date, Ticket details and Status.`

**Request > Other Request Approval**

* The Other Request Approval page shows the other requests which means any other requests, doesn't include Return Request Process and Admin Requests.

* This page also shows 4 stages list of Other Request Approval,

> 1. Show Pending (Pending)
> 2. Draft
> 3. Approved
> 4. Reject 

* This page has details of the `Project, Customer, Employee, and Status.`

* These datas are not created here, it is comes from the erp, we just call their api to show the datas.

**Request > Contract Renewal Request Approval**

* Contract Renewal Request Approval page shows the lists of approval requests of Contract Renewal Requests.

* This page also shows 4 stages list of Contract Request Approval,

> 1. Show Pending (Pending)
> 2. Draft
> 3. Approved
> 4. Reject

* This page has details of the `Project, Customer, and Status.`

* The user can take action of these datas to Approve or Reject.

* These datas are not created here, it is comes from the erp, we just call their api to show the datas.

**Request > Admin Request Approval**

* Admin Request Approval page shows the lists of approval requests of Admin Requests.

* This page also shows 4 stages list of Admin Request Approval,

> 1. Show Pending (Pending)
> 2. Draft
> 3. Approved
> 4. Reject

* This page has details of the `Project, Customer, Request type and Status.`

* The user can take action of these datas to Approve or Reject.

* These datas are not created here, it is comes from the erp, we just call their api to show the datas.

**Request > Letter Request Approval**

* Letter Request Approval page shows the lists of approval requests of Letter Requests.

* This page also shows 4 stages list of Letter Request Approval,

> 1. Show Pending (Pending)
> 2. Draft
> 3. Approved
> 4. Reject

* This page has details of the `Project, Customer, Letter type and Direction.`

* The user can take action of these datas to Approve or Reject.

* These datas are not created here, it is comes from the erp, we just call their api to show the datas.

<br>

### Reports

![](./Assets/Reports%20Menu.png)

This Reports menu has totally 10 sub-menus, They are;

> 1. Labors
> 2. Projects
> 3. Pay Statement Report
> 4. Salary and Fee Report
> 5. Loan Report
> 6. Aging Report
> 7. All Invoice
> 8. Pending Invoices
> 9. Account Statement
> 10. Account Statement Report

<br>

**Reports > Labors**

* Labors menu page shows the list of labor's report with the details.

* This Labor list shows the details of Employee, Iqama, Passport, Project and Contract.

* Here the user can download the Letter and labor lists data.

**Reports > Projects**

* Projects menu shows the lists of Projects with the details of `project name, type and attachments.`

* The user download the lists of datas here.

**Reports > Pay Statement Report**

* This Pay Statement Report page shows only the pay statement reports of the worker.

* It shows the worker's pay statement report with value and the fields of `Salary Calculation Id, Line Number, Personnel Number, Worker Name, Category Id, Organization Number, Pay Method, Pay Group Id, Pay Group Start & End Date, Basic Salary, Month Days, Actual Days, Absence Days, Vacation days, Loan Amount, Other Deduction, Net Salary and Total Vacation Days.`

* The user can view the Pay statement reports by filtering by `date, monthly and project id.`

* The user can Export this Pay statement report from his needed date and month from the project.

**Reports > Salary and Fee Reports**

* This Salary and Fee Reports page shows the Reports of an Employee's Salary and Fees Report.

* It shows the Employee's salary and fees report with the fields of `Employee Id, Name, Net Salary and Deserved Monthly Fee.`

* This Reports can able to download by user.

* The user can search reports by Time sheet Id.

**Reports > Loan Report**

* This Loan Report menu shows the details of the employee's loan reports.

* The Loan Reports are listed with the details of `Personnel Number, Worker Name, Loan Id, Source Type, Loan Profile Id, Loan Type, Other Loan Type, Loan Date, Loan Status, Workflow Status, Amount, Number of Installments, Deducted Amount, Remaining Amount and On Hold.`

* The User can download this report with datas.

**Reports > Aging Report**

* This Aging Report page shows the datas of the employee's aging report.

* This report shows the details with the fields of `Aging Period Definition, Description, Company and Sys Operation Execution Mode.`

* The user can able to download this Aging Report list.

**Reports > All Invoice**

* This Invoice menu shows the datas of employee's invoice list.

* This Invoice list shows the details of `Is Cleared From Zacta, Invoice Id, Sales Id, Invoice Date, Trans Dec, Currency Code, Invoice Amount and Proj Id.`

* The user can download this invoice details and the summary.

**Reports > Pending Invoices**

* Pending Invoices menu page shows the list of pending invoices of the employee.

* This invoice list shows the details of `Account Number, Customer Name, Invoice, Sales Id, Transaction Date, Transaction Description, Amount and Remaining Amount.`

* The user can able to download this invoice list datas.

**Reports > Account Statement**

* This Account Statement menu page shows the list of datas are employee's account statement.

* This Account Statement list shows the account statement details with the fields of `Transaction Date, Description, Invoice, Amount, Credit, Debit, Remaining Amount and Balance.`

* The user can download this account statement datas here.

**Reports > Account Statement (Reports)**

* Here the user can see the full complete Statement of Account report (Account Summary)

* User can able to download this account statement and take printouts.

<br>

### Time Sheet

**Time Sheet**

* This Time Sheet menu has the employee timesheet with datas.

* This time sheet has the datas with the fields of `Export, Import, Process, Submit, TimeSheet Id, Period, Project Id, Process Status, Approval Status, ERP Status and Salary Processed.`

* Here the user can download these datas.

* The user can filter the timesheet by month and year.

**Time Sheet Approve**

* This Time Sheet Approve menu shows the employee approve timesheet with datas.

* That the same fields with datas are shows here as Time sheet.

* The user can download these datas here.

<br>

### Interview Process Flow

**Interview Process Flow > Interview Process**

* This Interview Process menu shows the interview flow stages with datas. The Interview flow stages are,

> 1. Show Pending
> 2. Schedule
> 3. Agent Interview
> 4. Company Interview
> 5. Customer Interview
> 6. Online Test Schedule
> 7. Reschedule
> 8. Selected
> 9. Rejected

* The Interview Process shows the datas with the fields of `Interview Process Id, Candidate Id, Rec Order Line Id, Title, Description, Schedule Date, Schedule Time, Date, Time, Duration, Source Id and Source.`

**Interview Process Flow > Customer Interview**

* This Customer Interview menu shows the datas of interview which has been held by the customer for the employees.

* The Customer Interview menu has the interview flow stages with datas. The Customer Interview flow stages are,

> 1. Show Pending
> 2. Schedule
> 3. Confirmation
> 4. Interview
> 5. ReSchedule
> 6. Online Test
> 7. Selected
> 8. Rejected

* Customer Interview has the datas with the fields of `Interview Process Id, Candidate Id, Rec Order Line Id, Description, Date, Time, Duration, Agent Interview, Customer Interview and Company Interview.`

### Security

**Security > User Login**

* This User Login menu main purpose is to view the users last login and last logout date time of the users.

* User Login list shows the datas on the fields of `Name, User Name, Email, Mobile Number, User Type, Last Login, Last Logout, Customer Id, Account Id, Project Id and Customer Id's.`

* Here the user can Activate & DeActivate his account or the other user's account.

* And the user can assign role for him or other users.

* Here the user can create new users and assign project and customers for him.

* The user can edit or delete the existing users.

**Security > Role Master**

* The Role Master menu is very useful for the user or admin to give special role permission for the particular user to access the particular menu or settings.

* To give any new permission for the particular user, here the user can create new role.

* The user can assign and unssign the user to the roles.

* The user can edit and delete the roles.

**Security > User Activity**

* This User Activity menu shows the current date user's activities like what are the requests and actions are done by the users.

* Here the date filter is also available to filter the user's activities.

* The download option is also available to export the user activity report.

### Admin Reports

**Admin Reports > User Login Report**

* User Login Report menu page shows the login reports of the total users in portal.

* The User Login Report shows the login report information under the fields of `Name, User Id, Created Date, SignIn Date Time, SignOut Date Time, IP Address and Platform.`

* Here the filter is available to filter the from date and to date which means user signin date and signout date. Also can filter by username.

* This report slightly different from the user activity report.

* The download option is also available to export the user login report.

* This menu also shows the user login report and users report in chart view.

**Admin Reports > Approved TimeSheet Report**

* This Approved Timesheet Report menu page shows the list of employee's approved timesheet reports.

* These reports shows the information under the fields of `Customer Id, Project Id, Created By, Created Date, Method, URL, Request Body, Client URL, Header, Response, Status, Comments, Method Name and TimeSheet Type.`

* Here the filter is also available to filter the reports by date.

* The user can also see this report in chart view.

* Here the user has download option to download this reports.

**Admin Reports > Generated Timesheet Report**

* This menu page shows the list of Generated TimeSheet Reports.

* This Generated Timesheet report shows the datas under the fields of `Customer Id, Project Id, Created By, Created Date, Method, URL, Request Body, Client URL, Header, Response, Status, Comments, Method Name and TimeSheet Type.`

* Here the filter is also available to filter the Generated timesheet reports by date.

* The user can also see this report in chart view.

* Here the user has download option to download this reports.

**Admin Reports > Leave Request Report**

* This menu page shows the list of Leave Request Reports.

* The Leave Request Reports page shows the details under the fields of `Customer Id, Project Id, Created By, Created Date, URL, Method, Request Body, Header, Response, Status, Comments and Method Name.`

* Here the filter is also available to filter the Leave Request reports by date.

* The user can also see this report in the chart view.

* Here the user has download option to download this reports.

**Admin Reports > Termination Request Report**

* This Termination Request menu page shows the list of Termination Request Reports.

* The Termination Request Reports page shows the details under the fields of `Customer Id, Project Id, Created By, Created Date, URL, Method, Request Body, Header, Response, Status, Comments and Method Name.`

* Here the filter is also available to filter the Termination Request reports by date.

* The user can also see this report in the chart view.

* Here the user has download option to download this reports.

**Admin Reports > Other Request Report**

* This Other Request menu page shows the list of Other Request Reports.

* The Other Request Reports page shows the details under the fields of `Customer Id, Project Id, Created By, Created Date, URL, Method, Request Body, Header, Response, Status, Comments and Method Name.`

* Here the filter is also available to filter the Other Request reports by date.

* The user can also see this report in the chart view.

* Here the user has download option to download this reports.

**Admin Reports > Letter Request Report**

* This Letter Request menu page shows the list of Letter Request Reports.

* The Letter Request Reports page shows the details under the fields of `Customer Id, Project Id, Created By, Created Date, URL, Method, Request Body, Header, Response, Status, Comments and Method Name.`

* Here the filter is also available to filter the Letter Request reports by date.

* The user can also see this report in the chart view.

* Here the user has download option to download this reports.

**Admin Reports > Admin Request Report**

* This Admin Request menu page shows the list of Admin Request Reports.

* The Admin Request Reports page shows the details under the fields of `Customer Id, Project Id, Created By, Created Date, URL, Method, Request Body, Header, Response, Status, Comments and Method Name.`

* Here the filter is also available to filter the Admin Request reports by date.

* The user can also see this report in the chart view.

* Here the user has download option to download this reports.

**Admin Reports > Contract Renewal Request**

* * This Contract Renewal Request menu page shows the list of Contract Renewal Request Reports.

* The Contract Renewal Request Reports page shows the details under the fields of `Customer Id, Project Id, Created By, Created Date, URL, Method, Request Body, Header, Response, Status, Comments and Method Name.`

* Here the filter is also available to filter the Contract Renewal Request reports by date.

* The user can also see this report in the chart view.

* Here the user has download option to download this reports.