##Learn to use github: 

    https://github.com/codeschool

###TODO: (Add future features here)

    - PayPal integration
    - Wishlist
    - Raincheck
    
#Ch24\_guitar\_shop project

ch24 guitar shop is a multi person project.

Project consists of two parts and extra credit

**FIRST PART**

**To be deposited in First DropBox**

 Begin with the code in the book\_apps/ch24\_guitar\_shop. You will need PHPMailer to complete this project. Execute ch24\_guitar\_shop. Understand the logic of the program.  Determine and code for:

1. Best place to put logic to send e-mail to customer. Code the logic.  This should be sent only one-time for each order customer makes. 50 percent
  - Stating name of company. 
  - Thanking customer for order.
  - Stating what was ordered.
  - How much was ordered.
  - Price of each item.
  - Total cost of order
2. Change database to hold inventory of each item.  Either in existing table or create new table. 30 percent

 - You may have to adjust areas in program that access the table that you selected to contain the inventory.

3. Everytime a successful payment occurs with credit card - update running inventory for each item on order 20 percent.


**If you elect to do the EXTRA CREDIT, this may impact the way you handle inventory.**

**Second Part**

**To be deposited in Second DropBox**

Create a shipping department.

Put an application together that will:

- Screen shows all orders that have been shipped. **30 percent**
- Screen shows all orders that have not been shipped. **30 percent**
- Allow selection of an order to ship from this list **20 percent**
- Print out shipping document to include: **20 percent**
- Order number, Customer, Ship to, all items and quantities



**EXTRA CREDIT 5 points to final grade**

**To be deposited in Extra credit DropBox**

Keep track of inventory –

We need actual inventory and we also need to know pending shipments (customer has paid but item has not been shipped) . A message needs to be sent to the order screen if a customer is ordering a quantity of an item that will bring the inventory below zero. This includes the pending shipments.

A shipped item from the Second Part will deplete the actual inventory and pending orders. A successful payment from the first part will increase the pending orders.

**Something to think about**

To finish the cycle -  You may want to think about ordering the product and increasing inventory levels.