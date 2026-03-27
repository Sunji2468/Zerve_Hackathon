# Zerve_Hackathon

## What is this project?
This project was built for a data science hackathon. It looks at thousands of rows of user data to answer one big question: Why do some people keep using the app, while others quit?

Instead of just guessing, we built a machine learning model to find the exact actions that turn a new signup into a long-term power user.

## The Big Discoveries
By looking at what users do in their first 14 days, we found three major secrets to success:

* **The Magic Number is 3:** Users who explore and visit at least 3 different pages are much more likely to stick around. Clicking around is the biggest sign of success.
* **Day 1 is Everything:** The best users don't wait. They try the AI features and spend their first credits on the exact same day they sign up. 
* **Busy Users Stay:** People who take over 100 actions (like clicking, running tools, or searching) in their first two weeks almost never quit.

## How We Built It
* **Clean Data:** We took a massive dataset of over 400,000 events and simplified it down to the most important user behaviors.
* **Machine Learning:** We trained a predictive model (Gradient Boosting) that looks at a user's first two weeks and predicts if they will stay or leave with very high accuracy. 
* **Live Dashboard:** We built an interactive web app using Streamlit. You can move sliders to change a fake user's behavior (like how many pages they visit) and watch their chance of success go up or down in real-time.

## Business Advice
Based on the math, we recommend the product team changes how new users are welcomed:
1. Make a checklist that forces new users to visit 3 different pages.
2. Give them a reward for trying an AI tool within their first 24 hours.

## Tools Used
* Python (Pandas, NumPy)
* Machine Learning (Scikit-Learn, XGBoost)
* Data Visualization (Matplotlib, Seaborn)

## Check the Notebook ##
https://app.zerve.ai/notebook/879822a0-0048-412a-8dfd-b2a6254752ba
