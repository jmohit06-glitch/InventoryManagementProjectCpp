# 🏪 Inventory Management System (C++ Project)


## 🧩 Overview
    ```bash
    The Inventory Management System is a console-based application developed in C++.  
    It helps manage products, track stock levels, and record customer purchases.  
    The system reads and updates inventory data from files and automatically logs all sales.

## 💡 Proposed Solution
    This system simplifies manual inventory management by:
    1. Automating stock updates after each sale.  
    2. Maintaining detailed sales records with date and time.  
    3. Allowing users to quickly view available products.  
    4. Calculating total bills automatically.  
    5. Ensuring data persistence using text files (inventory.txt and sales.txt).

## 📦 Inventory Data (inventory.txt)

    +----+---------------------------+-----------+-----------+
    | ID | Product Name              | Price(Rs) | Quantity  |
    +----+---------------------------+-----------+-----------+
    | 1  | 5 Star                    | 5         | 85        |
    | 2  | Dairy Milk                | 10        | 91        |
    | 3  | Lays Chips                | 200       | 300       |
    | 4  | Pepsi                     | 15        | 250       |
    | 5  | Coke                      | 20        | 180       |
    | 6  | Sprite                    | 18        | 160       |
    | 7  | Fanta                     | 17        | 140       |
    | 8  | Mountain Dew              | 22        | 130       |
    | 9  | Thumbs Up                 | 19        | 145       |
    | 10 | Mirinda                   | 21        | 155       |
    | ...                            | ...       | ...       |
    | 50 | Horlicks                  | 130       | 55        |
    +----+---------------------------+-----------+-----------+


## 🧾 Sales Data (sales.txt)
    +-----+-----------------+---------------+---------------------------+-----------+-----------+---------------+---------------------------+
    | SNo | Customer Name   | Mobile        | Email                     | Prod ID   | Quantity  | Total (Rs)    | Date & Time               |
    +-----+-----------------+---------------+---------------------------+-----------+-----------+---------------+---------------------------+
    | 1   | Divya           | 7854215689    | divy@gmail.com            | 46        | 6         | 468.00        | Sun Nov 02 14:34:07 2025  |
    +-----+-----------------+---------------+---------------------------+-----------+-----------+---------------+---------------------------+
    | 2   | Rahul Mehta     | 9823456712    | rahulm@gmail.com          | 52        | 3         | 375.00        | Sun Nov 02 14:40:25 2025  |
    +-----+-----------------+---------------+---------------------------+-----------+-----------+---------------+---------------------------+
    | 3   | Sneha Kapoor    | 9098123456    | sneha.kapoor@gmail.com    | 61        | 2         | 260.00        | Sun Nov 02 14:47:13 2025  |
    +-----+-----------------+---------------+---------------------------+-----------+-----------+---------------+---------------------------+
    | 4   | Arjun Patel     | 9723412367    | arjunp@yahoo.com          | 47        | 4         | 520.00        | Sun Nov 02 15:05:42 2025  |
    +-----+-----------------+---------------+---------------------------+-----------+-----------+---------------+---------------------------+
    | 5   | Priya Nair      | 8805642389    | priyanair@outlook.com     | 49        | 1         | 125.00        | Sun Nov 02 15:12:56 2025  |
    +-----+-----------------+---------------+---------------------------+-----------+-----------+---------------+---------------------------+
    | 6   | Karan Singh     | 9987456123    | karansingh@gmail.com      | 58        | 5         | 675.00        | Sun Nov 02 15:25:39 2025  |
    +-----+-----------------+---------------+---------------------------+-----------+-----------+---------------+---------------------------+
    | 7   | Meera Joshi     | 9812765430    | meerajoshi@hotmail.com    | 53        | 3         | 360.00        | Sun Nov 02 15:41:20 2025  |
    +-----+-----------------+---------------+---------------------------+-----------+-----------+---------------+---------------------------+
    | 8   | Aditya Rao      | 9956234781    | aditya.rao@gmail.com      | 60        | 7         | 910.00        | Sun Nov 02 15:59:11 2025  |
    +-----+-----------------+---------------+---------------------------+-----------+-----------+---------------+---------------------------+
    | 9   | Nisha Verma     | 7865432109    | nishav@yahoo.com          | 44        | 2         | 220.00        | Sun Nov 02 16:15:48 2025  |
    +-----+-----------------+---------------+---------------------------+-----------+-----------+---------------+---------------------------+
    | 10  | Rohit Sharma    | 9823004567    | rohit.sharma@gmail.com    | 51        | 8         | 1040.00       | Sun Nov 02 16:32:33 2025  |
    +-----+-----------------+---------------+---------------------------+-----------+-----------+---------------+---------------------------+
    | 11  | Vedant Singh    | 8796564213    | vedant@gmail.com          | 50        | 5         | 650.00        | Sun Nov 02 16:45:58 2025  |
    +-----+-----------------+---------------+---------------------------+-----------+-----------+---------------+---------------------------+

## ⚙️ Steps to Run
  ### 1️⃣ Clone Repository:
       git clone https://github.com/yourusername/Inventory-Management-System.git  
       cd Inventory-Management-System  
    
  ### 2️⃣ Compile Code:
       g++ main.cpp -o inventory  
    
  ###  3️⃣ Run Program:
       ./inventory    # (Linux/Mac)  
       inventory.exe  # (Windows)
    
  ###  4️⃣ Use Program:
       - View product list  
       - Enter customer and purchase details  
       - Get total bill and save sale record  
       - Inventory auto-updates after each sale  
    
  ###  5️⃣ Push Updates to GitHub:
       git add .  
       git commit -m "Updated inventory and sales data"  
       git push origin main

## 👩‍💻 Team Members
      1. Divya Saxena  
      2. Vedant Singh  
      3. Prit Patel  
      4. J Mohit

## 🧠 Team Info
      Project Name  : Inventory Management Team  
      Institute     : SRM University AP
      Course        : B.Tech (Computer Science)  
      Project Year  : 2025  
      Language      : C++

