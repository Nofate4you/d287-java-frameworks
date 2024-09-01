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
Line number:
Changes:
18: Added navigation link <a href="/about">About Us</a>.
19: Added navigation link <a href="/">Home</a>.
56-58: Added @GetMapping("/about") method


"TASK E"
Prompt: Added sample parts and products, with conditions to check if the data already existed or was empty.
File name: BootStrapData.java
Line number:
Changes:
44-47: Added conditional check to ensure the sample inventory is added only if both the part and product repositories are empty.
57-73: Created addSampleInventory() method to add sample parts and products if they don't already exist.
74-83: Created addPartIfNotExists() method to add a part only if it doesn't already exist in the repository.
85-95: Created addProductIfNotExists() method to add a product only if it doesn't already exist in the repository.








