# BigCommerce Test #

## Changes Made ## 

* Added parameter hover="true" in card.html
* Added script in responsive-img.html to manage hover class and display appropriate image.
* Included Jquery in responsive-img.html
* Included Jquery in category.html
* Added script in category.html.
  *	Added script to add all items in category
    * Script queries GraphQL API for all items in category
    * Script creates add to cart URLs for each object and async adds them all
    * Script displays message for the user alerting that all items in category have been added to the cart.
  * Added script to remove all items from cart
    * Script checks to see if there are items in the cart. If so, displays button to remove all.
    * Script queries Storefront API for all items in cart
    * Script async removes every item and reloads page
    * Script displays message for the user alerting that all items have been removed
* Added span in navigation.html to include customer's name in header if user is logged in.

## Temporary Store URL ##
https://gilson-trial.mybigcommerce.com/?ctk=1c6dd0b2-caaf-4237-a303-5d17aa40632a

Temporary access code: knoo1x8865
