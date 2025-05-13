# 𝓕𝓲𝓷𝓪𝓵𝓼 𝓛𝓪𝓫 𝓣𝓪𝓼𝓴 5: 𝓢𝓠𝓛 𝓥𝓲𝓮𝔀𝓼, 𝓕𝓾𝓷𝓬𝓽𝓲𝓸𝓷𝓼, & 𝓢𝓽𝓸𝓻𝓮𝓭 𝓟𝓻𝓸𝓬𝓮𝓭𝓾𝓻𝓮𝓼
> This repository demonstrates advanced SQL skills by using views, stored procedures, and stored functions in MySQL Workbench through structured tasks on a sample inventory system.
---
## 🧩 Tasks Overview
### 🔹 Task 1: Create a VIEW for 2002+ product entries 🗓️
- 📌 View includes: vendors_code, vendors_name, product_description, p_indate
- **✅ Filter: p_indate ≥ 2002**
  
  ![image](https://github.com/user-attachments/assets/27d7af69-013a-416f-8eac-6e694cd8857a)
---
### 🔹 Task 2: Create a VIEW for products priced 💸 between 100–150
- **📌 Filters products where: p_price BETWEEN 100 AND 150**
![image](https://github.com/user-attachments/assets/d49f37de-d222-4f0b-8c42-82f4a5abc67c)
---
### 🔹 Task 3: Create a VIEW to compute TOTAL_PRICE 🧮
- 📌 Calculates: P_ONHAND * P_PRICE
- 📌 For vendors: v_code IN (21344, 23119, 24288)
![image](https://github.com/user-attachments/assets/e22ad900-5f70-483c-8cf3-192daf5bf3d0)
---
### 🔹 Task 4: Create a STORED PROCEDURE 🛠️
- 📌 Task: Takes 1 parameter and updates vendor name
- ✏️ From Bryson, Inc. ➡️ Bryson and Co
  
![image](https://github.com/user-attachments/assets/36d51392-4b2d-41da-ab6e-a99adb8c316b)

### 🔹 Task 5: Create a FUNCTION with 2 parameters ⚙️
- 📌 Parameters: v_code, v_state
- 📌 Returns: product_description, price based on parameters
![image](https://github.com/user-attachments/assets/bcfdeb7d-656c-45ee-ac9f-91957d78bbcd)

---
![image](https://github.com/user-attachments/assets/e896488b-7af6-4515-8d5b-c6b2760f403c)

---
💾 SQL Export of Views and SP/Functions
📝 To export:

MySQL Workbench → Server → Data Export → Choose structure & routines only → Export as .sql

📂 : [SQL COPY ⭐ ](https://github.com/aening/EDM-PROJECTS-Kate/blob/main/Finals%20Lab%20Task%203/Dump20250420%20(3).sql)






