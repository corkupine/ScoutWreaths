# ScoutWreaths
Site to sell wreaths for BSA fundraising

Site is hosted on github pages - no hosting necessary

https://corkupine.github.io/ScoutWreaths/ is the actual URL

http://cantonbsawreaths.org/ redirects to github pages

Managing The Site

* To open site:
    * Edit open.html as directed below
    * Rename index.html to closed.html, and rename open.html to index.html 
* To close site: 
    * Edit closed.html to reflect current year
    * Rename index.html to open.html, and rename closed.html to index.html 

The site automatically loads index.html when you visit

You can edit everything in the UI here on github.com! 

Editing open.html for a new season:
* Update flyer.pdf to reflect current items/pricing
* Edit open.html to reflect the upcoming sales season
* Change year in heading
* Add buttons where old ones were
* Use https://www.paypal.com/buttons/ to generate Paypal "Add To Cart" buttons
    * Create button
        * Button type: Shopping Cart
        * Item Name: wreath32 (or similar)
        * Item ID: blank
        * Price: 40 (or similar)
        * Customize button: Add text field "Scout Name"
        * Click "Create Button"
        * There is a link to "create similar" so you don't have to retype everything
    * Insert code into html
    * Edit code to match format of last year's button code, including adding the Quantity code
