# ML Projects

## Projects

1. **Diabetes Prediction**  
   Predicts whether a person has diabetes or not based on health data.

2. **Rock vs Mine Classification**  
   Classifies sonar reads as rock or mine.

3. **Spam Mail Detection**  
   Classifies an email as spam or not based on text classification.

4. **Credit Card Fraud Detection**  
   Recognizes credit card fraud based on the behavior of credit card usage.

5. **Heart Disease Prediction**  
   Whether a person has a heart disease or not.

6. **House Price Prediction**  
   Predict the price of the houses.

7. **Loan Status Prediction**  
   Approval or rejection of the loan.

8. **Bike Sharing Demand Prediction**  
   Predict bike rentals based on weather and time attributes.

9. **Custom vs Sklearn Linear Regression on Student Exam Data**  
   Predicts student math grades using linear regression. This project contrasts a customLinear regression model (i.e., implemented from scratch) with Scikit-learn's `LinearRegression` to see how they compare in terms of performance.

10. **Real vs Fake Job Posting Detection (Custom vs Sklearn Logistic Regression)**  
    *Identifies spam job postings with text and binary features.*  
    I merged job description columns into one `text` column then used **TF-IDF Vectorizer** to transform the text into numerical features. The dataset was **strongly imbalanced** so undersampling was done to balance the classes. I made a logistic regression model from scratch and compared it to the one from sklearn. Finally I made bar charts to compare the accuracy between the two.

11. **Custom vs Library SVM: Performance Comparison on Breast Cancer Dataset**  
    I implemented a SVM from scratch and used it on breast cancer dataset. I compared its accuracy with the accuracy of the SVM from Scikit-learn. Surprisingly, my custom model performed slightly better.

12. **Lasso Regression from Scratch vs Scikit-Learn**  
    I used a custom lasso regression from scratch to predict the salary of a person. I compared my model with the one from sklearn to see which one performs better.

13. **Comparing Regression Models with Train-Test and Cross-Validation**  
    I compared LinearRegression, Lasso, RandomForestRegressor, and XGBRegressor on the Medical Cost dataset using R² as the evaluation metric. I also used cross-validation to observe differences in model performance.

14. **Big Mart Sales Prediction**  
    I Compared several regression models for sales prediction then I used RandomizedSearchCV on the top 2 models to improve their performance.
    
15. **Calories Burnt Prediction: Comparing Simple and Complex Models**  
    I compared several regression models (LinearRegression, Lasso, RandomForestRegressor, and XGBRegressor) to predict calories burnt based on exercise data.  
    I intentionally tried complex models like **XGBRegressor** and **RandomForestRegressor** to see if they would overfit.  
    Both models achieved a perfect **R² score of 1.0** during cross-validation, which likely indicates **overfitting** — possibly due to the simplicity of the dataset.  
    Therefore, I chose to stick with simpler models like **LinearRegression** and **Lasso**, which had slightly lower but more realistic R² scores and are less prone to overfitting.

16. **Anime Recommendation System**  
    Using the MyAnimeList dataset, I developed a content-based anime recommendation algorithm. I created a single text feature by combining high-level features like genres, synopsis, type, and aired date. After converting the text data into numerical vectors using TF-IDF Vectorizer, I utilized cosine similarity to determine how similar the animes were. Then I let the user input an anime name, and the system will recommend to him the top animes that are comparable.

    

    
    
