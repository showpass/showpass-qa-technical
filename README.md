# Showpass QA Engineer Technical

Welcome to the Showpass QA Engineer Technical Challenge! In this challenge, we invite you to showcase your scripting skills by creating a sample script project to verify our checkout process. To get started, please fork this repository and make your changes there. You have the freedom to choose any language or framework for your project. However, during the evaluation, we will inquire about the reasons behind your choices.

## Part 1: Verifying the Ticket Buying Process
To begin, set up a test script project that validates the ticket buying process. You can access our staging environment by visiting [https://beta.showpass.com](https://beta.showpass.com). Within this environment, you can explore various events, all of which are test events, so there's no need to worry about purchasing real tickets.

To verify the ticket buying process, go to [https://beta.showpass.com/conference-october-2023/](https://beta.showpass.com/conference-october-2023/) or search for "Conference October 2023" on the application. Proceed to purchase tickets for this event. For the purpose of this project, you can use credit card as the payment method. To process the payment, feel free to use the test card numbers listed on this page: https://stripe.com/docs/testing. Once you reach the checkout confirmation page and can access your tickets, consider the transaction successful.

## Part 2: Testing Another Front-end Framework
In addition to the previous task, we have another page that allows ticket purchases. However, this page is built using a different front-end framework. You can access it at [https://beta.showpass.com/e/conference-october-2023/](https://beta.showpass.com/e/conference-october-2023/). Identify the modifications needed in your script to ensure the verification process works correctly on this page. Implement these changes in a separate test file.

## Part 3: Analysis
Please include your answers to the following question in a separate file at the root of the repository.

- Based on your observations of the purchase and checkout flow, identify at least two other aspects that you believe should be automated. Explain why you think automation would be beneficial in these cases.


We appreciate your efforts and look forward to reviewing your submission. If you have any questions or need further clarification, don't hesitate to reach out. Good luck!
