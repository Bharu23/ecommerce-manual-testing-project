-----------------------------------------------Test Cases – E-Commerce Web Application-------------------------------------------------------------

 1. Registration Test Cases

| Test Case ID | Test Scenario                        | Preconditions                  | Test Steps                                                              | Expected Result                                        | Status       |
| ------------ | ------------------------------------ | ------------------------------ | ----------------------------------------------------------------------- | ------------------------------------------------------ | ------------ |
| TC-REG-001   | Register with valid details          | Registration page is available | Enter valid name, email, password and required details → Click Register | User should be registered successfully                 | Not Executed |
| TC-REG-002   | Register with existing email         | Email is already registered    | Enter existing email with valid details → Click Register                | Appropriate error message should be displayed          | Not Executed |
| TC-REG-003   | Register with invalid email          | Registration page is available | Enter invalid email format → Submit                                     | Email validation message should be displayed           | Not Executed |
| TC-REG-004   | Register with blank mandatory fields | Registration page is available | Leave mandatory fields blank → Click Register                           | Required field validation messages should be displayed | Not Executed |
| TC-REG-005   | Verify password confirmation         | Registration page is available | Enter different values in password and confirm password                 | Password mismatch message should be displayed          | Not Executed |

 2. Login Test Cases

| Test Case ID | Test Scenario                     | Preconditions           | Test Steps                                                    | Expected Result                               | Status       |
| ------------ | --------------------------------- | ----------------------- | ------------------------------------------------------------- | --------------------------------------------- | ------------ |
| TC-LOG-001   | Login with valid credentials      | Registered user exists  | Enter valid username/email and password → Click Login         | User should be logged in successfully         | Not Executed |
| TC-LOG-002   | Login with invalid username/email | Login page is available | Enter invalid username/email and valid password → Click Login | Appropriate error message should be displayed | Not Executed |
| TC-LOG-003   | Login with incorrect password     | Registered user exists  | Enter valid username/email and incorrect password             | Login should fail with an appropriate message | Not Executed |
| TC-LOG-004   | Login with blank fields           | Login page is available | Leave username/email and password blank → Click Login         | Required field validation should be displayed | Not Executed |
| TC-LOG-005   | Verify password masking           | Login page is available | Enter password in password field                              | Password should be masked                     | Not Executed |

3. Product Search Test Cases

| Test Case ID | Test Scenario                     | Preconditions             | Test Steps                                 | Expected Result                                      | Status       |
| ------------ | --------------------------------- | ------------------------- | ------------------------------------------ | ---------------------------------------------------- | ------------ |
| TC-SRC-001   | Search using valid product name   | Application is accessible | Enter valid product name → Click Search    | Relevant product results should be displayed         | Not Executed |
| TC-SRC-002   | Search using invalid product name | Application is accessible | Enter an unavailable product name → Search | No-result message should be displayed                | Not Executed |
| TC-SRC-003   | Search using partial product name | Application is accessible | Enter partial product name → Search        | Relevant matching results should be displayed        | Not Executed |
| TC-SRC-004   | Search with blank field           | Application is accessible | Leave search field blank → Click Search    | Appropriate validation or result should be displayed | Not Executed |

4. Product Details Test Cases

| Test Case ID | Test Scenario          | Preconditions                     | Test Steps                           | Expected Result                               | Status       |
| ------------ | ---------------------- | --------------------------------- | ------------------------------------ | --------------------------------------------- | ------------ |
| TC-PDT-001   | Verify product details | Product is available              | Select a product from search results | Product details should be displayed correctly | Not Executed |
| TC-PDT-002   | Verify product name    | Product details page is available | Open a product                       | Correct product name should be displayed      | Not Executed |
| TC-PDT-003   | Verify product price   | Product details page is available | Open a product                       | Correct product price should be displayed     | Not Executed |
| TC-PDT-004   | Verify product image   | Product details page is available | Open a product                       | Product image should be displayed correctly   | Not Executed |
| TC-PDT-005   | Verify Add to Cart     | Product details page is available | Click Add to Cart                    | Product should be added to the cart           | Not Executed |

 5. Shopping Cart Test Cases

| Test Case ID | Test Scenario           | Preconditions          | Test Steps                         | Expected Result                                 | Status       |
| ------------ | ----------------------- | ---------------------- | ---------------------------------- | ----------------------------------------------- | ------------ |
| TC-CART-001  | Add product to cart     | Product is available   | Select product → Click Add to Cart | Product should be added to cart                 | Not Executed |
| TC-CART-002  | Add multiple products   | Products are available | Add multiple products to cart      | All selected products should appear in cart     | Not Executed |
| TC-CART-003  | Update product quantity | Product exists in cart | Change product quantity            | Cart quantity and total should update correctly | Not Executed |
| TC-CART-004  | Remove product          | Product exists in cart | Click Remove/Delete                | Product should be removed from cart             | Not Executed |
| TC-CART-005  | Verify cart total       | Products exist in cart | View cart                          | Total should be calculated correctly            | Not Executed |

 6. Checkout Test Cases

| Test Case ID | Test Scenario                        | Preconditions                      | Test Steps                              | Expected Result                                           | Status       |
| ------------ | ------------------------------------ | ---------------------------------- | --------------------------------------- | --------------------------------------------------------- | ------------ |
| TC-CHK-001   | Proceed to checkout                  | Product exists in cart             | Open cart → Click Checkout              | User should be taken to checkout page                     | Not Executed |
| TC-CHK-002   | Checkout with valid details          | Checkout page is available         | Enter valid required details → Continue | User should proceed successfully                          | Not Executed |
| TC-CHK-003   | Checkout with blank mandatory fields | Checkout page is available         | Leave mandatory fields blank → Continue | Required field validation should be displayed             | Not Executed |
| TC-CHK-004   | Verify order summary                 | Product exists in cart             | Proceed to checkout                     | Product, quantity and total should be displayed correctly | Not Executed |
| TC-CHK-005   | Verify order confirmation            | Valid checkout details are entered | Complete the order                      | Order confirmation should be displayed                    | Not Executed |

7. Logout Test Cases

| Test Case ID | Test Scenario                      | Preconditions       | Test Steps                     | Expected Result                                                   | Status       |
| ------------ | ---------------------------------- | ------------------- | ------------------------------ | ----------------------------------------------------------------- | ------------ |
| TC-OUT-001   | Logout from application            | User is logged in   | Click Logout                   | User should be logged out successfully                            | Not Executed |
| TC-OUT-002   | Verify redirect after logout       | User is logged in   | Click Logout                   | User should be redirected to the appropriate page                 | Not Executed |
| TC-OUT-003   | Access protected page after logout | User has logged out | Try to access a protected page | User should not be able to access protected content without login | Not Executed |

 Test Execution Status

The test cases will be executed against the selected e-commerce web application.

Possible execution statuses:

* Pass
* Fail
* Blocked
* Not Executed

-------------------------------------------------------Note-----------------------------------------------

Actual execution results, defects, screenshots, and evidence will be updated after testing the application.

-----------------------------------------------------------------------------------------------------------
