# Assignment 6 Part 2 - Writeup

---

## Question 1: Feature Importance

Based on your house price model, rank the four features from most important to least important. Explain how you determined this ranking.

**YOUR ANSWER:**
1. Most Important: Bedrooms
2. Bathrooms
3. Age
4. Least Important: SquareFeet

**Explanation:**
This ranking was determined by how much impacted the cost. Since square footage could be in the thousands, its importance per foot was very low. However, each bedroom significantly brought the cost up which made it the most important.



---

## Question 2: Interpreting Coefficients

Choose TWO features from your model and explain what their coefficients mean in plain English. For example: "Each additional bedroom increases the price by $___"

**Feature 1:**
Each additional square foot increases the price by $121.11

**Feature 2:**
Each additional bedroom increases the price by $6648.97

---

## Question 3: Model Performance

What was your model's R² score? What does this tell you about how well your model predicts house prices? Is there room for improvement?

**YOUR ANSWER:**

My R^2 score was 99.36%. This means that my model predicts house prices 99.36% accurately. Realistically there may not be much more to improve with a correlation that is that high of a percentage.


---

## Question 4: Adding Features

If you could add TWO more features to improve your house price predictions, what would they be and why?

**Feature 1:**
Distance from city

**Why it would help:**
Homes further away from cities tend to be cheaper as a result.

**Feature 2:**
Neighborhood safety

**Why it would help:**
The more violence that there is in an area, the prices of homes in that neighborhood would drop.

---

## Question 5: Model Trust

Would you trust this model to predict the price of a house with 6 bedrooms, 4 bathrooms, 3000 sq ft, and 5 years old? Why or why not? (Hint: Think about the range of your training data)

**YOUR ANSWER:**

I would trust the model with it as the graphs seem to be consistent and there aren't many external factors that would lower the cost of the house prices so I would trust the model.
