# Second-Sale-Shopping
Here’s a rewritten version of the **README.md** file without plagiarism:

---

# 🛒 Second Sale Shopping

Second Sale Shopping is a platform designed for users to act as both buyers and sellers, enabling a smooth exchange of products. The project integrates a well-structured database, an efficient backend, and an engaging frontend to provide a seamless user experience.

---

## 📂 Database Structure

The system is built with several interconnected tables to manage data effectively:

1. Category:  
   - Stores the categories added by the admin.  
   - Key Field: `category_name`.  

2. Subcategory:  
   - Manages subcategories linked to specific categories.  
   - **Key Fields**: `sub_category_name`, `category_id` (Foreign Key).  

3. User:  
   - Handles user data, enabling both registration and account management.  
   - **Key Fields**: `name`, `email`, `phone`, `password`, `about`, `status`.  

4. Product:  
   - Allows sellers to upload product details, including descriptions and images.  
   - **Key Fields**: `product_name`, `price`, `picture`, `description`, `posted_date`, `subcategory_id` (Foreign Key), `seller_id` (Foreign Key).  

5. Transaction:  
   - Manages purchase records and payment details.  
   - Key Fields: `requested_amount`, `seller_amount`, `admin_amount`, `status`, `date`, `settlement_date`, `product_id` (Foreign Key), `buyer_id` (Foreign Key), `seller_id` (Foreign Key).  

---

🔧 Backend Technologies

- Python:  
   - Built using the Flask framework for server-side functionality.  
   - Manages interactions with the database and facilitates smooth data processing.  

- MySQL:  
   - Utilized for storing user credentials, managing product data, and processing transactions.  

---

🎨Frontend Technologies

- HTML:  
   - Provides the structure for creating web pages.  

- CSS:  
   - Styles the interface for a visually appealing design.  

- Bootstrap:  
   - Simplifies the design process with pre-built templates for buttons, forms, and layouts.  

- JavaScript:  
   - Adds interactivity to the web pages and handles data requests and user actions.  



 🌐 Live Project

Explore the live application here: [Second Sale Shopping](http://3.138.155.237/)




