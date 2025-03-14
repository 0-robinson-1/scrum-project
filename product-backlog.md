W 100   As a customer, I would like a homepage featuring highlighted products and a list of the best-selling products so that I can entice 
        visitors
        to complete a   purchase.

W 150   As a customer, I want a visitor who is not registered to still be able to make a purchase so that I can sell as many products as 
        possible,          
        including  to new visitors of the webshop. (For non-registered visitors, a purchase can be made using only an email address.)
    
W 200   As a customer, I want to be able to register and log in so that I can manage my details and shopping cart.
            •	During registration, the password must be entered twice to avoid typing errors.
            •	If an active account already exists with the email address, the email address cannot be used again for registration. This prevents duplicate 
                accounts.
            •	Errors (email and/or password) are displayed so that users know why they cannot register or log in.
            •	Passwords are encrypted to prevent hacking.
            •	An email address that does not exist or is disabled cannot be used to log in.
            •	During registration, users must indicate whether they are an individual or a legal entity. Individuals and legal entities have different    
                fields to fill in.

W 300   As a customer, I want to see an overview of a product (a product is more than just a name) on a single page with specifications so that I 
        can order 
        the right product.

W 400   As a customer, I want the website’s color scheme to match my company’s brand identity so that the website’s branding aligns with the rest 
        of the 
        company.

W 500   As a customer, I want to order one or multiple products from the webshop.
            •	Overview of ordered items.
            •	I can only order a product that is in stock.
            •	A logged-in user can order something (data taken from the profile).
            •	A non-logged-in user can order something (data requested).

W 600   As a customer, I want to have access to a shopping cart where I can add products so that I can make a purchase.
        Once the customer is satisfied with the products in the shopping cart, the order can be placed.

        The customer can enter discount codes, which come in two types:
            •	Personal discount code (one-time use).
            •	Discount code for everyone with a start and end date.
        (When a personal discount code is entered, it must be removed from the database after use. Only one discount code can be used per order, and each discount code gives a 10% discount on the total amount.)

W 700   As a customer, I want each order to have different statuses that the logged-in user can see, so that they can check the current status of 
        the order.
             •  Ongoing.
             •  Paid.
             •  Cancelled.
             •  Preparing.
             •  On the way and delivered.
        (Each order can only have one status at a time. Every order is delivered in its entirety, and each order is delivered separately. A logged-in user who places two orders on the same day will receive two deliveries.)