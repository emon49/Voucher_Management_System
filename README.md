# Voucher Management System

## Motivation

<p>Every company needs to maintain a voucher management system for their daily expenses. We are trying to solve this problem using our project.</p>

## Prospective Client

<p>Any company who has quite a good number of expenses to maintain in their daily routine, will be helped by this software.</p>

## Searching Options

<p>We can search based on many conditions. Some of them are as follows:</p>
 
1. The vouchers by the issuer user 
2. Total expense of a month by querying all the vouchers 
3. Total earning of a month by querying all the credit vouchers
4. View voucher details through searching by Voucher Id

## Project Structure:

### TABLES:

1. Users

   - User_ID
   - User_name
   - Password
   - email

2. Vouchers

   - Voucher_ID
   - Expense_type_id
   - User_ID

3. Expense Type

   - Expense_type_name
   - Expense_type_id

4. Voucher Details
   - voucher_id
   - Expense_sector_id
   - issue_Date
   - Description
   - Voucher_ID
   - Amount

## Schema Diagram

<img src="./Database/Schema_Diagram.jpg">
<br>

## ER Diagram

<img src=./Database/ER_Diagram.jpg>
<br>
<br>
<br>

## User Interfaces

<h3 style="text-align:center"> Welcome Screen </h3>
<img src="./UI Images/Welcome Screen.png">
<br>
<br>
<br>
<h3 style="text-align:center"> Log IN </h3>
<img src="./UI Images/LogIn.png">
<br>
<br>
<br>
<h3 style="text-align:center"> Create Voucher </h3>
<img src="./UI Images/Create Voucher.png">
<br>
<br>
<br>
<h3 style="text-align:center"> Voucher Hub </h3>
<img src="./UI Images/Viucher Hub.png">
<br>
<br>
<br>
<h3 style="text-align:center"> Search By Voucher ID </h3>
<img src="./UI Images/Search by Voucher ID.png">
<br>
<br>
<br>
<h3 style="text-align:center"> Summary </h3>
<img src="./UI Images/Summary.png">

## Tools

<a href="https://www.microsoft.com/en-us/sql-server" target="_blank"> <img src="https://www.svgrepo.com/show/303229/microsoft-sql-server-logo.svg" alt="android" width="50" height="50"/> </a>
<a href="https://netbeans.apache.org/" target="_blank"> <img src="https://okanaganwebdeveloper.com/wp-content/uploads/2015/04/20150401-icon.png" alt="android" width="40" height="40"/> </a>
