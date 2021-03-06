# Pizza 42 Front End - React App Implementing Auth0

This repository hosts a React project that defines a Single-Page Application (SPA). It runs using the similarly named backend [Pizza 42 Backend](https://github.com/kinamod/pizzaForty2-backend)

# User States
This application has *four* user tiers:  
- [Signed Up](#signed-up)  
- [Email Verified](#Email-verified)  
- [Google Account or Google Account linked](#Google-Account-or-Google-Account-Linked)  
- [Administrator](#Administrator)

## Signed Up
A signed-up user is able to view their profile data on the [Profile](https://pizzafortytwodsj.herokuapp.com/profile) page and get a generic _"Public Message"_ from the [Order Pizza](https://pizzafortytwodsj.herokuapp.com/orderpizza-api) page.
## Email Verified
If a user's email has been verified, they will also be able to order pizza from the [Order Pizza](https://pizzafortytwodsj.herokuapp.com/orderpizza-api) page.
## Google Account or Google Account Linked
If a user's Google account has been linked, they will be able to see the amount of Google connections they have, and also their gender from the [Profile](https://pizzafortytwodsj.herokuapp.com/profile) page.
## Administrator
This user is able to see and use the link that takes you to the [Users' Info](https://pizzafortytwodsj.herokuapp.com/usersinfo) page. This page simply has a graph that reflects how many Google Connections each user of the site has. _*N.B.* If there is less than 20 user’s worth of data the app randomises an extra 1000 just to make the graph look more interesting._ Informative? No, but good for a demo.


# Linked Accounts
Pizza Forty2 will ask you if you wish to link accounts if you have previously signed up with the same email address using different identity providers.
_e.g._  
- _Signing up with email address and password and then_
- _Signing up again with a Google account_  
_Will cause the system to ask if you wish to like these accounts_

# Thanks for Looking!
Besides these points there isn't a lot to this little project. Have fun viewing my React and Auth0 implementation!
