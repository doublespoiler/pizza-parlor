# Pizza Parlor

#### By Skylan Lew

#### _{Brief description of application}_

## Technologies Used

* HTML
* CSS
* Javascript
* Bootstrap

## Description

_{This is a detailed description of your application. Give as much detail as needed to explain what the application does as well as any other information you want users or other developers to have.}_

## Setup/Installation Requirements

* _This is a great place_
* _to list setup instructions_
* _in a simple_
* _easy-to-understand_
* _format_



## Tests


## Known Bugs

* _Any known issues_
* _should go here_

## License

[GNU GPL3.0](https://choosealicense.com/licenses/gpl-3.0/)

Copyright (c) 2022 Skylan Lew



Describe Pizza()

Test 1: It should return a Pizza object with one property for size string, one for cheese string, one for toppings array, one for other array.
Code: const myPizza = new Pizza("medium", "normal", ["pepperoni", "hot peppers"], ["millennia-cake", "popplers-cup"]);
Expected Output: Pizza{size: "medium," cheese: "normal", toppings: ["pepperoni", "hot-peppers"], other:["millennia-cake", "popplers-cup"]};


Describe Pizza.prototype.totalCost()

Test 1: It should return a number that is the tax that will be added to the total purchase. Tax is 17.25%cost + 2.5 
Code: const myPizza = new Pizza();
myPizza.totalCost();
Expected Result: 2.5

Test 2: It should return a number (price) that considers the size of the pizza with tax.
Code: const myPizza = new Pizza("medium");
myPizza.totalCost();
Expected Result: 8.3625

Test 3: It should return a number (price) that is rounded to 2 digits.
Code: const myPizza = new Pizza("medium");
myPizza.totalCost();
Expected Result: 8.36

Test 3: It sould return a number (price) that considers the amount of cheese
const myPizza = new Pizza("medium", "heavy");
myPizza.totalCost();
Expected Result: 10

Test 4: It should return a number (price) that considers any number of toppings.
Code: const my Pizza = new Pizza ("medium", "heavy", ["pepperoni", "banana peppers"]);
myPizza.totalCost();
Expected Result: 14

Test 5: It should return a number (price) that considers any number of drinks.
Code: const my Pizza = new Pizza ("medium", "heavy", ["pepperoni", "banana peppers"], ["lobrau", "slurm"]);
myPizza.totalCost();
Expected Result: 20

Test 6: It should return a number (price) that considers any number of other items.
Code: const my Pizza = new Pizza ("medium", "heavy", ["pepperoni", "banana peppers"], ["lobrau", "slurm"], ["millennia-cake", "popplers-cup"]);
myPizza.totalCost();
Expected Result: 30

