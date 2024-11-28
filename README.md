# **DSA210_TermProject**

_A detailed analysis of Steam account data for the Sabancı University Data Science Analysis course (DSA210)._


## **Introduction**
This project is part of the Data Science Analysis (DSA210) course at Sabancı University. The aim is to analyze and derive meaningful insights from Steam account data. The analysis will utilize:
- **Steam API key** for fetching personal gaming data.
- **SteamDB**, a third-party platform, for enhanced and detailed game-specific data.

The project leverages my own Steam account data, including game names, playtime, purchase history, and game genres. This analysis will provide insights into personal gaming habits, game values, and trends in gameplay over time.

---

## **Project Goals**
The primary goals of this project are:
1. **Observing the relation between money spent and time spent**:
   - Analyzing if the cost of a game correlates with the time played.
2. **Dividing playtime according to game types**:
   - Identifying which genres (e.g., action, strategy, story) are most played.
3. **Exploring the relation between playtime and general game ratings**:
   - Investigating whether higher-rated games tend to be played more.

These goals will guide the analysis and visualization efforts throughout the project.

---

## **Project Overview**
The project is divided into two main stages:

1. **Data Collection**:
   - Using the **Steam API key** to extract:
     - Game names and total playtime (in minutes).
     - Purchase history, from the account's first day of activity to the present.
   - Using **SteamDB** to gather:
     - Game genres (e.g., action, strategy, story).
     - Current price, release date, overall rating, and other game-specific data.

2. **Derived Data Pool**:
   After assembling data from both sources, detailed and derived datasets will be created. Key metrics from SteamDB include:
   - **Account Value (Current Price)**: Based on today’s price (including discounts).
   - **Account Value (Lowest Price)**: Based on the recorded lowest price.
   - **Total Games**: Number of games in the account library.
   - **Total Games Played**: Number of games with recorded playtime.
   - **Hours on Record**: Total playtime across all games.
   - **Average Price per Game**: Total account value divided by the number of games.
   - **Average Price per Hour**: Includes only games with a price.
   - **Average Playtime per Game**: Total games played divided by hours on record.

The derived datasets will help in exploring trends and analyzing personal gaming patterns.

---

## **Dataset**
1. **Steam API Data**:
   - Extracted game list and total playtime (in minutes).
   - Purchase history data for every game in the account.

2. **SteamDB Data**:
   - Game metadata including:
     - Release date.
     - Overall rating.
     - Current price.
     - Genre classification (action, strategy, story, etc.).
   - Account-level metrics, such as:
     - Total account value (current and lowest price).
     - Total and average playtime.
     - Average price per game and price per hour.

---
