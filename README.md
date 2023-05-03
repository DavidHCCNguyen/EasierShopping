# EazyShopping

### Group Project: Web Application

## USER STORY
```
AS A regular online shopper,
I WANT to purchase my favorite items from the convenience of my home,
SO THAT I can engage in other tasks.
```

## ACCEPTANCE CRITERIA
```
WHEN I open the application,
THEN the login page should display and will have an option to login via member or as guest.

WHEN I attempt to type-in my details to log in/sign up to the application,
THEN the input field should include an Auto-complete function as a regular shopper.

WHEN I open the application,
THEN I am presented with the products on offer, each product with its respective image and description.

WHEN I click on a product of interest,
THEN application should automatically create a new list of shopping items or add to an already existing list to the right of the window.

WHEN I accidentally leave the application and return,
THEN I am presented with my existing list of shopping items, without the need to start shopping from the beginning.

WHEN I decided to change my order,
THEN I am able to delete the item as there is a remove button option to do so.

WHEN I have completed my shopping,
THEN I can click the proceed to checkout button and a modal will appear that my purchase was completed.
```

## Table of Contents
- [EazyShopping](#eazyshopping)
    - [Group Project: Web Application](#group-project-web-application)
  - [USER STORY](#user-story)
  - [ACCEPTANCE CRITERIA](#acceptance-criteria)
  - [Table of Contents](#table-of-contents)
  - [Project Description](#project-description)
  - [Features and its Screenshots](#features-and-its-screenshots)
  - [Installation and Usage](#installation-and-usage)
  - [Technologies Used](#technologies-used)
  - [Task Breakdown](#task-breakdown)
  - [Live Site and Repository](#live-site-and-repository)
  - [References and Credits](#references-and-credits)
  - [License](#license)
  - [Authors](#authors)
  
## Project Description
```
The goal of this project is to create a user-friendly online shopping application that enables regular online shoppers to purchase their favorite items from the convenience of their homes. The application will have a login page that allows users to sign in as members or as guests. 

Upon signing in, users will be presented with a list of products on offer, each with its respective image and description. The application will include an auto-complete function for regular shoppers, which will save them time and effort when typing in their details to log in or sign up. 

When users click on a product of interest, the application will automatically create a new list of shopping items or add to an already existing list to the right of the window. If the user accidentally leaves the application and returns, they will be presented with their existing list of shopping items without needing to start shopping from the beginning.

The application will also allow users to change their order by deleting items using a remove button option. Once the user has completed their shopping, they can click the proceed to checkout button and a modal will appear to confirm their purchase was completed successfully.

Overall, this project aims to improve the online shopping experience for regular shoppers by making the process more efficient, convenient, and user-friendly.
```

## Features and its Screenshots
- When opening the application, this is what the user will see. The user can be a member, guest or can join up to be a member.
  <img width="1119" alt="login" src="https://user-images.githubusercontent.com/122607160/235833314-25aeb70f-993c-4af3-9bab-cd5ba57eee8c.png">


- The main page once you sign in
  <img width="1664" alt="mainpage" src="https://user-images.githubusercontent.com/122607160/235851906-81ee1b5b-d9f2-45d0-8b57-b2f108a4b0ce.png">


- Adding the items and will show the local storage. Tested that when you close the web application, the items will be still in the cart.
<img width="1807" alt="localstorage" src="https://user-images.githubusercontent.com/122607160/235851566-752325d7-14ac-43a3-9907-4e1fc45687d1.png">


- Proceed to Checkout with modal
  ![checkout](https://user-images.githubusercontent.com/122607160/235833317-42740fa3-2ffa-4be9-9cd8-c24c6cac16a8.png)

## Installation and Usage
- We cloned the [David](https://github.com/DavidHCCNguyen/EazyShopping)'s repository which is the main branch in on our local machine.
- The remaining members - [Kana](https://github.com/anayoifediora), [Kristine](https://github.com/mcramileux), and [Maya](https://github.com/retnodamayanti), made our own feature branches to create our task and push them once it is done.
- Open VSCode to write the code.
  - For alternative, open Chrome DevTools by pressing the shortcuts:
  - For Windows and Linux: Ctrl + Shift + J
  - For MacOS: Command + Option + J
- Chrome DevTools Application to check local storage. 

## Technologies Used
- HTML and CSS
- CSS Foundation
- Foundation Blocks
- Necolas' Normalize CSS
- Google Fonts
- JavaScript
- JQuery
- W3Schools
- Fake Store API
- GoogleMaps API
- MDN web docs
  
## Task Breakdown
- David
    - Created two HTMLs - one for logging in and signing up. 
    - Created the basic css looks for it and also used a foundation for it so it fits the theme of the main page html. 
    - Found a map API and used it to show Australia for the users to use for if they forget where some of their stores are located within this EazyShopping website/app.
  
- Kana
    - Accessed the Fakestore Side API to fetch product data. 
    - Ensured product data (including image, price and rating) displayed on the home page. 
    - Worked on the checkout cart to display the selected products when the "add to cart" button is picked
    - Created the checkout message as a modal.
    - Wrote the User Story and Acceptance Criteria.
  
- Kristine
    - Created the HTML and CSS part of the header and footer.
    - Created the Responsiveness of the navigation bar.
    - Edited READme section and presentation.
  
- Maya
   - Added ID attribute to the button and event listener on the add to cart button.
   - Added item to local storage and display it on the cart, added remove button,
  
## Live Site and Repository
- For finish product, go to this link: https://davidhccnguyen.github.io/EasierShopping/
- Group Repository: https://github.com/DavidHCCNguyen/EasierShopping

## References and Credits
- Necolas' [Normalize.css](https://github.com/necolas/normalize.css) for better view for small, medium and large screens.
- [Foundation CSS Framework](https://get.foundation/sites/docs/installation.html).
- [Foundation's Building Blocks](https://get.foundation/building-blocks/).
- [W3S](https://www.w3schools.com/css/) for more css techniques.
- [Chat.GPT](https://chat.openai.com/) for clearer explanation on creating our web application.
- [MDN Web Docs](https://developer.mozilla.org/en-US/docs/Web/JavaScript) javascript documentation.
- [FakeStore API](https://fakestoreapi.com/docs) for e-commerce products
- [GoogleMaps API](https://developers.google.com/maps/documentation/javascript/get-api-key) for location

## License
- This project is [MIT](https://choosealicense.com/licenses/mit/) license.

## Authors
- © 2023 
- [David](https://github.com/DavidHCCNguyen)
- [Kana](https://github.com/anayoifediora) 
- [Kristine](https://github.com/mcramileux)
- [Maya](https://github.com/retnodamayanti)
