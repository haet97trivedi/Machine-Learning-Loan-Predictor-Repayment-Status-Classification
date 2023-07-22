<h1 align=center><font size = 5>Machine Learning Loan Predictor Repayment Status Classification</font></h1>

<h2>About the Project</h2>
<p>This project explores various machine learning algorithms to build a model for predicting loan repayment status, thus serving as an important tool for financial institutions. Our task is to train a model using a dataset containing past loans and details about 346 customers whose loans are either already paid off or defaulted. The algorithms used include K-Nearest Neighbors, Decision Trees, Support Vector Machines, and Logistic Regression.</p>

<h2>Data</h2>
<p>The dataset used, <code>Loan_train.csv</code>, includes details such as Loan status, Principal amount, Terms, Effective date, Due date, Age, Education, and Gender of the applicant. Each row in the dataset corresponds to a customer.</p>

<h2>Dependencies</h2>
<p>The libraries used in this project include:</p>
<ul>
<li>itertools</li>
<li>numpy</li>
<li>matplotlib.pyplot</li>
<li>pandas</li>
<li>sklearn.preprocessing</li>
<li>sklearn.model_selection</li>
<li>sklearn.neighbors</li>
<li>sklearn.tree</li>
<li>sklearn</li>
<li>sklearn.linear_model</li>
<li>sklearn.metrics</li>
</ul>

<h2>Workflow</h2>
<p> The project follows the below workflow: </p>

<h3>Data Preprocessing</h3>
<p>Data is loaded from the CSV file, and date-time objects are converted for processing. The loan status of the customers is then evaluated to understand the distribution of paid and defaulted loans. Data visualization is conducted for various columns like principal amount and age, across genders.</p>

<h3>Feature Selection/Extraction</h3>
<p>Further preprocessing is conducted, with new features like 'weekend' extracted to identify if people who get loans at the end of the week pay it off. Categorical features like gender and education are converted to numerical values and binary variables respectively.</p>

<h3>Model Development</h3>
<p>Multiple machine learning models are built, including:</p>
<ul>
<li>K Nearest Neighbors (KNN)</li>
<li>Decision Trees (DT)</li>
<li>Support Vector Machine (SVM)</li>
<li>Logistic Regression (LR)</li>
</ul>

<p>For KNN, the best 'k' is determined by training and predicting with different k values. For the other models, they are built with parameters suitable to the nature of the data.</p>

<h3>Model Evaluation</h3>
<p>Once all models are built, they are evaluated on a test dataset. Metrics such as Jaccard Index, F1-score, and LogLoss are used for assessing the models' performances.</p>

<h2>Results</h2>
<p>The performance of all the models was commendable, with SVM showing the highest accuracy. The accuracies were:</p>
<ul>
<li>KNN: Jaccard index: 0.67, F1-score: 0.63</li>
<li>Decision Tree: Jaccard index: 0.72, F1-score: 0.74</li>
<li>SVM: Jaccard index: 0.80, F1-score: 0.76</li>
<li>Logistic Regression: Jaccard index: 0.74, F1-score: 0.66, LogLoss: 0.57</li>
</ul>

<h2>Conclusion</h2>
<p>By successfully applying machine learning algorithms, the project effectively predicted the loan repayment status based on historical data. This project's findings are useful for banks and financial institutions, helping them make informed decisions and manage risks better. Additionally, the project demonstrates how machine learning can transform traditional industries and catalyze data-driven decision-making.</p>

</body>
</html>
