"TASK C"
Prompt: Changed the names to match the theme and content related to cars.
File name: mainscreen.html
Line number:
Changes:
14: Changed the title to <title>Kevin's Hot Wheels Dealership</title>.
19: Updated the heading to <h1>Car Supply Shop</h1>.
21: Updated the subheading to <h2>Car Parts</h2>.
53: Updated another subheading to <h2>Car Products</h2>.


"TASK D"
Prompt: Added an "About" page for the car store, with navigation links and related content.
File name: mainscreen.html, about.html, MainScreenController.java
Line number & Changes:
18: Added navigation link <a href="/about">About Us</a>.
19: Added navigation link <a href="/">Home</a>.
56-58: Added @GetMapping("/about") method


"TASK E"
Prompt: Added sample parts and products, with conditions to check if the data already existed or was empty.
File name: BootStrapData.java
Line number & Changes:
44-47: Added conditional check to ensure the sample inventory is added only if both the part and product repositories are empty.
57-73: Created addSampleInventory() method to add sample parts and products if they don't already exist.
74-83: Created addPartIfNotExists() method to add a part only if it doesn't already exist in the repository.
85-95: Created addProductIfNotExists() method to add a product only if it doesn't already exist in the repository.

"TASK F" 
Prompt: added success or fail validators
File name: AddProductController.java, Product.java, mainscreen.html
Line number & Changes:
86: added a Buy Now button and style it similar to the others like delete, update.
177-189: added if logic to in the controller to display success or failure of a purchase.
94-102: set up encapsulation to product.java in order to make a simple and add modularity to the code.
1-15 in errobuyproduct.html I added the visual view for failure pop up when product is out of stock
1-15 on confirmationbuyproduct.html I added the visual to display if it was a successful purchase an option to go to main page

"TASK G"
Prompt: overall set the min and max value restrictions 
File name: Part.java,inhoustPart.java,inhousePartForm.html, application.properties
Line number & Changes: 
32-36: added min and max inv fields in Part.java
59-65: added getters and setters in Part.java
81-84: in BootStrapData.java set a values for default min and max to 1min and 9max
17-29: set up default min, max values inhousePart and create a constructor for inhousePart
17-28: set up default min and max values for OutsourcePart.java and also created the corresponding constructor
40-47: had to add getter and setters to inhousePart.java because I had type error for because I did not use camalcase this is just extra code I wrote.
24-31: added visual look, label and textbox to inhousePartForm.html
25-32: added form field for min and max to OutsourcePartForm.html to display visually in the website
131-138: added min and max validator to enforce the inv is between min, max.
6: application.properties I rename the database to Kevin_HotWheel_Rides

"TASK H"
Prompt:
File name: Part.java, outsourceform.html,inhouseform.html, partform.html
Line number & Changes:
134 & 136: added in Part.java a validator that validates you put a min and max allowed value
42-57: inhousepartform.html added method to visually displays allowed if not successfully gives error message
12-13: method for saving outsourcepartform.html to the correct endpoint.
12-28: partform.html defines input for minimum and maximum inventory in outsourcepartform.html and inhousepartform.html

"TASK I"
Prompt:
File name: 
Line number & Changes:


 