# Use Cases    
## 1. User Sign-Up:
    - Action: User visits www.myproject.com.
    - Reaction: Server renders a form to verify users age.

    - Action: User verifies age in the window, or else is banned for rest of session.
    - Reaction: Server renders the guest homepage, with a guest navbar at the top of the page.

    - Action: User clicks the 'login/sign-up' button on the navbar.
    - Reaction: Server renders page with a form to sign up as well as a form to log in

    - Action: User enters a username, email, password, and birthday into the fields and submits.
    - Reaction: If valid, User instance is created and saved to database.
    User is then redirected home.
        - If invalid, user is redirected to form with errors displayed.

## 2. User Shopping/Browsing:
    - Action: Logged-in User clicks on the link 'Shop' on their nav bar
    - Reaction: Server renders the store's homepage. Various products are featured, users can browse by category, do a search, see 'featured' products etc.

    - Action: User navigates the store until they find a product they want to buy.
    If a user chooses, they can add an item to their cart on their search/browsing
    page, but instead they click on the item to get details on the product
    - Reaction: The server renders a page with all information available on that product for the customer to view, including user reviews. 
    
    - Action: The User clicks the 'add to cart' button after reading up.
    - Reaction: The page refreshes, the item is added to their cart both on the UI and on the server-side. A message is flashed up top to let the user know that their item was added successfully. 

    - Action: The User opens their cart, and clicks the "check out" button
    - Reaction: The server renders a page where the User can look over their current order (cart) and begin to finalize their order.

    - Action: User decides the order list looks correct, and they hit the 'continue' button at the bottom of the order summary.
    - Reaction: Server renders a page where a customer will confirm their billing information (this is framed as a pick-up order), as well as 'a phone number' for short-notice contact.

    - Action: User fills out forms properly, and the order is placed. The user is redirected home, a green flashed message appears at the top of the page that confirms their order has been placed, and will provide a link to the order details page.

## 3. User Reviewing/Rating:
    - Action: Our user has since picked up their order, and wishes to leave a review. Our user can either refer to their order history page or search it up manually anywhere on the site. Once they are on the page, reviews are listed on the bottom of the page, with newest comments showing up first. 
    There is a button at the top of the list that reads 'Write a review'.
    User clicks this button.
    - Reaction: A form is rendered for our User to write their review in. 

    - Action: The User inputs a title, a review body, and a rating. They submit the form.
    - Reaction: Assuming all inputs are valid, the review is appended to the top of the list for the next visitors to see. 

