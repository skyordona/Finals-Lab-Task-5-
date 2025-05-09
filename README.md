# [Finals Lab Task 5 - Views, Stored Procedures and Functions](https://github.com/user-attachments/files/20126886/Finals.Lab.Task.5.-.Ordona.docx)
- This portfolio demonstrates the use of SQL views, stored procedures, and stored functions to manage and manipulate database data. It covers tasks such as filtering data with views, updating records with stored procedures, and retrieving data using functions.

## Step-by-Step Process:
1. **Setup MySQL Workbench:**

   * Open XAMPP and start the MySQL server.
   * Connect MySQL Workbench to the server.
   * Execute practice queries using the `democodes.sql` file.

2. **Use Inventory Database:**

   * Open the `inventory.sql` file to begin the tasks.

3. **Create Views:**

   * Create a view to display vendor information and products with in-date from 2002 onward.
   * Create a view for products with prices between 100-150.
   * Create a view to compute the total price for products sold by specific vendors.

4. **Create Stored Procedure:**

   * Create a stored procedure that updates the vendor name from 'Bryson, Inc.' to 'Bryson and Co'.

5. **Create Function:**

   * Create a function that takes vendor code and state as parameters to display product details.

6. **Execute and Document:**

   * Execute the SQL statements and capture screenshots of the commands and outputs.

# Screenshots of Codes and Outputs:
### 1. CREATE A VIEW that will display the vendors_code, vendors name, product
description p_indate, of all products with p_indate from 2002 onwards
- ![Image](https://github.com/user-attachments/assets/a8545cac-4839-46e9-b1d7-2e7713c7561d)

## Output
- ![Image](https://github.com/user-attachments/assets/2c812ea2-f9be-403b-8992-e685ccdaf01e)

### 2. CREATE a VIEW that will display all products whose price range is between 100-150
- ![Image](https://github.com/user-attachments/assets/c61aea57-6451-4203-ad49-c65282240010)

## Output
- ![Image](https://github.com/user-attachments/assets/c703a454-0776-4941-ae42-e6d06ece0b0a)

### 3. Create a VIEW that will COMPUTE for the (TOTAL_PRICE) of ALL
PRODUCTS by getting the (P_ONHAND x P_PRICE) Sold by vendors with
the following v_code (21344, 23119 and 24288)
- ![Image](https://github.com/user-attachments/assets/d03aa9d7-f526-47ee-bfd5-86a4cfb03052)
## Output
- ![Image](https://github.com/user-attachments/assets/b1295f73-b8b5-4eb4-bd3e-c42223f784ed)

### 4. CREATE a STORED PROCEDURE that WILL take a SINGLE PARAMETER and
UPDATED the Name of Vendor ‘Bryson,Inc.’ to ‘Bryson and Co’.
- ![Image](https://github.com/user-attachments/assets/86a96b15-e271-4177-beda-d0fd2dec9e3d)
## Output
- ![Image](https://github.com/user-attachments/assets/28b3ca4f-879b-494a-8ec6-f3aca1e1f78f)

### 5. CREATE A Function that will take 2 parameters(v_code and
v_state) and display All the product description and price based on
the parameters passed to the function
- ![Image](https://github.com/user-attachments/assets/025cd604-93d1-462a-927f-138dd9635991)
## Output
- ![Image](https://github.com/user-attachments/assets/9f27a067-adb3-4131-bd69-abcc4ba7d970)
