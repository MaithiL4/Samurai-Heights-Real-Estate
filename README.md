# Samurai-Heights-Real-Estate
# We are given dataset of house prices with some features like no of bathrooms, no of bedrooms, etc.
# we have to  create a model which will predict the price for any new house by looking at the features.
# The first question we should ask is what is the business objective and end goal? How will Samurai-Heights-Real-Estate benefit from the model?
# Samurai-Heights-Real-Estate will use this model to predict house prices in a given area and will invest in the area if its undervalued.

# Finding the type of model to build.
1. Supervised, unsupervised, or Reinforcement Learning? = Supervised because we have  labels and Feature.
2. Classification task or Regression task? = Regression because we nedd price prediction.
3. Batch learning or online learning techniques? = Batch learning because we have datase.

# Selecting a performance measure.
1. A typical performance measure for regression problems is the Root Mean Square Error (RMSE).
2. RMSE is generally the preferred performance measure for regression tasks, so we choose it for this particular problem we are solving for Samurai-Heights real estates Pvt. Ltd.
3. Other performance measures include Mean Absolute Error, Manhattan norm, etc but we will use RMSE for this problem.

# Checking the assumptions.
1. It is very important to check for any assumptions we might have made and correct them before launching the ml system
2. For example, he should make sure that the team needs the price and not the categories like expensive, cheap, etc.
3.If latter is the case, formulating the problem as a regression task will be counted as a big mistake.
4. We talked to the Samurai-Heights-Real-Estate team members and ensured that we all are aware of all the assumptions.

# WE are using jupyter Notebook. it make it easy to document and use the code as a notebook.
