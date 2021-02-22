# Use Cases    
## 1. User Sign-in/Sign-up:
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

## 2. User Browsing Flow:
    - Action: Logged-in User clicks on the link 'Shop' on their nav bar
    - Reaction: Server renders the store's homepage. Various products are featured, users can browse by category, do a search, see 'featured' products etc.

    - Action: User navigates the store until they find a product they want to buy.
    From here, the user can click on the product to see the product details,
    or they can add the product to their cart directly from the preview.
    - Reaction: 
