# House-Price-Prediction
This project uses Machine Learning to predict house prices based on size. It uses Linear Regression to learn from data and make predictions. It is a simple beginner project made with Python and scikit-learn.
from sklearn.linear_model import LinearRegression

X = [[500], [1000], [1500], [2000], [2500]]
y = [50000, 100000, 150000, 200000, 250000]

model = LinearRegression()
model.fit(X, y)

prediction = model.predict([[1200]])

print("Predicted house price:", prediction[0])
