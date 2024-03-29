# SwagOfIndia E-commerce website (FrontEnd)

 https://swag-of-india-website.netlify.app

## Description 
Fully Functional E-commerce website Swag of India is a responsive e-commerce website. The technologies used in this project are HTML, CSS, Vanilla JavaScript and Bootstrap. There are a few important modules in the project like home page, image carousel, product listing page, product page, cart page, wishlist page etc. The data is accessed using ajax call and then rendered into the webpage using dynamic html template created using string literals. For cart-page we are using localstorage to temporarily storing data before clicking on the checkout button. I took almost 40 - 50 hrs to complete this project. SkillLync helped me by providing the wire-frames for all relevant feature pages


## Main Features
1. ### Country selection
On clicking on the country it gives the user the ability to choose from different country upon which the contact number and flag changes accordingly. 

2. ### Loading products from database
On clicking on the **shop now** or **view more** button the user is taken to the all-products page where the information of different products are loaded from a database via a fake server. This feature was implemented using AJAX calls and javascript. The product information in the server were stored in JSON format.  

3. ### Cart page implementations 
Within the latest section of the homepage where different products are displayed, on hovering over the mouse users can click on the cart icon and add multiple products to cart. The cart on the top navigation bar increments as the user adds products and upon clicking on it takes them to the cart page. Here. users can select their preferred size of different products and also change the quantity of order as they need. Also, users can delete products from cart permanently by clicking the remove button or add the particular product to wishlist by clicking on the add to wishlist button. When satisfied, the user can click on proceed to checkout button to go to the checkout page. 

4. ### Wishlist page implementations
Similar to add to cart, users can hover over products and click on the heart icon to add that product to wishlist. The wishlist on the top navigation bar increments as the user adds products and upon clicking on it takes them to the wishlist page. Here. users can either move their wishlist items to cart by clicking on add to cart button or remove the product from wishlist permanently by clicking on remove from wishlist button. 

5. ### Checkout page implementations
On arriving at the checkout page, users will have to pass 3 stages to place the order. First, they need to sign in successfully, second they will have to enter their address and contact information and finally they will have to choose a mode of payment. Once this is done, the user can click on the place order button to place the order successfully and the thank-you page gets displayed. If users want to go back any stage, then they need to click on the change button to make any changes. 

6. ### Profile creation and updation
The users can head to the my-profile page by clicking on the Profile on top navigation bar. Here, the user is shown their information like name, gender, email, location etc among others and the users can edit these details by clicking on the edit button which takes them to the edit-profile page. Here, users can change entire information or edit previously saved information and click on save details button to save the details. Upon doing this the user is taken back to the my-profie page where the updated details are displayed. 

## Other features
Some generic features implemented are login modal, scroll-to-top button, banner image with carousel effect, product tabs, dropdown menus, FAQ page with accordion, clickable side menus in all pages, seller page, related products carousel effect, hamburger menu for small screens and tablets.

## Coding Best Practises Used
* DRY (Do Not Repeat Yourself)
* Clean, readable and organised code
* Comments describing functions and code blocks
* Re-used code as much as possible

## Future Work
* Password hide/show feature
* Adding buttons for cart, wishlist and product view for phones and tablets instead of hovering icons
* Connecting Facebook, Twitter, Gmail API for login
* Creating a backend and database and connecting the front end with it to create a full fledged e-commerce website.
