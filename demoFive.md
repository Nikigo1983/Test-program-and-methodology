# Test program and methodology 
## Scenario 1 
## Testing the user authorization form in the Glovo application
|**№**|**Actions**|**Result**|
|:-------:|:-----|:-----|
| 1 | Press the "Login" button. | Opens the user authorization form with the fields "Login (e-mail)" and "Password", as well as tips for filling in each field.|
| 2 | Fill in the fields "Login (e-mail)" and "Password" incorrectly. Press the "Login" button. | At the bottom of the authorization form pops up a window "Oops! Could not find user or incorrect password". | 
| 3 | Fill in the "Login (e-mail)" field correctly and the "Password" field incorrectly. Press the "Login" button. | At the bottom of the authorization form pops up a window "Oops! Could not find user or incorrect password". |
| 4 | Fill in the "Login (e-mail)" field incorrectly and the "Password" field correctly. Press the "Login" button. | A tooltip appears under the incorrect email address field: "Please enter a valid email address. |
| 5 | Fill in the fields "Login (e-mail)" and "Password" correctly. Press the "Login." | The user is successfully authorized by the system. A screen opens for entering the address: "Please enter a delivery address" with a "Define address" button. Switching to the test scenario 3 "Registration". |
| 6 | Field "Login (e-mail)" is left blank, the field "Password" is filled correctly. | If the field "Login (e-mail)" is empty, the system will not activate the "Login" button. |
| 7 | Fill in the "Login (e-mail)" field incorrectly, leave the "Password" field blank. | If the "Password" field is blank, the system will not activate the "Login" button. |
| 8 | Field "Login (e-mail)" is left blank, the field "Password" is filled incorrectly. | If the field "Login (e-mail)" is empty, the system will not activate the "Login" button. |
| 9 | Leave the "Login (e-mail)" field empty, leave the "Password" field empty. | If the fields "Login (e-mail)" and "Password" are empty, the system will not activate the button "Login". |
| 10 | Click on the button "Forgot your password?" | To restore the forgotten password you need to go to scenario 2 "Forgot Password". |
| 11 | Fill the "Login (e-mail)" field correctly, the field "Password" leave blank. | If the field "Password" is blank, the system will not activate the "Login" button. |