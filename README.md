# ReactJS Card Challenge
A responsive card based design, to be implemented by React &amp; Redux

## Introduction 
In this challenge, you are going to develop a reactJS responsive web application which shows a 
random card on the page and has a 'Try' button. Whenever the user clicks on the 'Try' button, 
you should show him another card. (Order of the cards does not matter).

Each card has at least 2 items:
- title
- description

We have different Cards which are shown differently:

- **Picture Card** which shows a picture at the end of card content (code is 0)
- **Animated Card** which uses a special animation when it is shown (code is 1) (Use a good animation of your choice)
- **Sound Card** which plays a sound when the card is shown (code is 2)

Cards can be shown in different themes (meaning they are based on a different template), icon and color representing their tag:

- sport
- art
- fun

You can choose your desired template, icon and color for each theme.

Use the following URL to initialize the card list: [http://static.pushe.co/challenge/json](http://static.pushe.co/challenge/json).
Application state and data, fetched from the server, should be managed by **Redux**.

User is able to edit the title and description text on the cards and save it (just saved it locally, 
no need to send the saved data to the server). After hitting 'Try' button several times, when visiting the 
same card again: the saved text should be shown instead of the original server text (for both title and description).

## Expectations

We expect a clean, readable and maintainable code with meaningful comments and js docs.

## Estimation

After reading and understanding the challenge and all of expectations, estimate the challenge 
development cost, send us your time cost estimation and your reasoning on how you've estimated 
this. **Please do not start development before getting a confirmation from us**.

## Task

1. Fork this repository (if you don't know how to do that, Google is your friend)
2. Develop the given challenge
3. Commit and Push your code to your new repository
3. Send us a pull request, we will review your code and get back to you
