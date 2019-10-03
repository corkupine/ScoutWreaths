# ScoutWreaths
Site to sell wreaths for BSA fundraising

Site is hosted on github pages - no hosting necessary

https://corkupine.github.io/ScoutWreaths/ is the actual URL

http://cantonbsawreaths.org/ redirects to github pages

Managing The Site

You can edit everything in the UI here on github.com! 

* Update flyer.pdf to reflect current items/pricing
* Edit open.html to reflect the upcoming sales season
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

The site automatically loads index.html when you visit, so:
* To open site: rename index.html to closed.html, and rename open.html to index.html 
* To close site: rename index.html to open.html, and rename closed.html to index.html 
