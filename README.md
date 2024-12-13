# Data Analytics Intern Assignment

## 📋 **Project Overview**
The objective of this project is to analyze datasets related to user behavior, cooking preferences, and order trends. We aim to uncover insights that will drive business decisions, such as identifying popular dishes, understanding the relationship between cooking sessions and orders, and discovering how user demographics affect engagement.

---

## 📁 **Project Structure**
```

📁 data-analytics-assignment
├── 📁 data
│   |                      # UserDetails(Sheet-1)      -> User demographic and preference data
│   ├── excel_data.xlsx    # CookingSessions(Sheet-2)  -> Cooking session activity data
│   │                      # OrderDetails(Sheet-3)     -> Order transaction details
│   │                      
│   └── cleaned_data.csv   # cleaned data csv file
│
├── 📁 notebooks
│   ├── Data Cleaning.ipynb                # Jupyter Notebook to clean and merge datasets
│   └── Analysis And Visualization.ipynb   # Jupyter Notebook for analysis and visualization
│
├── 📁 visualizations
│   ├── popular_dishes.png
│   ├── revenue_by_meal.png
│   ├── sessions_vs_orders.png            # Visual outputs from the analysis
│   ├── user_engagement_by_age.png
│   └── charts_and_graphs.png 
│
└── 📜 README.md               # Overview of the project (this file)

```

---

## 📊 **Data Description**

### 1️⃣ **UserDetails.csv**
- **User ID**: Unique identifier for the user.
- **User Name**: Name of the user.
- **Age**: User's age.
- **Location**: User's location.
- **Favorite Meal**: The user's preferred meal type (Breakfast, Lunch, Dinner, etc.).
- **Total Orders**: Total number of orders placed by the user.

### 2️⃣ **CookingSessions.csv**
- **Session ID**: Unique identifier for the cooking session.
- **User ID**: Links the session to a specific user.
- **Dish Name**: Name of the dish being prepared.
- **Meal Type**: Type of meal (Breakfast, Lunch, Dinner, etc.).
- **Session Start**: Timestamp for when the session started.
- **Session End**: Timestamp for when the session ended.
- **Duration (mins)**: Total duration of the session.
- **Session Rating**: User rating for the session (out of 5).

### 3️⃣ **OrderDetails.csv**
- **Order ID**: Unique identifier for the order.
- **User ID**: Links the order to a specific user.
- **Order Date**: Date the order was placed.
- **Meal Type**: Type of meal (Breakfast, Lunch, Dinner, etc.).
- **Dish Name**: Name of the dish ordered.
- **Order Status**: Status of the order (Completed, Canceled, etc.).
- **Amount (USD)**: Total order amount in USD.
- **Time of Day**: Period when the order was placed (Morning, Day, Night, etc.).
- **Rating**: User rating for the order (out of 5).
- **Session ID**: Links the order to a specific cooking session.

---

## 🔍 **Key Objectives**
- **Data Cleaning & Merging**: Process and combine UserDetails, CookingSessions, and OrderDetails.
- **Analysis of User Behavior**: Identify user ordering behavior after cooking sessions.
- **Popular Dishes**: Find out which dishes are most popular among users.
- **Demographic Analysis**: Discover how demographic factors influence engagement.

---

## 📈 **Visualizations**
- **Top 10 Popular Dishes**: Displayed using bar plots.
- **User Engagement by Age**: Visualize user orders and sessions across different age groups.
- **Cooking Sessions vs Orders**: Analyze user engagement from cooking sessions to order placement.
- **Revenue Insights**: Understand how order amounts change based on meal types.

---

## 📝 **Business Recommendations**
- **Promote Popular Dishes**: Focus marketing on top dishes to increase sales.
- **Target High-Engagement Demographics**: Identify user groups with high activity (like specific age groups or regions) for targeted promotions.
- **Encourage Cooking-to-Order Conversion**: Suggest personalized offers right after a cooking session to convert users into buyers.

---

## 📧 **Contact**
For questions or feedback, please reach out to **[Abhishek Kumar]** at **[abhishek939.ak@gmail.com]**.

---

**Thank you for exploring this project!**

