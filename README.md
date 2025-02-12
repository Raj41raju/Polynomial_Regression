
# Polynomial Regression

Polynomial Regression is an extention of linear regression having best line is Non-linear or curved line instead of straight line.
The best fir curved included **higher-degree** terms like x 
2
 ,x 
3
 ,x 
4
  to the equation.

and 

y = a0 + a1 * x + a2 * x, a3.x**2 +_ _ _ + an*x**n

![image alt](https://github.com/Raj41raju/Polynomial_Regression/blob/main/Polynomial_Regg_BestFitCurve.png?raw=true)

### Choosing the Right Degree

#### : Choosing the Right Degree (How Much Curve?)
The degree of the polynomial controls how curvy the line is.

- **Degree = 1** → Simple linear regression (**straight line**).
- **Degree = 2 or 3** → Moderate curvature (**good fit**).
- **Degree = 10** → Very wiggly (**overfitting**).

#### ⚠️ The Trade-Off:
- 🔴 **Too Low (Underfitting)** → Model is **too simple**, doesn’t capture trends.
- 🟢 **Just Right** → Captures patterns **without going too extreme**.
- 🔵 **Too High (Overfitting)** → Model learns **random noise** instead of actual trends.

#### ✅ Best Practice:
- Start with a low degree and **gradually increase**.
- Use can use the  **cross-validation** to find the optimal degree.
- Avoid excessive complexity unless absolutely necessary.

![image alt](https://github.com/Raj41raju/Polynomial_Regression/blob/main/Polynomial_Regg_overfitting.png?raw=true)


## Key Points
 - Start with degree 1 and increase gradually.
- Use visualization to check the fit.
- Compare models using MSE, R², and cross-validation.
- Avoid overfitting with regularization techniques such Ridge and Lasso.
- Automate the search using Grid Search or AIC/BIC.
- when DoF is too high then model can be overfiting and when DoF is too low the model would be Underfitting.

#### 📌 Polynomial regression is used in many real-world scenarios, such as:

- 📉 Stock Price Prediction → Prices often follow non-linear patterns.
- 🚗 Self-Driving Cars → Predicting road curves.
- 🌡 Weather Forecasting → Predicting temperature changes.
- 📊 Marketing & Sales → Predicting revenue trends.
- ⚕ Medical Research → Disease progression modeling.

# Questions:
**Q. Although there is high degree of relationship between x and y, then why it is called a part of linear regression?**

Polynomial regression is considered a part of linear regression because, despite the presence of polynomial terms (e.g., x2, x,3), the model remains linear in parameters  means the linear relationship between coefficients, intercept and y (predicted value).
