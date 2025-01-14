# **Machine Learning for Predicting Constitutive Relationships in Structural Adhesives**

## **Project Overview**
This project demonstrates the application of machine learning techniques to predict stress-strain relationships for structural adhesives. The primary aim is to replace computationally expensive finite element analysis (FEA) with efficient and accurate ML models.

### Key Features:
- Dataset generated through FEA simulations.
- Models include regression techniques (Linear, Lasso, Ridge, Polynomial, and Support Vector Regression) and advanced ML models (XGBoost and Neural Networks).
- Focus on computational efficiency and predictive accuracy.

---

## **Dataset**
The dataset used in this project was generated using finite element modeling (FEM). 

### Features:
- **Inputs:** Strain components (`X`, `Y`, `Z`, `XY`, `YZ`, `ZX`, and Effective Strain).
- **Outputs:** Stress components (`ZX-Stress` and `Effective Stress`).

### Datasets:
- **Set A:** Bi-linear stress-strain relationship.
- **Set B:** Stress-strain data for different input variations.

---

## **Machine Learning Models**
### Regression Models:
1. Linear Regression
2. Lasso Regression
3. Ridge Regression
4. Polynomial Regression
5. Support Vector Regression

### Advanced Models:
- **XGBoost**: High performance in computational efficiency and predictive accuracy.
- **Neural Networks**: Feedforward networks with multiple dense layers.

Model performance is evaluated using metrics such as **RMSE** and **R²**.

---

## **Results**
- **Best Models**: XGBoost and Neural Networks.
- **Performance Highlights**:
  - **XGBoost**: `RMSE = 0.0108`, `R² = 0.99756`
  - **Neural Network**: `RMSE = 0.0121`, `R² = 0.99722`
- **Comparison**: XGBoost was computationally more efficient while providing high predictive accuracy.

---

## **Conclusion & Future Work**
This project provides proof of concept for using machine learning to model constitutive relationships in structural adhesives.

### Future Improvements:
- Expanding the dataset with more complex FEA models.
- Optimizing neural network architectures for higher accuracy.
