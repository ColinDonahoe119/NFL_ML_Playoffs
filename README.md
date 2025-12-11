# NFL Playoff Predictor
In this Project, I create a simple Logistic ML model that predicts NFL playoff teams based on offensive EPA per play and defensive EPA per play. EPA per play is an advanced metric that measures the average points added for every play. Offensives want highly positive EPA per play, and defenses want a highly negative EPA per play. Access to this dataset is free and found at https://data.scorenetwork.org/football/nfl-team-statistics.html

Before I made the model, I had to clean and manipulate the dataset. After doing so, I manually made functions to calculate sigmoid, cost, gradient, and gradient descent. Of course, some Python packages do this much easier, but manually creating the functions conceptually reinforced the math behind the code. At its current state, the model is incomplete. It can use a larger training set and more features such as strength of schedule, turnover margin, and special teams metrics. I plan on returning to improve the model and any advice/critiques are welcome!

<img width="1051" height="668" alt="image" src="https://github.com/user-attachments/assets/4b17add7-87a3-4858-95df-3cf22e5425f5" />


