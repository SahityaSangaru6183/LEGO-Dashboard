# 🧱 LEGO Set Explorer Dashboard

An interactive Power BI dashboard to explore LEGO sets based on theme, price, age range, and more — helping collectors quickly narrow down the best options using dynamic filters, visuals, and slicers.

---

## 🔍 Short Description / Purpose

This dashboard was created to help LEGO enthusiasts easily explore and compare LEGO sets using specific criteria like price, theme, age range, and piece count. It aims to provide an intuitive way to filter and analyze sets visually, without diving into raw data.

---

## 💻 Tech Stack

The dashboard was built using the following tools and technologies:

- 📊 **Power BI Desktop** – Core tool for dashboard creation  
- 🧹 **Power Query** – Used for data cleaning and shaping  
- 🧠 **DAX (Data Analysis Expressions)** – Used for conditional columns and KPIs  
- 🔗 **Data Modeling** – Defined relationships among LEGO attributes  
- 🗂️ **.pbix** format – Project saved as a Power BI report file

---

## 🗃️ Data Source

- Source: LEGO Sets Dataset from Maven Analytics Challenge  
- Structure: CSV file with columns like `name`, `theme`, `pieces`, `min_age`, `price`, `imageURL`, and more

---

## 🎯 Features / Highlights

### • Business Problem

With thousands of LEGO sets available, it’s difficult for collectors or buyers to explore and decide on a set that matches their interests and budget.

### • Goal of the Dashboard

To create an interactive Power BI tool that helps users:

- View and compare LEGO sets
- Filter sets by age, price, theme, and piece count
- Get insights at a glance with key metrics

### • Walkthrough of Key Visuals

- 🔢 **Card KPIs**  
  Show:  
  - Total Sets  
  - Average Price  
  - Average Pieces  
  - Average Age  

- 🧩 **Table Visual**  
  Displays: `set name`, `theme`, `image`, `price`, `pieces`, `age range`, `price range`, `set ID`

- 🎛️ **Slicers/Filters**  
  Allow users to filter based on:  
  - Theme group  
  - Age range  
  - Price range  
  - Max price (numeric range slicer)

- 🧠 **DAX Measures**  
  - Total Sets  
  - Total Theme Groups  
  - Average Price  
  - Average Pieces  
  - Conditional Columns for Age & Price Range

- 📌 **Tooltips & Interactivity**  
  - Image shown on hover  
  - Slicers affect only selected visuals  
  - Button to reset filters using bookmarks and actions

- 🌳 **Decomposition Tree (Bonus)**  
  - Analyze total sets by theme, category, or name  
  - Navigate between pages using buttons

### • Business Impact & Insights

- Helps users **filter LEGO sets based on criteria**, saving time  
- Enables **data-driven selection** of age-appropriate or budget-friendly sets  
- Can be extended for use by **LEGO stores, parents, collectors**, or enthusiasts  
- Supports clear **visual storytelling** using interactive features

---

## 🖼️ Dashboard Snapshots

> Add screenshots from your PBIX here. You can upload them in your GitHub repo and embed as below:

```markdown
Example: ![Dashboard Preview](https://github.com/the-mansi-goel/Ski-dashboard/blob/main/Snapshot%20of%20the%20Dahbaord.png)
