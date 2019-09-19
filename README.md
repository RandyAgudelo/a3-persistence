## Online Shopping Calculator

http://a3-randyagudelo.glitch.me

- This project helps the user create a shopping list where they can add, modify, and remove products as well as give the final total cost of all the products in the list
- Each user can have their own shopping list by creating their own account which allows each user to have a unique and distinct shopping list which is saved to the server
- The main challenge faced was the ability to save each users' accounts and shopping list and having the shopping list correspond to the correct user who is signed in
- The authentication strategy and database used was passport-local and lowdb which were used because it was easier to implement as I had a lack of experience using authentication strategies
- The CSS framework used was milligram as it was recommended by the Professor and it was the one that needed the least amount of changes to the CSS I originally had
- The CSS modifications I had to make were to properly space elements out to make it look better and to have an attractive background and readable headings.
- The Express middleware packages I used are passport (passport-local), body-parser, express-session, express-slash, express-debug, response-time, express-uncapitalize

- Passport was used to authenticate users using the local database 
- body-parser was used to make parsing requests easier 
- express-session was used to create a server-based session with the settings I specified 
- express-slash was used to enable strict routing and handles the routes in server with and without trailing slashes 
- express-debug was used to help me debug certain aspects of the web application by giving me additional details about variables, session, and more
- response-time was used to record the response time of requests from the server which I used to see if a request was taking longer than it was supposed to (debugging purposes)
- express-uncapitalize redirects user HTTP requests that contain uppercase letters to the same URL in lowercase letter form   
  
- Additional Notes/Comments: This web application should allow the user to create a new account and once the user has an account, they should be able to log back in sing the login. 
 Once new users have an account, they will start with an empty shopping List which they can add/modify/remove items. The modification of items is when th user decides to delete only a
 certain number of products and not all of the products. Each user has their own respective accounts and shopping list that are all unique to each user. When removing products, users are 
 expected to only remove up to the most amount of products they have in their shopping list and nothing more. **Important: When clicking the sign out, view shopping list, and the back buttons, click on 
 letters within the button to get a response.** 

## Technical Achievements
- **Having 3 seperate index.html, scripts.js**: Created a separate webpage for the user to login. Once logged in, the user will be taken to another page where they input all their data while also having the 
ability to go back to the login page by signing out. Each of the index.html files have their own script.js files with their own functionality.

- **Created a somewhat accessible web application**: Through the use of a web accessibility tool online, I was able to make my webpages more accessible through the use of labels and creating 
additional identification and details to certain html tags. I also checked the elements on the webpages and they have a good contrast making it easy to read the text with the given background.

- **User can create a new account and login with that account after**: Implemented an explicit way to allow the users to register a new account or if the user already has an account, they can log back in 


### Design/Evaluation Achievements
- **Accessibility**: I followed best practices for accessibility including using semantic HTML. There are no <div> or <span> elements in my document.
