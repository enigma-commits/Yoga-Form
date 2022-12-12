# Yoga-Form

Hosted Site Link:-https://6396c561a84ec4442b03c043--yoga-form-app.netlify.app/

This project is created in **MERN** stack. 
All the frontend is designed using **react**.
Backend is designed using **NodeJS** and "Express" is used as backend framework.

All the input is taken from the user in form.
When user submits the form first of all following validation are done.
1. User must be atleast of age 18 and no more then 65.
2. Email should be valid and verified using regex.
3. Length of name should be in between 3 to 65.

** In the Payment section I have assumed we do payment for only using debit/credit card.**

Following validations are done on card.
Card number should be of length 16.
Expiry date should be valid and should be of future date from current date.
CVV of length exactly 3.

When a user enters wrong information and reaches to payment form then you can go back using edit info button.

I have assumed that we have to show the registered user as well so I have shown them as well.
