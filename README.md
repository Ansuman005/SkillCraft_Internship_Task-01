SCT_Task1 🏠 House Price Prediction - Linear Regression Project This project uses a Linear Regression model to predict house prices based on:

Square footage Number of bedrooms Number of bathrooms

You can run this project: ✅ Interactive Web Interface ✅ Real-time predictions 📂 Project Files

house-price-predictor.jsx → Complete React component with ML implementation README.md → This documentation file Synthetic Dataset → Generated training data (200 house records)

🔧 Requirements This project uses:

React 18+ Recharts (for visualization) Tailwind CSS (for styling) JavaScript ES6+

🎯 Features

✅ Multiple Linear Regression - From scratch implementation ✅ Real-time Predictions - Instant price updates ✅ Interactive Controls - Adjust square footage, bedrooms, bathrooms ✅ Performance Metrics - R-squared, RMSE displayed ✅ Data Visualization - Scatter plots and model performance charts ✅ Modern UI - Responsive design with gradient backgrounds

📊 Model Performance

R-Squared: 85-95% accuracy RMSE: ~$50,000-80,000 prediction error Training Data: 200 synthetic house records Algorithm: Normal Equation method

💡 Usage

Open the application in your web browser Adjust the input sliders:

Square Footage: 500-5000 sq ft Bedrooms: 1-8 rooms Bathrooms: 1-6 rooms

View real-time prediction - Price updates automatically Analyze model performance - Check R-squared and RMSE metrics

🔧 Technical Implementation The project implements multiple linear regression using the Normal Equation: Price = β₀ + β₁(sqft) + β₂(bedrooms) + β₃(bathrooms) Key Functions:

trainLinearRegression() - Trains the model using normal equation solveLinearSystem() - Gaussian elimination for coefficient calculation generateTrainingData() - Creates synthetic dataset Real-time prediction updates with React hooks

📈 Future Enhancements

Kaggle Dataset Integration - Use actual house price competition data Additional Features - Add location, age, garage size Advanced Models - Ridge regression, Random Forest Model Comparison - Side-by-side algorithm performance

🤝 Contributing Feel free to fork this repository and submit pull requests for improvements! 📄 License MIT License - feel free to use this project for learning and development.

⭐ Star this repository if you found it helpful!
