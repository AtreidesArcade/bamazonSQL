# Week 12 homework assignment:
## Node.js & MySQL

### Introduction

* I created an Amazon-like storefront app, called Bamazon, using MySQL, the MySQL NPM Package, and the Prompt Package.
* This app takes in orders from customers and deplete from the store's total supplies.
* The app first displays a list of all of the available products, their costs, and current stock.


![Image of product display](/readMeImg/productsDisplay.png)

* The app will display the stock before your purchase, what you are buying, how many, and the unit cost.

* The app asks the following things from the user.

	1. product ID
	2. the amount the user wants to purchase

* Then it will display the total cost and ask if you want to purchase another item. 


![Image of product prompts](/readMeImg/productPrompt.png)

* The app will then decrement the quantity of the product the user selected.

![Images of Quantity and decremented quantity](readMeImg/beginningQuantity.png)
![Images of Quantity and decremented quantity](readMeImg/decrementedQuantity.png)

* These are the npm packages I used and are needed to run the app

	1. [prompt](https://www.npmjs.com/package/prompt)
	2. [mysql](https://www.npmjs.com/package/mysql)


