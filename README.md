# Zomato Restaurant Data Analysis

## 📌 Overview
This project analyzes restaurant data from Zomato to answer key questions about online and offline restaurant services, customer preferences, and pricing trends. 

## 📊 Questions Addressed
1. **Do more restaurants provide online delivery compared to offline services?**  
2. **Which types of restaurants are the most favored by the public?**  
3. **What price range is preferred by couples for dining?**  
4. **Do online orders receive better ratings than offline orders?**  

## 🗃 Dataset
The dataset (`Zomato data.csv`) contains the following columns:
- **name** – Name of the restaurant.
- **online_order** – Whether the restaurant provides online delivery (Yes/No).
- **book_table** – Whether table booking is available.
- **rate** – Restaurant rating.
- **votes** – Number of votes received.
- **approx_cost(for two people)** – Approximate cost for two people.
- **listed_in(type)** – Category of the restaurant (e.g., Buffet, Café, Quick Bites).

## 🛠 Dependencies
Ensure the following Python libraries are installed before running the script:
```bash
pip install pandas numpy matplotlib seaborn
