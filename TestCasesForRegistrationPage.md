## In this markdown file, we have discussed how to create awesome testcases for Registration Page

Test Cases for a registration page is one of the most commonly asked interview questions during software testing interviews. Since registration functionality is a fairly common feature in most of the applications, the interviewer can directly ask this question to check the ability of the tester to create test cases. without needing to explain the application.

### Following are some of the steps which we can follow to do create awesome test cases for our registration page:

* First of all, Verify that all the specified fields are present on the registration page.
* Then, Verify that the required/mandatory fields are marked with * against the field.
* Now, for better user interface dropdowns, radio buttons and checkboxes, etc fields are displayed wherever possible instead of just text boxes.
* The next step is to verify that the page has both submit and cancel/reset buttons at the end.
* Now comes the crucial step, verify that clicking submits button after entering all the required fields, submits the data to the server.
* Verify that not filling the mandatory fields and clicking the submit button will lead to a validation error.
* Verify that clicking cancels/reset button after entering all the required fields, cancels the submit request, and reset all the fields.
* To avoid invalid inputs, Check the upper limit of the textboxes.
* Similarly, Check validation on the date and email fields (only valid dates and valid email Ids should be allowed) and numeric fields by entering alphabets and special     characters.
* Verify that entering blank spaces on mandatory fields leads to the validation error.
* Now comes the crucial step which should not be ignored at all, verify that after making a request to the server and then sending the same request again with the same unique key will lead to the server-side validation error.
* Also, to remove extraspace, verify that leading and trailing spaces are trimmed.


### These were the crucial steps to be followed to make your registration page more user friendly, and error-free.

### Hope you gained a lot of insights and ideas to make a proper portal.



