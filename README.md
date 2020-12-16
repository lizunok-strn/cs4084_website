# CS4084 Mobile Application Development
## Introduction
Jelizaveta Lapteva (18229225)
Cathal Kelly (18244513)
John Maguire (18250076)
Alannah Ryan (18232132)

We have decided to create a budgeting app that would be useful to monitor spendings and manage savings in a unique and efficient way. We will allow for the user to input income and expenditure, allowing the app to show them where they can afford to save some money. The user could set up a savings percentage that will be taken from the income and recorded in their savings account. This means that when the user puts in an income figure of their choice, that will then be taken from the income and automatically put into the savings figure.
We are hoping to be able to show a graph where you can see what months you have saved more money than others as well as show the change in expenses.
This app could also allow pictures to be saved and linked to specific transactions, i.e. receipts of purchase. Firebase Realtime Database would be useful for this feature.
We will also be making a search function to allow users to search through their transactions for specific entries, possibly using string comparison between the searched term(s) and the entry titles in our income/expenditure.
We would like to have an option of separating our savings and setting specific goals. Eg: we could have our regular savings (i.e. for a rainy day) while also having a separate figure for different, more specific events. This would be very helpful to manage saving with a certain goal in mind,e.g: for a new car.

## Technical Design
We use firebase firestore and firebase auth for this project. We also intended to use the camera to save images to firebase storage but due to time constraints this was not possible. We chose these options due to their convenience plus out experience with them.

We learned a lot from this project, we learned that time management is incredibly important and it is always important to be in contact with the other members of the team, to see if they are pulling their weight.This is especially important near the end of the project, so that as little as possible crunch is needed.

We also learned how to accurately measure your own abilities, not overpromising and knowing what we are capable.

As you can see from the introduction a lot of things had to be left out in the end. This is due to those issues mentioned above, culminating in an overwhelming,frusrating experience

## Structure
After entering the app, you sign in using an email and secure password, can also save these for easier access. From there you have the option between inputting expenses and viewing expenses. If you click into the input expenses you are able to input any value into the text box provided, and by clicking the camera button you can take a picture of the receipt. From there you can save it, bringing you back to the previous screen, saving the details to the database. From there you can either input more expenses or click view expenses, being able to view your previous expenses, unique to the users account.

## Copyright and License

Copyright 2013-2020 Start Bootstrap LLC. Code released under the [MIT](https://github.com/StartBootstrap/startbootstrap-new-age/blob/gh-pages/LICENSE) license.
