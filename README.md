# UC Variable Price Module

The **UC Variable Price** module allows you to enable variable pricing for any product in your Ubercart store. Instead of a fixed price set by an administrator, customers can specify their own price when adding a product to the cart. This makes the module especially useful for donation-based websites or pay-what-you-want stores.

## Key Features
- **Customer-Defined Pricing:** Customers can set their preferred price directly on the product’s add-to-cart form.
- **Minimum and Maximum Price Control:** You can define minimum and maximum allowable prices for each product.
- **Customizable Labels:** Adjust field labels and titles to fit your store’s branding.
- **Product Class Integration:** Apply the Variable Price feature automatically to all products of a specific product class.

## How It Works
Once enabled, the module updates the product’s add-to-cart form to include a price input field. When customers specify a price, the module processes it according to the configured rules and adds the item to the shopping cart.

## Documentation
### Adding Variable Pricing to a Product
You will first need to create and save your product, before you can configure this in "Features" tab. 
1. **Edit the Product:** Navigate to the product’s **Edit** page in your store.
2. **Enable the Feature:** Go to the **Features** tab and add the **Variable Price** feature.
3. **Configure Prices:** Set optional minimum and maximum price limits.
4. **Save the Product.**

### Applying to Multiple Products
- **Use Product Classes:** Create a new product class and assign the Variable Price feature as a default setting. This ensures that all products of this class will have variable pricing enabled automatically.

### Special Behavior
- **Unique Cart Entries:** Each variable-priced product added to the cart gets a unique ID, ensuring that quantity is always set to 1, regardless of how many times the product is added.
- **Custom Cart Display:** The module modifies the quantity display in the cart. To change how the quantity appears, override the theme function `theme_varprice_qty()` in your custom theme.

By leveraging UC Variable Price, you can offer a more dynamic and flexible shopping experience, perfectly suited for donation platforms and custom-priced product sales.

## Notes

Please, be cautious and report issues in the [issue queue](https://github.com/backdrop-contrib/uc_varprice/issues).

## Drupal 7 Version

- https://www.drupal.org/project/uc_varprice

## Installation

- Install this module using the official Backdrop CMS instructions at
  https://backdropcms.org/guide/modules.

## Maintainers for Backdrop

 - [Tim Erickson](https://github.com/stpaultim)
 - Help wanted (open a PR and ping me)

## Credits

 - Port sponsored by: Simplo (https://simplo.site) by Triplo (https://triplo.co)
 - Drupal 7 version maintained by: [jrust](https://www.drupal.org/user/124030), [rszrama](https://www.drupal.org/u/rszrama)
 - Supported development of the original D7 module - [Churches Group](http://groups.drupal.org/churches) following [these specs](https://groups.drupal.org/node/19981). 

## LICENSE

This project is GPL v2 software. See the LICENSE.txt file in this directory for
complete text.
