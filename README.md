# Salary Range Classification

## Objective

The objective of this project is to develop a predictive model for salary range classification using demographic and employment-related data extracted from the 1994 Census database by Barry Becker. The dataset includes various attributes such as age, education, occupation, marital status, and hours worked per week.

### Goals
1. **Identify Key Features:** Explore the dataset to identify key demographic and employment-related features that influence salary levels.
2. **Build a Predictive Model:** Develop a machine learning model capable of accurately classifying individuals into two salary categories: those earning over 50,000 USD per year and those earning 50,000 USD or less.
3. **Utilize Classification Techniques:** Experiment with various classification techniques to determine the most effective approach for predicting salary ranges.
4. **Leverage Insights for Social Impact:** Use the model to assist in identifying individuals who may require further assistance, enabling targeted public policy initiatives and support programs.
5. **Facilitate Decision-Making:** Aid decision-making processes in both public and private sectors by providing insights into salary determinants and helping allocate resources effectively.

## Dataset

### About the Dataset

The dataset used in this project is the [1994 Census database](https://archive.ics.uci.edu/ml/datasets/adult) provided by Barry Becker. It includes demographic and employment-related information collected from individuals. Here is a description of the attributes present in the dataset:

1. **age:** Continuous variable representing the individual's age.
2. **workclass:** Represents the type of employment the individual is engaged in, such as Private, Self-employed, or Government.
3. **fnlwgt:** Continuous variable representing final weight.
4. **education:** Level of education attained by the individual (e.g., "Bachelors", "HS-grad", "Masters").
5. **education-num:** Continuous variable representing the number of years of education completed.
6. **marital-status:** Represents the marital status of the individual.
7. **occupation:** Represents the type of occupation held by each individual.
8. **sex:** Gender of the individual (e.g., Male or Female).
9. **race:** Ethnicity or racial background of the individual.
10. **relationship:** Type of relationship the individual has (e.g., Husband, Wife, Not-in-family).
11. **capital-gain:** Continuous variable representing the capital gains of individuals.
12. **capital-loss:** Continuous variable representing the capital losses of individuals.
13. **hours-per-week:** Continuous variable representing the number of hours worked per week by individuals.
14. **native-country:** Represents the country of origin or citizenship of the individual as reported in the dataset.
15. **salary:** Target variable indicating whether an individual earns more than 50,000 USD per year (1) or 50,000 USD or less (0).

## Methodology Summary

To achieve these objectives, the project will involve the following steps:

1. **Exploratory Data Analysis (EDA):** Understand the dataset's characteristics and relationships, identifying key features that influence salary ranges.
2. **Data Preprocessing:** Prepare the data for modeling by handling missing values, encoding categorical variables, and normalizing the data.
3. **Modeling:** Evaluate various classification algorithms, including:
   - Decision Trees
   - Random Forests
   - Support Vector Machines (SVM)
   - Logistic Regression
   - K-nearest Neighbours (KNN)

   The goal is to determine the most suitable model for accurately classifying salary ranges.

4. **Evaluation:** Assess the model's performance using metrics like accuracy, precision, recall, and F1-score to ensure the model's effectiveness in predicting salary ranges.

5. **Insights and Applications:** Utilize the insights gained from the model to support decision-making processes and develop targeted initiatives for social impact.

## Results

### Model Performance

Here is a summary of the performance of different models:

- **Logistic Regression:** Accuracy - 78.95%
- **K-nearest Neighbours (KNN):** Accuracy - 76.11%
- **Random Forest:** Accuracy - 85.28%
- **SVM:** Accuracy - 78.19%

Among these models, the Random Forest model demonstrated the highest accuracy at 85.28%, outperforming the others. Despite its complexity, it exhibited superior precision (0.74) and recall (0.64), resulting in an F1-score of 0.69. While SVM showed competitive performance with an accuracy of 78.19%, the Random Forest model emerged as the most effective for salary classification, showcasing its predictive power and suitability for deployment.

### Model Performance Visualizations

![Model Performance](path/to/your/image1.png)
*Figure 1: Model Performance Comparison*

![Confusion Matrix](path/to/your/image2.png)
*Figure 2: Confusion Matrix for Random Forest Model*

## Next Steps
- **Data Analysis:** Perform EDA and identify key features.
- **Model Development:** Build and train the predictive model.
- **Evaluation and Tuning:** Fine-tune the model and evaluate its performance.
- **Documentation:** Compile findings and insights to aid stakeholders in decision-making.

## Conclusion

This project aims to provide valuable insights into salary determinants and develop a robust predictive model that can have a meaningful impact on public policy and resource allocation. By accurately classifying salary ranges, the model can help identify individuals who may need further support and guide effective decision-making processes.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
