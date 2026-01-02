# 🍽️ MealDB – Postman API Project

## 📌 Project Overview
This project uses **TheMealDB API** in Postman to fetch meal recipes, process the ingredient data, and display it beautifully using **Postman Visualizer**.  
The main goal of this project is to identify the **meal that requires the least number of ingredients**, making it easier and quicker to cook.

---

## 🌐 API Used
TheMealDB Public API  
Base URL:
https://www.themealdb.com/api/json/v1/1/search.php?s=

This API returns:
- Meal Name  
- Category  
- Region  
- Ingredients  
- Measures  
- Instructions  
- Image  

---

## 🛠️ Tools & Technologies
- Postman  
- JavaScript (Postman Scripts)  
- REST API  
- HTML + CSS (Visualizer UI)  

---

## 🚀 How the Project Works
1️⃣ Send API request to TheMealDB using Postman  
2️⃣ Receive response in JSON format  
3️⃣ Loop through each meal  
4️⃣ Count valid ingredients  
5️⃣ Find the meal with the **minimum ingredients**  
6️⃣ Display result in Postman Visualizer in a clean UI  

---

## ▶️ How to Run
1. Open **Postman**
2. Click **Import**
3. Select: `MealDB_Postman.json`
4. Open the request and click **Send**
5. Open **Visualizer Tab** to see output

---

## 📂 Repository Contents
MealDB-Postman-Project/
├── MealDB_Postman_Collection.json
├── README.md
└── screenshots (optional)

---

## 👀 Output
✔ Meal Name  
✔ Category & Area  
✔ Ingredient Count  
✔ Ingredients with Measures  
✔ Instructions  
✔ Clean Visual Output  

If no meal is found → it shows **"No Meals Found"**

---

## 🎯 Learning Outcomes
✔ Understanding REST APIs  
✔ JSON parsing  
✔ Logical programming  
✔ Postman scripting  
✔ Data visualization
