# Test Cases - SauceDemo

## TC001 Verify user can login with valid credentials
Requirements: REQ-001

Precondition:
User has access to the SauceDemo website

Steps:
1. Open https://www.saucedemo.com
2. Enter username: standard_user
3. Enter password: secret_sauce
4. Click Login button

Expected Result:
User is redirected to the Products page

## TC002 Verify user cannot login with invalid password
Requirements: REQ-002

Precondition:
User is on the Login page

Steps:
1. Enter username: standard_user
2. Enter password: secrete_sauc
3. Click Login button

Expected Result:
Error message displayed indicating invalid credentials

## TC003 Verify locked user cannot login
Requirement: REQ-003

Precondition: User is on the Login page

Steps:
1. Enter username: locked_out_user
2. Enter password: secrete_sauce
3. Click Login button

Expected Result:
A message displayed stating that the user is locked out

## TC004 Verify product list is displayed after log in
Requirement: REQ-004

Precondition:
User is on the login page

Steps:
1. Enter username: standard_user
2. Enter password: secret_sauce
3. Click Login button
 
Ecpected result:
The user is redirected to the product page and all products are displayed with name, image and price

## TC005 Verify product can be added to cart
Requirement: REQ-005

Precondition:
User is on the product page and all products are displayed with name, details, image, price and "Add to cart" button

Steps:
1. Click the "Add to cart" button for a product

Expected result:
The product was added successfully to the shopping cart

## TC006 Verify cart page loads correctly
Requirement: REQ-007

Precondition:
User is on the product page

Steps:
1. Click the Cart icon in the right top corner

Expected result:
The Cart page opened and displays the cart items

## TC007 Verify product can be removed from cart
Requirement: REQ-006

Precondition:
User is on the Cart page and at least one product is added to the cart.

Steps:
1. Click the "Remove" button

Expected result:
The product is removed successfuly from the cart and no longer appears in the cart list

## TC008 Verify checkout process
Requirement: REQ-008

Precondition:
User is on the Cart page and at least one item is added to the Cart

Steps:
1. Click Checkout button 

Expected result:
The Checkout Information page is displayed with First Name, Last Name and Zip/Postal Code

## TC009 Verify checkout information fields accept input
Requirement: REQ-009

Steps:
1. Enter a valid First Name
2. Enter a valid Last Name
3. Enter a valid Postal Code

Expected result:
The fields accept the entered information

## TC010 Verify checkout information submission
Requirement: REQ-010

Precondition:
User is on the Checkout Information page

Steps:
1. Enter First Name: Anastasia
2. Enter Last Name: Dragoman
3. Enter Postal Code: 34787
4. Click the Continue button

Expected result:
The Checkout Overview page is displayed with the following information:
Quantity and Description for each item
Payment Information 
Shipping Information 
Price Total

## TC011 Verify order completion
Requirement: REQ-011

Precondition:
User is on the Checkout Overview page

Steps:
1. Click the Finish button

Expected result:
The Checkout Complete page is displayed with the message stating "Thank you for yout order!"

## TC012 Verify checkout validation error messages when First Name is missing
Requirement: REQ-012

Precondition: 
User is on the Checkout Information page

Steps:
1. Leave First Name field empty
2. Enter valid Last Name
3. Enter valid Postal Code
4. Click Continue button

Expected Result:
An error message is displayed indicating that the First Name field is required

## TC013 Verify checkout validation error messages when Last Name is missing
Requirement: REQ-012

Precondition: 
User is on the Checkout Information page

Steps:
1. Enter valid First Name
2. Leave Last Name field empty
3. Enter valid Postal Code
4. Click Continue

Expected Result:
Error message "Last Name is required" is displayed

## TC014 Verify user logout 
Requirement: REQ-013

Precondition:
User is logged into th system and is on product page

Steps:
1. Click the meniu icon
2. Click Logout

Expected result:
User is logged out and redirected to the Login page
