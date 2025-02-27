# Lab Exercise: Decision Tree

## Objective:
- Learn how to calculate **Information Gain (ID3)** and **Gini Impurity (CART)** for attribute selection.
- Construct decision trees manually and compare the ID3 and CART algorithms.
- Implement ID3 and CART from scratch in Python (without using built-in classifiers).

---

## Dataset:

The dataset consists of customer attributes and their class labels, indicating whether they purchased a computer.

| RID | age          | income  | student | credit_rating | Class: buys_computer |
|-----|--------------|---------|---------|---------------|-----------------------|
| 1   | youth        | high    | no      | fair          | no                    |
| 2   | youth        | high    | no      | excellent     | no                    |
| 3   | middle_aged  | high    | no      | fair          | yes                   |
| 4   | senior       | medium  | no      | fair          | yes                   |
| 5   | senior       | low     | no      | fair          | yes                   |
| 6   | senior       | low     | yes     | excellent     | no                    |
| 7   | middle_aged  | low     | yes     | excellent     | yes                   |
| 8   | youth        | medium  | yes     | fair          | yes                   |
| 9   | youth        | low     | yes     | fair          | yes                   |
| 10  | senior       | medium  | yes     | fair          | yes                   |
| 11  | youth        | medium  | yes     | excellent     | yes                   |
| 12  | middle_aged  | medium  | no      | excellent     | yes                   |
| 13  | middle_aged  | high    | yes     | fair          | yes                   |
| 14  | senior       | medium  | no      | excellent     | no                    |

---

## Exercise:

### 1. Compute Entropy and Information Gain (ID3)
- Calculate the **Entropy** of the dataset.
- Compute **Information Gain** for each attribute.
- Identify the best attribute for splitting based on **Information Gain**.
- Manually construct the first few levels of the **ID3 Decision Tree**.

---

### 2. Compute Gini Impurity (CART)
- Compute the **Gini Impurity** for each attribute.
- Identify the best attribute for splitting based on the lowest **Gini Index**.
- Manually construct the first few levels of the **CART Decision Tree**.

---

### 3. Implement ID3 and CART in Python
- Write a Python function to:
  - Compute **Entropy** and **Information Gain** and select the best attribute for splitting (**ID3**).
  - Compute **Gini Impurity** and select the best attribute for splitting (**CART**).
- Construct a **Decision Tree** from scratch without using `DecisionTreeClassifier`.

---

### 4. Compare ID3 vs. CART
- **Questions**:
  - Which attribute was chosen first in ID3? Why?
  - Which attribute was chosen first in CART? Why?
  - How do the resulting decision trees differ?
  - Which method is better when dealing with continuous variables?
