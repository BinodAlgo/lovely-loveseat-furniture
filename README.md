
---
# Lovely Loveseats Furniture Store Receipt - Python Project

## Project Description

In this beginner-friendly Python project, we'll be creating a system to help speed up the process of creating receipts for customers of our furniture store, Lovely Loveseats for Neat Suites on Fleet Street.

We will start by setting up our catalog with the names and prices of the furniture items we offer. Then, we will process the total price and item list for a customer's purchase and print them to the output terminal.

## Project Tasks

### 1. Adding In The Catalog

Let’s add in our first item, the Lovely Loveseat that is the store’s namesake. Create a variable called `lovely_loveseat_description` and assign to it the following string:

```python
lovely_loveseat_description = "Lovely Loveseat. Tufted polyester blend on wood. 32 inches high x 40 inches wide x 30 inches deep. Red or white."
```

Create another variable called `lovely_loveseat_price` and set it equal to the price of the Lovely Loveseat:

```python
lovely_loveseat_price = 254.00
```

Now, let’s extend our inventory with another characteristic piece of furniture! Create a variable called `stylish_settee_description` and assign to it the following string:

```python
stylish_settee_description = "Stylish Settee. Faux leather on birch. 29.50 inches high x 54.75 inches wide x 28 inches deep. Black."
```

Create a variable called `stylish_settee_price` and set it equal to the price of the Stylish Settee:

```python
stylish_settee_price = 180.50
```

Fantastic, we just need one more item before we’re ready for business. Create a new variable called `luxurious_lamp_description` and assign it the following:

```python
luxurious_lamp_description = "Luxurious Lamp. Glass and iron. 36 inches tall. Brown with cream shade."
```

Let’s set the price for this item. Create a variable called `luxurious_lamp_price` and set it equal to the price of the Luxurious Lamp:

```python
luxurious_lamp_price = 52.15
```

### 2. Calculating Sales Tax

In order to be a business, we should also be calculating sales tax. Let’s store that in a variable as well.

Define the variable `sales_tax` and set it equal to 0.088 (8.8%):

```python
sales_tax = 0.088
```

### 3. Our First Customer

Our first customer is making their purchase! Let’s keep a running tally of their expenses by defining a variable called `customer_one_total`. Since they haven haven’t purchased anything yet, let’s set that variable equal to 0 for now:

```python
customer_one_total = 0
```

We should also keep a list of the descriptions of things they’re purchasing. Create a variable called `customer_one_itemization` and set that equal to the empty string `""`. We’ll tack on the descriptions to this as they make their purchases:

```python
customer_one_itemization = ""
```

Our customer has decided they are going to purchase our Lovely Loveseat! Add the price to `customer_one_total`:

```python
customer_one_total += lovely_loveseat_price
```

Let’s start keeping track of the items our customer purchased. Add the description of the Lovely Loveseat to `customer_one_itemization`:

```python
customer_one_itemization += lovely_loveseat_description + "\n"
```

Our customer has also decided to purchase the Luxurious Lamp! Let’s add the price to the customer’s total:

```python
customer_one_total += luxurious_lamp_price
```

Let’s keep the itemization up-to-date and add the description of the Luxurious Lamp to our `customer_one_itemization`:

```python
customer_one_itemization += luxurious_lamp_description + "\n"
```

They’re ready to check out! Let’s begin by calculating sales tax. Create a variable called `customer_one_tax` and set it equal to `customer_one_total` times `sales_tax`:

```python
customer_one_tax = customer_one_total * sales_tax
```

Add the sales tax to the customer’s total cost:

```python
customer_one_total += customer_one_tax
```

Let’s start printing up their receipt! Begin by printing out the heading for their itemization. Print the phrase "Customer One Items:":

```python
print("Customer One Items:")
```

Print `customer_one_itemization`:

```python
print(customer_one_itemization)
```

Now add a heading for their total cost: Print out "Customer One Total:"

```python
print("Customer One Total:")
```

Now print out their total! Our first customer now has a receipt for the things they purchased:

```python
print(customer_one_total)
```

### 4. Congratulations!

Congratulations! We created our catalog and served our first customer. We used our knowledge of strings and numbers to create and update variables. We were able to print out an itemized list and a total cost for our customer. Lovely!



