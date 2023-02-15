### Shop Inventory Management System with JSON
Skill used - Python, Preprocessing, Data Analysis, JSON
Functionalities applied - GST, Discount and more.
####  How to run locally -

1. Clone the git repository - [Link](https://docs.github.com/en/repositories/creating-and-managing-repositories/cloning-a-repository)

2. Open the .ipynb file in Jupyter Notebook - [Link](https://www.anaconda.com/products/distribution)

3. Run and explore...

### Demo - 
**When Order Price more than 250 Rs -**
\
**Functionalities - OFFER SECTION**

```
1. If your total bill is 250 or above 5% discount on total bill. 
2. If your purchase all quantity of the inventory, 10% discount.
```

**Functionalities - MENU SECTION**
(Read JSON file and show Menu items with Price and Quantity Available)
```
---------------------------MENU------------------------------
       NOTE : 18% GST WILL BE APPLICABLE TO ALL ITEMS            
ID: Name                                        | Price | Qn Avl.
-----------------------------------------------------------------
1 : Modern Bread High Fiber Diet 		| 17 	| 200
2 : Good Night Mosquito Refill regular 		| 77 	| 30
3 : Amul Taaza Milk Pure Milk A1 cow 		| 26 	| 100
4 : Red Cow Milk Pure A Cow Milk 		| 30 	| 80
6 : Metro Toned Fresh Milk a1 buffolo 		| 26 	| 70
7 : Thumps Up Cold Drinks Fresh 		| 30 	| 20
8 : Sprite Cold Drinks Fresh Small 		| 40 	| 35
9 : Limca Cold Drinks Fresh Small 		| 30 	| 80
10 : Fanta Cold Drinks Fresh Big 		| 70 	| 10
11 : Mountain Dew Cold Drinks Fresh 		| 40 	| 20
12 : Bisleri Packaged Water 5L Pure 		| 70 	| 10
13 : Bisleri Water 1L Pure Mineral 		| 20 	| 20
14 : Lays Chips Classical Flavour 		| 20 	| 70
15 : Kurkure Chips Family Hunger 		| 20 	| 70
16 : Uncle Chipps Classical chips 		| 20 	| 40
17 : Doritos Chips The Triangle Love 		| 30 	| 30
18 : ACT II popcorn 2 minutes Popcorn 		| 26 	| 70
19 : Prabhuji Bhujia Pure Bhujia ready 		| 247 	| 20
20 : Mukharochak Chanachur for All 		| 70 	| 30
21 : Britannia Treat Waffle for Childs 		| 20 	| 30
22 : Winkies Tea Cake Pure Cake Pure 		| 124 	| 20
23 : Britannia Toastea Toast Biscuit 		| 40 	| 20
24 : Fortune Mustard Oil Pure Oil 		| 154 	| 30
25 : Tata Salt Desh ka namakh iodised 		| 25 	| 30
-----------------------------------------------------------------
```


**--User Details--**
```
Enter UserName : Aryadeep
Enter Mail ID  : aryadeepit@gmail.com
Enter Phn No   : 9735427303
```

**--Enter Requirement--**
```
Enter Product ID : 19
Enter Quantity   : 2
```


**--BILL SECTION --**
```
Product Name       :  Prabhuji Bhujia Pure Bhujia ready
Price Per Item (₹) :  247 Rs
Quantity Requested :  2

 Unit Price (₹)     :  494 Rs
 GST (18%)          :  88.92 Rs
 Discount (5%)      :  29.15 Rs
 Bill (₹)           :  553.77 Rs
```

-----------------------------------------------------------------
           Thanks for your order, Inventory Updated!             
-----------------------------------------------------------------

**If user wants to purchase all available quantity -**
**10% discount applied**
```
-----------------------User Details------------------------------
Enter UserName : Sanchita
Enter Mail ID  : sanchita@aryadeep.com
Enter Phn No   : 8282828282
-----------------------------------------------------------------

------------------------Enter Requirement------------------------
Enter Product ID : 15
Enter Quantity   : 100
-----------------------------------------------------------------

Sorry, We are not having enough Quantity in our Inventory.
We're only having 70 quantity.
-----------------------------------------------------------------
Press Y/y to Purchase: y

-------------------------BILL------------------------------------
Product Name       :  Kurkure Chips Family Hunger
Price Per Item (₹) :  20 Rs
Quantity Requested :  70
-----------------------------------------------------------------
Unit Price (₹)     :  1400 Rs
GST (18%)          :  252.0 Rs
Discount (10%)     :  165.2 Rs
Total Bill (₹)     :  1486.8 Rs
-----------------------------------------------------------------


-----------------------------------------------------------------
           Thanks for your order, Inventory Updated!             
-----------------------------------------------------------------
```

**If purchase price is less than 250 -**
```
-----------------------User Details------------------------------
Enter UserName : Arya
Enter Mail ID  : arya@gmail.com
Enter Phn No   : 98989898
-----------------------------------------------------------------

------------------------Enter Requirement------------------------
Enter Product ID : 1
Enter Quantity   : 5
-----------------------------------------------------------------

-------------------------BILL------------------------------------
Product Name       :  Modern Bread High Fiber Diet
Price Per Item (₹) :  17 Rs
Quantity Requested :  5
-----------------------------------------------------------------
Unit Price (₹)     :  85 Rs
GST (18%)          :  15.299999999999999 Rs
Bill (₹)           :  100.3 Rs
-----------------------------------------------------------------

-----------------------------------------------------------------
           Thanks for your order, Inventory Updated!             
-----------------------------------------------------------------
```

**If User don't want to purchase as desired quantity not available - **

```
-----------------------User Details------------------------------
Enter UserName : Munu
Enter Mail ID  : munu@iam.com
Enter Phn No   : 8080808080
-----------------------------------------------------------------

------------------------Enter Requirement------------------------
Enter Product ID : 14
Enter Quantity   : 30
-----------------------------------------------------------------

Sorry, We are not having enough Quantity in our Inventory.
We're only having 20 quantity.
-----------------------------------------------------------------
Press Y/y to Purchase: n
Thank You!
```