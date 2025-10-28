# 💻 Laptop Price EDA Project

![Python](https://img.shields.io/badge/Python-3.10-blue)
![Jupyter](https://img.shields.io/badge/Notebook-Google%20Colab-orange)
![Libraries](https://img.shields.io/badge/Libraries-Pandas%2C%20NumPy%2C%20Seaborn%2C%20Matplotlib-brightgreen)
![Status](https://img.shields.io/badge/Status-Completed-success)
![License](https://img.shields.io/badge/License-MIT-yellow)
![Contributions](https://img.shields.io/badge/Contributions-Welcome-blueviolet)
![Made with ❤️](https://img.shields.io/badge/Made%20with-%E2%9D%A4-red)



![Dashboard Preview](images/laptop_price_dashboard.png)


This project analyzes laptop pricing trends using Python (Pandas, Seaborn, Matplotlib).  
It explores how different specifications — such as RAM, brand, screen size, and storage — affect laptop prices.  
The findings are visualized through a Power BI dashboard and detailed EDA notebook.

---

## 📂 Project Structure


---

## 📌 Sections Covered

- **1. Introduction**
- **2. Data Importing**
- **3. Data Cleaning**
- **4. Univariate Analysis**
- **5. Bivariate Analysis**
- **6. Feature Engineering**
- **7. Correlation Heatmap**
- **8. Key Insights & Summary**
- **9. Conclusion**
- *(Optional)* Save cleaned data or plots

---

## 📊 Dataset Description

The dataset includes the following columns:
- Company
- TypeName
- Inches
- ScreenResolution
- Cpu
- Ram
- Memory (HDD/SSD)
- Gpu
- OpSys
- Weight
- Price

---

## 🔍 Key Insights

### 🔥 Correlation Heatmap
![Correlation Heatmap](images/heatmapt.png)

### 💻 Operating System Distribution
![OS Distribution](images/countplot5.png)

- **Windows 10** dominates the market share among Operating Systems.
- **SSD-equipped** laptops and **i7 CPUs** strongly increase laptop prices.
- **Apple**, **Dell**, and **Workstation** laptops are typically in the premium price range.
- **Touchscreen laptops** are generally lighter and have smaller screens.
- **Weight** increases with screen size and RAM.
- Strong positive correlation between **Inches and Weight** (0.49).

---

## 🛠 Tools Used

- [x] Python
- [x] Google Colab
- [x] Power BI
- [x] Pandas
- [x] NumPy
- [x] Seaborn
- [x] Matplotlib

---

## 🚀 How to Run

1. Open the `.ipynb` file using **Google Colab** or **Jupyter Notebook**.
2. Run cells step by step to follow the EDA process.
3. All plots are generated inline and insights are printed within the notebook.

---

## ✅ Final Thoughts

This EDA revealed how laptop specifications — especially **RAM**, **SSD presence**, **brand**, and **CPU type** — significantly impact pricing. It also demonstrated how screen size, weight, and operating systems play roles in user preferences and pricing tiers.

---
**👨‍💻 Created by:** Bheemankar Vijay  
🎓 AIML Student | Data Analytics Enthusiast  
📧 Contact: [bheemankarvijay@gmail.com]  
📍 Tools: Python | Power BI | Google Colab | GitHub  


