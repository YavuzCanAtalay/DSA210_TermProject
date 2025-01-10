# **DSA210_TermProject**

Welcome to the **Steam Account Data Analysis** project repository!

My name is **Yavuz Can Atalay (32445)**, and I am a sophomore Computer Science student at **Sabancı University**. This project is part of the **Data Science Analysis (DSA210)** course and serves as the term project for the class. It involves a detailed analysis of my personal Steam account data collected over the past ten years. Through this analysis, I aim to answer specific research questions and derive meaningful insights about my own gaming habits and about what I enjoy.

---

## **Introduction**

This project focuses on analyzing data from my own Steam account using modern data science techniques. By utilising the **Steam API** and **SteamDB**, I aim to extract, clean, and analyze my gaming data accumulated over a decade. The ultimate goal is to uncover meaningful patterns and answer questions related to my spending habits, my gameplay preferences, and the correlation between game ratings and playtime.

### **Key Tools and Resources**
- **Steam API Key**: For fetching personal gaming data directly from Steam.
- **SteamDB**: A third-party platform providing enhanced and detailed game-specific data.

The project will involve data such as game titles, playtime, purchase history, genres, and more, enabling a comprehensive analysis of gaming behavior.

---

## **Project Goals**

The primary objectives of this project are:

1. **Analyze the relationship between money spent and time spent on games**:
   - Investigate whether the cost of a game correlates with the amount of time played.
   - Hypothesis: Games that cost more are associated with longer playtimes compared to cheaper games.
2. **Explore the link between playtime and game ratings**:
   - Examine if I have played higher-rated games more frequently or do I have a distinctive taste.
   - Hypothesis: Games with higher average ratings have a positive correlation with total playtime.

---

## **Project Workflow**

The project consists of two main stages:

### **1. Data Collection**
Data will be collected from the following sources:
- **Steam API**:
  - Game list and total playtime (in minutes).
  - Purchase history for all games in the account, spanning from the first purchase to the present.
- **SteamDB**:
  - Additional game metadata, including:
    - Release dates.
    - Overall ratings.
    - Current prices and historical lowest prices.
    - Genre classification (action, strategy, etc.).

### **2. Derived Data Analysis**
After gathering and organizing the data, I will create derived datasets for analysis. Key properties to be calculated include:
- **Account Value (Current Price)**: Sum of current prices for all games.
- **Account Value (Lowest Price)**: Sum of the historically lowest prices for all games.
- **Total Games**: Number of games in the account.
- **Total Games Played**: Number of games with recorded playtime.
- **Total Playtime (Hours on Record)**: Sum of playtime across all games.
- **Average Price per Game**: Account value divided by the number of games.
- **Average Price per Hour Played**: For games with a price and recorded playtime.
- **Average Playtime per Game**: Total playtime divided by the number of games played.

---

## **Dataset Overview**

The datasets used in this project consist of the following components:

1. **Steam API Data**:
   - Extracted game list.
   - Total playtime (in minutes) for each game.
   - Purchase history for all games.

_Here is a small and basic part of steam API key data set and a small part of steam purchase history:_







---
   
2. **SteamDB Data**:
   - Game-specific metadata, such as:
     - Release date.
     - Overall rating.
     - Current price and historical lowest price.
     - Genre classification.
   - Account-level summaries, such as:
     - Total account value (current and lowest price).
     - Total playtime.
     - Average playtime, price per game, and price per hour.
     - 


# **Data File Access Links**
---
You can use this section in order to access prefered data set:

You can access Data file from here -> 
[DataFile access](https://github.com/YavuzCanAtalay/DSA210_TermProject/blob/main/DataFile/AllSteamDatas.md)


If you want to learn more about SteamDB you can wisit its website from here -> 
[SteamDB website](https://steamdb.info/#:~:text=Database%20of%20everything%20on%20Steam,about%20SteamDB%2C%20join%20our%20Discord.)








## **Expected Outcomes**

By the end of the project, I aim to:
- Visualize trends in personal gaming behavior over time.
- Quantify the relationship between spending and playtime.
- Identify favorite genres and their share of total playtime.
- Examine whether higher-rated games lead to increased engagement.
- Illustrate if there is a correlation between a game's release date and total playtime.


Feel free to explore the repository and its contents.
