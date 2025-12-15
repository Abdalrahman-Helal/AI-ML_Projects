# AI and Machine Learning Projects Collection

This repository serves as a comprehensive collection of projects demonstrating various Artificial Intelligence (AI) and Machine Learning (ML) concepts, algorithms, and applications. The projects range from classical search algorithms for games and pathfinding to practical machine learning models for data analysis and prediction.

## Repository Structure

The repository is organized into distinct folders, each representing a self-contained project.

| Project Folder | Description | Key Concepts |
| :--- | :--- | :--- |
| `Maze/` | Implementations of various search algorithms to solve a maze. | Uninformed Search, Informed Search, Pathfinding |
| `TelcoCustomerChurn/` | A machine learning project focused on predicting customer churn for a telecommunications company. | Data Preprocessing, Exploratory Data Analysis (EDA), Classification, Machine Learning |
| `TicTacToe/` | AI implementations for the classic game of Tic-Tac-Toe using different search strategies. | Game Theory, Search Algorithms, State-Space Search |

---

## Project Details

### 1. Maze Solver (`Maze/`)

This project explores the application of both uninformed and informed search algorithms to find a path from a starting point to an end point in a maze. The implementations provide a clear comparison of how different search strategies perform in terms of efficiency and path optimality.

**Implemented Algorithms:**

*   **Uninformed Search:**
    *   Breadth-First Search (BFS)
    *   Depth-First Search (DFS)
    *   Depth-Limited Search (DLS)
    *   Iterative Deepening Search (IDS)
    *   Uniform Cost Search (UCS)
*   **Informed Search:**
    *   Greedy Best-First Search
    *   A\* Search

### 2. Telco Customer Churn Prediction (`TelcoCustomerChurn/`)

This is a data science project that utilizes the **Telco Customer Churn Dataset** to build a predictive model. The goal is to identify customers who are likely to discontinue their service (churn) based on various features such as contract type, services used, and monthly charges.

The project includes:

*   **Exploratory Data Analysis (EDA):** Visualizing data distributions and relationships between features and the target variable (`Churn`).
*   **Data Preprocessing:** Handling missing values, encoding categorical variables, and scaling numerical features.
*   **Model Building:** Training and evaluating classification models (e.g., Logistic Regression, Decision Trees, Random Forest) to predict churn.

**Key Files:**

*   `Telco-Customer-Churn.ipynb`: The main Jupyter Notebook containing the analysis and model development.
*   `Telco-Customer-Churn.csv`: The dataset used for the project.

### 3. Tic-Tac-Toe AI (`TicTacToe/`)

This project implements AI agents for the game of Tic-Tac-Toe using fundamental search algorithms. The AI determines the optimal move by exploring the game state space.

**Implemented Algorithms:**

*   Breadth-First Search (BFS)
*   Depth-First Search (DFS)
*   Greedy Search

---
