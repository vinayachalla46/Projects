#TITLE

Bill Generator  - Java Console Application

#DESCRIPTION

Pizza Bill generator is a simple Java console application that simulates ordering pizzas with customizable options such as extra cheese, extra toppings, and takeaway packaging. It supports four types of pizzas:

- Veg Pizza
- Non-Veg Pizza
- Deluxe Veg Pizza
- Deluxe Non-Veg Pizza

The program calculates the total price based on selected options and prints a detailed bill.

---

## Project Structure

- Pizza.java — Base class representing a pizza with options to add cheese, toppings, and takeaway packaging.
- DeluxPizza.java — Subclass of pizza representing deluxe pizzas with different base prices.
- Main.java — Contains the main method and user interaction to choose and customize pizzas.

#Features


- Select pizza type (Veg, Non-Veg, Deluxe Veg, Deluxe Non-Veg)
- Add extra cheese and toppings
- Opt for takeaway packaging
- View detailed bill with all chosen options and total price

---

# Technologies Used

**Java**
 **OOP Concepts**:  
  - Inheritance  
  - Method Overriding  
  - Constructors  
  - Access Specifiers 

---
# How to Run

1. Clone the repository:

   git clone https://github.com/vinayachalla46/Projects.git
   cd Projects
   
3. Compile the Java files:

   javac bill/*.java

4. Run the application:
 
   java bill.Main

