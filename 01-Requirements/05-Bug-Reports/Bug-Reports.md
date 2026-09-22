Bug Reports – E-Commerce Web Application

1. Bug Report Overview

This document contains the defects identified during testing of the e-commerce web application.

Each defect is documented with relevant information to support investigation, resolution, retesting, and tracking.

2. Defect Report Format

| Field              | Description                                       |
| ------------------ | ------------------------------------------------- |
| Bug ID             | Unique identifier for the defect                  |
| Module             | Application module where the defect was found     |
| Title              | Short description of the defect                   |
| Severity           | Impact of the defect on the application           |
| Priority           | Urgency for fixing the defect                     |
| Preconditions      | Conditions required before reproducing the defect |
| Steps to Reproduce | Steps required to reproduce the defect            |
| Expected Result    | Expected application behavior                     |
| Actual Result      | Actual application behavior                       |
| Status             | Current defect status                             |

 3. Defect Severity

Critical – Application or major functionality is completely unavailable.
High     – Major functionality is affected and the user cannot complete an important task.
Medium   – Functionality is affected but a workaround may be available.
low      – Minor issue with limited functional impact.

4. Defect Priority

High     – Requires immediate attention.
Medium   – Should be fixed in the planned release.
Low      – Can be fixed later based on priority.

5. Defect Status

Possible defect statuses:

* New
* Assigned
* Open
* Fixed
* Retest
* Reopened
* Closed
* Deferred

6. Defect Reports

BUG-001

| Field              | Details                                                          |
| ------------------ | ---------------------------------------------------------------- |
| Bug ID             | BUG-001                                                          |
| Module             | Login                                                            |
| Title              | Login validation issue                                           |
| Severity           | Medium                                                           |
| Priority           | Medium                                                           |
| Preconditions      | User is on the login page                                        |
| Steps to Reproduce | 1. Open login page  2. Enter invalid credentials  3. Click Login |
| Expected Result    | Appropriate error message should be displayed                    |
| Actual Result      | To be updated after actual execution                             |
| Status             | Not Executed                                                     |

 BUG-002

| Field              | Details                                            |
| ------------------ | -------------------------------------------------- |
| Bug ID             | BUG-002                                            |
| Module             | Product Search                                     |
| Title              | Search result validation issue                     |
| Severity           | Medium                                             |
| Priority           | Medium                                             |
| Preconditions      | User is on the product search page                 |
| Steps to Reproduce | 1. Enter an invalid product name  2. Click Search  |
| Expected Result    | Appropriate no-results message should be displayed |
| Actual Result      | To be updated after actual execution               |
| Status             | Not Executed                                       |

BUG-003

| Field              | Details                                                                       |
| ------------------ | ----------------------------------------------------------------------------- |
| Bug ID             | BUG-003                                                                       |
| Module             | Shopping Cart                                                                 |
| Title              | Cart quantity calculation issue                                               |
| Severity           | High                                                                          |
| Priority           | High                                                                          |
| Preconditions      | Product is available in the shopping cart                                     |
| Steps to Reproduce | 1. Add a product to the cart  2. Increase quantity  3. Check the total amount |
| Expected Result    | Cart total should be updated according to the selected quantity               |
| Actual Result      | To be updated after actual execution                                          |
| Status             | Not Executed                                                                  |

 BUG-004

| Field              | Details                                                         |
| ------------------ | --------------------------------------------------------------- |
| Bug ID             | BUG-004                                                         |
| Module             | Checkout                                                        |
| Title              | Mandatory field validation issue                                |
| Severity           | High                                                            |
| Priority           | High                                                            |
| Preconditions      | User is on the checkout page                                    |
| Steps to Reproduce | 1. Leave a mandatory field blank  2. Click Continue/Place Order |
| Expected Result    | Appropriate validation message should be displayed              |
| Actual Result      | To be updated after actual execution                            |
| Status             | Not Executed                                                    |

 7. Important Note

The above defect records are  sample defect templates for the portfolio project.

They must not be presented as confirmed defects until they are actually reproduced during test execution.

After testing the selected application, the Actual Result, evidence, severity, priority, and status will be updated based on the observed behavior.
