# Swag Labs Automation Testing using Selenium

# Adding Highest Price Item to the Cart

## Background: Logging in to Sauce Demo as Standard User
- **Given** I am on the Sauce Demo login page
- **When** I enter the username as "standard_user"
- **And** I enter the password as "secret_sauce"
- **And** I click on the login button

## Scenario: Adding Highest Price Item to the Cart
- **Given** I am on the products page
- **When** I click on the "ADD TO CART" button corresponding to the highest priced item
- **And** I click on the cart icon
- **Then** I should see the product successfully added

<img width="1644" alt="Cucumber Report" src="https://github.com/SriniTalla/SauceDemo/assets/22282628/d3867fa6-74b7-45ea-a537-091fb239638f">

