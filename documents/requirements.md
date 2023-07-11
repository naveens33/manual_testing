### Requirement ID: 378

Name: Transfer Amount (Within Own Accounts)

Description:
Users have the ability to transfer funds between their own accounts. Upon selecting the Transfer option from the Menu bar, the Transfer page will be displayed. By choosing the "Own Account" radio button, users can view their own account details. They can then click on any account to which they want to transfer the amount. Once the account is selected, users will be directed to the Payment Information page, where they can provide the following details:
- From account (dropdown)
- To account (disabled)
- Amount (text field)
- Message (text field)
- Cancel button
- Confirm button

Users can confirm the payment after entering the necessary information. If the payment is successful, the message "Payment Successful" will be displayed.

Note:
- Only valid transactions are permitted.
- Invalid transactions, such as transferring a larger amount from an account with insufficient balance, will result in an "Insufficient Balance" error.
- If a user selects an account from the list, that account will be disabled in the Payment Information section, and it will not appear in the "from account" dropdown menu.

### Requirement ID: 379

Name: Car Loan EMI Calculator

Description:
Users are provided with an option to calculate the EMI for a car loan. Within the Loans menu, there will be a Car Loan tile displayed. By clicking on "Apply Now," users will be directed to the car loan section. In this section, they will find the following sliders to select and calculate the EMI amount:

Loan Amount Slider (Minimum Rs. 1,00,000 - Maximum Rs. 7,00,000)
Interest Rate Slider (Minimum 8.05% - Maximum 12.5%)
Loan Tenure Slider (Minimum 1 Year - Maximum 7 Years)
Processing Fee Text Field
Calculate Button
By providing all the required details, the corresponding EMI amount will be calculated.

Sample Data:    

Loan Amount (P) = Rs. 2,00,000
Interest Rate (Annual) = 10.5%
Loan Tenure (Years) = 5
Processing Fee = Rs. 100
EMI = Rs. 4399

### Requirement ID: 380

Name: Forgot Password

Description:
Users have the option to reset their password. On the login page, there is a "Forgot your password?" question displayed. By clicking on it, users are directed to the Forgot Password page. Here, users can enter their email ID, answer the captcha question, and click on "Send Password."

Only if the user answers the captcha correctly, the "Send Password" button will be enabled. Once the email ID and captcha are successfully validated, the message "We've sent an email to [email address] with instructions. If the email doesn't show up soon, please check your spam folder." will be displayed.