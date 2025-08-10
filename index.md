# 🍽️ Foodify – Online Food Ordering System

<p>
  <img src="https://raw.githubusercontent.com/jayakanthDeveloper/Foodify-repo/refs/heads/main/FoodifyLogo.png" alt="Foodify Logo" width="150">
</p>

---

## 📌 Project Overview
Foodify is an **online food ordering system** where users can explore restaurants,explore the menu by restaurants, add items to the cart, place orders, and track their order history.  
The project is developed using **HTML**, **CSS3**, **JSP**, **Java**,**JDBC**, **Servlets**, and **MySQL**, following the **DAO design pattern**.

---

## 🛠️ Technologies Used

<p align="center">
  <img src="https://upload.wikimedia.org/wikipedia/commons/6/61/HTML5_logo_and_wordmark.svg" alt="HTML5" width="60" height="60" style="margin-right:30;"/>
  <img src="https://upload.wikimedia.org/wikipedia/commons/d/d5/CSS3_logo_and_wordmark.svg" alt="CSS3" width="60" height="60" style="margin-right:30;"/>
  <img src="https://upload.wikimedia.org/wikipedia/en/3/30/Java_programming_language_logo.svg" alt="Java" width="60" height="60" style="margin-right:30;"/>
  <img src="https://img.icons8.com/?size=100&id=QFcVqyh6lBh6&format=png&color=000000" alt="MySQL" width="60" height="60" style="margin-right:30;"/>

</p>

---

## 📂 Project Phases

### **Phase 1**  
Created database with 5 main tables: **User, Restaurant, Menu, Orders, OrderItem**.

### **Phase 2**  
Designed **DAO Design Pattern** for all tables with segregated packages:  
- POJO classes  
- DAO Interfaces  
- DAO Implementations  
- Launcher classes for inserting data from Java  

### **Phase 3**  
Created servlet to **display all restaurants** and pass the data to **JSP** for showing dynamic restaurant listings.

### **Phase 4**  
Displayed **menus under specific restaurants** with **Add to Cart** buttons.

### **Phase 5**  
When user clicks **Add to Cart**, checks if:  
- Cart exists or not  
- Items are from the same restaurant  
Allows **increase, decrease, and remove** cart items.

### **Phase 6**  
Added **place order functionality**:  
- Requires user **address** & **payment mode**  
- Checks if the user is logged in (if not, redirects to login/registration)  
- Validates and processes the order  

### **Phase 7**  
Added **Order History**:  
- User can view previous orders  
- See ordered menu items  
- Reorder previous orders with one click  

---

## ✨ Features
- 🔍 Explore restaurants without login.
- 🛒 Add menus to cart from the same restaurant.
- 📦 Increase, decrease, or remove items from cart.
- 🏠 Save user address before checkout.
- 💳 Choose payment mode before placing an order.
- 📜 View **order history** and **reorder** past items.
- 🔐 Login/Registration validation before checkout.

---


## 📷 Screenshots
### **Home Page** 
<img src="https://raw.githubusercontent.com/jayakanthDeveloper/Foodify-repo/refs/heads/main/Home%20page.png" alt="Homepage Screenshot" width="900">

### **All Restaurants** 
<img src="https://raw.githubusercontent.com/jayakanthDeveloper/Foodify-repo/refs/heads/main/All%20restaurants.png" alt="Homepage Screenshot" width="900">

### **All menu** 
<img src="https://raw.githubusercontent.com/jayakanthDeveloper/Foodify-repo/refs/heads/main/Menu.png" alt="Homepage Screenshot" width="900">

### **Cart page** 
<img src="https://raw.githubusercontent.com/jayakanthDeveloper/Foodify-repo/refs/heads/main/Cart%20page.png" alt="Homepage Screenshot" width="900">

---

## See my code using this link👇🏿

[(https://github.com/jayakanthDeveloper/Foodify)](https://github.com/jayakanthDeveloper/Foodify)

---

## 🚀 How to Run
1. Clone the repository  
2. Import into your IDE (Eclipse/IntelliJ)  
3. Configure **Tomcat Server**  
4. Create database and import SQL file  
5. Run on `localhost`  

---

## 📧 Contact
For queries, contact: **jayakanthdeveloper@gmail.com**

