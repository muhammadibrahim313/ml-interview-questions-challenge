# 🧠 ML Interview Questions — 30-Day Challenge

150 multiple-choice questions covering core Machine Learning and Data Science concepts. 5 questions per day, 30 days, with detailed answers and explanations.

Built for building **muscle memory** around ML fundamentals — no deep learning, just the classics.

## 📌 What's Inside

- **150 MCQs** across 30 topics
- **Detailed explanations** with intuitive examples
- **Topic-based resources** for deeper learning
- Focused on **classical ML & data science** (regression, classification, clustering, feature engineering, statistics, etc.)

## 📅 Challenge Roadmap

| Day | Topic | Status |
|-----|-------|--------|
| 01 | [ML Basics & Types of Learning](#day-01--ml-basics--types-of-learning) | ✅ |
| 02 | [Overfitting & Underfitting](#day-02--overfitting--underfitting) | ✅ |
| 03 | [Train/Test Split & Cross-Validation](#day-03--trainttest-split--cross-validation) | ✅ |
| 04 | [Linear Regression](#day-04--linear-regression) | ✅ |
| 05 | [Regression Assumptions & Diagnostics](#day-05--regression-assumptions--diagnostics) | ✅ |
| 06 | [Logistic Regression](#day-06--logistic-regression) | ✅ |
| 07 | [Confusion Matrix & Classification Metrics](#day-07--confusion-matrix--classification-metrics) | ✅ |
| 08 | [F1 Score, ROC & AUC](#day-08--f1-score-roc--auc) | ✅ |
| 09 | [Multi-class Metrics](#day-09--multi-class-metrics) | ✅ |
| 10 | [Decision Trees](#day-10--decision-trees) | ✅ |
| 11 | [Random Forests](#day-11--random-forests) | ✅ |
| 12 | [Bagging vs Boosting](#day-12--bagging-vs-boosting) | ✅ |
| 13 | [Support Vector Machines](#day-13--support-vector-machines) | ✅ |
| 14 | [K-Nearest Neighbors](#day-14--k-nearest-neighbors) | ✅ |
| 15 | [Naive Bayes](#day-15--naive-bayes) | ✅ |
| 16 | [K-Means Clustering](#day-16--k-means-clustering) | ✅ |
| 17 | [Clustering Methods (DBSCAN, Hierarchical)](#day-17--clustering-methods) | ✅ |
| 18 | [Feature Engineering](#day-18--feature-engineering) | ✅ |
| 19 | [Feature Selection](#day-19--feature-selection) | ✅ |
| 20 | [Handling Missing Data](#day-20--handling-missing-data) | ✅ |
| 21 | [Handling Imbalanced Data](#day-21--handling-imbalanced-data) | ✅ |
| 22 | [Dimensionality Reduction (PCA, t-SNE)](#day-22--dimensionality-reduction) | ✅ |
| 23 | [Regularization (L1, L2, Elastic Net)](#day-23--regularization) | ✅ |
| 24 | [Probability & Statistics Basics](#day-24--probability--statistics-basics) | ✅ |
| 25 | [Probability Distributions](#day-25--probability-distributions) | ✅ |
| 26 | [Gradient Descent](#day-26--gradient-descent) | ✅ |
| 27 | [Model Selection & Hyperparameters](#day-27--model-selection--hyperparameters) | ✅ |
| 28 | [Practical ML Concepts](#day-28--practical-ml-concepts) | ✅ |
| 29 | [Data Preprocessing](#day-29--data-preprocessing) | ✅ |
| 30 | [ML Pipeline & Final Review](#day-30--ml-pipeline--final-review) | ✅ |

## 🚀 How to Use

1. Try answering the 5 questions **without looking at the answers**
2. Check the answers and read the explanations
3. If a topic feels weak, check the **resources** section for that day
4. Repeat and revisit — build muscle memory!

---

## Day 01 — ML Basics & Types of Learning

### Questions

**1.** Which of the following is an example of unsupervised learning?
- a) Spam email detection
- b) Customer segmentation using clustering
- c) Predicting house prices
- d) Image classification

**2.** What does the bias-variance tradeoff describe?
- a) The tradeoff between training speed and accuracy
- b) The tradeoff between model complexity and generalization
- c) The tradeoff between data size and feature count
- d) The tradeoff between precision and recall

**3.** Overfitting occurs when:
- a) The model performs well on training data but poorly on unseen data
- b) The model performs poorly on both training and test data
- c) The model is too simple to capture patterns
- d) The training dataset is too large

**4.** Which of the following is NOT a type of machine learning?
- a) Supervised Learning
- b) Unsupervised Learning
- c) Reinforcement Learning
- d) Descriptive Learning

**5.** In supervised learning, the model learns from:
- a) Unlabeled data only
- b) Labeled data with input-output pairs
- c) Reward signals from the environment
- d) Random data sampling

### Answers

<details>
<summary>Click to reveal answers</summary>

**1. b) Customer segmentation using clustering**

Clustering groups similar customers together WITHOUT any labels. Spam detection, house prices, and image classification all use labeled data — that's supervised learning.

**2. b) The tradeoff between model complexity and generalization**

Simple models have high bias (underfit) and low variance. Complex models have low bias but high variance (overfit). The sweet spot is in the middle. A straight line through curvy data = high bias. A super wiggly line = high variance.

**3. a) The model performs well on training data but poorly on unseen data**

Overfitting means the model memorized the training data instead of learning the actual pattern. Like memorizing answers for one specific test but failing a different test on the same topic. Option (b) describes underfitting.

**4. d) Descriptive Learning**

The three main types of ML: Supervised, Unsupervised, and Reinforcement Learning. "Descriptive Learning" is not a standard ML category.

**5. b) Labeled data with input-output pairs**

Supervised learning needs a "teacher" — labeled examples where both the input (features) and output (target) are known. Example: 1000 emails labeled "spam" or "not spam" and the model learns the pattern.

</details>

### Resources


* **Types of ML (Supervised vs. Unsupervised)**
* [MLU-Explain: Types of Machine Learning](https://www.google.com/search?q=https://mlu-explain.github.io/machine-learning-types/) – Visual interactive essay on learning paradigms.


* **Bias-Variance Tradeoff**
* [StatQuest: Bias and Variance](https://www.youtube.com/watch?v=EuBBz3bI-aA) – Clear explanation of model complexity (MCQ 2).
* [Scott Fortmann-Roe: The Tradeoff](http://scott.fortmann-roe.com/docs/BiasVariance.html) – The definitive technical article on the "sweet spot."


* **Overfitting & Underfitting**
* [MLU-Explain: Cross-Validation](https://mlu-explain.github.io/cross-validation/) – Visualizes how models fail on unseen data (MCQ 3).

* **Foundation Summary**
* [StatQuest: ML Fundamentals Playlist](https://www.youtube.com/playlist?list=PLblh5JKOoLUICTaGLRoHQDuF_7q2GfuJF) – Comprehensive visual series for Day 01 topics.


---

## Day 02 — Overfitting & Underfitting

### Questions

**1.** Which technique helps prevent overfitting?
- a) Increasing model complexity
- b) Removing training data
- c) Adding regularization
- d) Removing validation data

**2.** Underfitting is characterized by:
- a) High training accuracy, low test accuracy
- b) Low training accuracy, low test accuracy
- c) High training accuracy, high test accuracy
- d) Low training accuracy, high test accuracy

**3.** If a model has high variance, what should you do?
- a) Use a more complex model
- b) Add more features
- c) Collect more training data or simplify the model
- d) Remove the test set

**4.** The training error is always _____ the test error in typical scenarios.
- a) Greater than
- b) Less than or equal to
- c) Equal to
- d) Unrelated to

**5.** Which of the following increases the risk of overfitting?
- a) More training data
- b) Fewer features
- c) Very deep decision tree with no pruning
- d) Strong regularization

### Answers

<details>
<summary>Click to reveal answers</summary>

**1. c) Adding regularization**

Regularization adds a penalty for complexity, telling the model "keep it simple!" L1 (Lasso) and L2 (Ridge) are the most common types.

**2. b) Low training accuracy, low test accuracy**

Underfitting means the model is too simple to capture the underlying pattern. It fails on BOTH training and test data. Like fitting a straight line to a clearly curved relationship.

**3. c) Collect more training data or simplify the model**

High variance means the model is too sensitive to training data. More data helps generalize. Simpler model or regularization also works. Adding complexity makes it worse.

**4. b) Less than or equal to**

Models optimize on training data, so they naturally perform better on it. If test error is much higher than training error, that's a sign of overfitting.

**5. c) Very deep decision tree with no pruning**

An unlimited tree memorizes every training example, including noise. More data (a) and regularization (d) actually PREVENT overfitting.

</details>

### Resources

* **How to handle High Variance**
* [Dealing With High Bias and Variance](https://medium.com/data-science/contents-9b2e49f49fe9) – A clear overview of Varinace, Bias, Regularization, how adding more data reduces high variance. He literally explains everything in detail in his **medium** post. (MCQ 1,2,3 & 4)
  
* **Overfitting and it's prevention**
* [Overfitting - What is it and how to prevent it?](https://www.ibm.com/topics/overfitting) – A clear, high-level overview of Overfitting and the most common techniques like Lasso, Ridge, and Dropout. (MCQ 1,2 & 3)

* **Regularization**
* [Regularization in Machine Learning](https://towardsdatascience.com/regularization-in-machine-learning-76441ddcf99a) – A deeper dive into the math behind L1 and L2 regularization and how it affects our model. (MCQ 1)

* **Overfitting in Decision Trees**
* [Overfitting and Pruning in Decision Trees](https://medium.com/nerd-for-tech/overfitting-and-pruning-in-decision-trees-improving-models-accuracy-fdbe9ecd1160) – Ovefitting in Decision trees and how to increase models accuracy using Pre-pruning, Post-Pruning and it's implementation using scikit-learn. (MCQ 5)
---

## Day 03 — Train/Test Split & Cross-Validation

### Questions

**1.** Why do we split data into training and test sets?
- a) To speed up training
- b) To evaluate model performance on unseen data
- c) To increase the dataset size
- d) To reduce overfitting during training

**2.** In k-fold cross-validation with k=5, how many times is the model trained?
- a) 1
- b) 3
- c) 5
- d) 10

**3.** What is the main advantage of cross-validation over a single train/test split?
- a) It's faster
- b) It gives a more reliable estimate of model performance
- c) It eliminates the need for a test set
- d) It always improves accuracy

**4.** Stratified k-fold cross-validation ensures:
- a) Equal number of samples in each fold
- b) Each fold has the same class distribution as the full dataset
- c) Features are normalized in each fold
- d) The model trains faster

**5.** Data leakage occurs when:
- a) The test set is too large
- b) Information from the test set influences model training
- c) The model underfits
- d) Cross-validation is not used

### Answers

<details>
<summary>Click to reveal answers</summary>

**1. b) To evaluate model performance on unseen data**

The test set acts as "unseen data" to check if your model generalizes or just memorized training data.

**2. c) 5**

In 5-fold CV, data is split into 5 parts. Each fold takes turns being the validation set while the other 4 are used for training. Model trains 5 separate times and results are averaged.

**3. b) It gives a more reliable estimate of model performance**

A single split can be lucky or unlucky depending on which data falls where. CV uses ALL data for both training and validation across different folds, giving a stable and trustworthy performance estimate.

**4. b) Each fold has the same class distribution as the full dataset**

If your dataset has 90% class A and 10% class B, stratified ensures each fold also has roughly 90%/10%. Without it, some folds might have 0% of the minority class, giving misleading results.

**5. b) Information from the test set influences model training**

Data leakage is accidental cheating. Example: normalizing the ENTIRE dataset (including test) before splitting. The model "sees" test data statistics during training. Always fit transformations on training data only.

</details>

### Resources

* **Train/Test Split & Generalization**
* [MLU-Explain: Train, Test, and Validation](https://mlu-explain.github.io/train-test-validation/) – Interactive visualization showing why we need unseen data (MCQ 1).
* [StatQuest: Training and Testing](https://www.youtube.com/watch?v=fSytzGwwBVw) – A simple, visual breakdown of the basic split logic.


* **K-Fold Cross-Validation**
* [Scikit-Learn: Cross-Validation Guide](https://scikit-learn.org/stable/modules/cross_validation.html) – The industry standard visual for how folds rotate (MCQ 2 & 3).
* [StatQuest: K-fold Cross-Validation](https://www.youtube.com/watch?v=fSytzGwwBVw) – Visualizes how the model trains $k$ times to get a reliable average.


* **Stratified Splits**
* [Machine Learning Mastery: Stratified K-Fold](https://www.google.com/search?q=https://machinelearningmastery.com/cross-validation-iterator-algorithms-in-python/) – Explains why maintaining class distribution matters for imbalanced data (MCQ 4).


* **Data Leakage (The "Cheating" Problem)**
* [Kaggle: Data Leakage](https://www.kaggle.com/code/alexisbcook/data-leakage) – A critical tutorial on how to avoid accidentally letting test info into training (MCQ 5).
* [Towards Data Science: Data Leakage in ML](https://towardsdatascience.com/data-leakage-in-machine-learning-6161c167e8ba/) – Practical examples of what to watch out for during preprocessing.



---

## Day 04 — Linear Regression

### Questions

**1.** Linear regression assumes a _____ relationship between input and output.
- a) Exponential
- b) Linear
- c) Polynomial
- d) Logarithmic

**2.** The coefficient (slope) in linear regression represents:
- a) The prediction error
- b) The change in y for a one-unit change in x
- c) The intercept value
- d) The R-squared score

**3.** The cost function most commonly used in linear regression is:
- a) Cross-entropy loss
- b) Hinge loss
- c) Mean Squared Error (MSE)
- d) Log loss

**4.** If R² = 0.85, it means:
- a) The model is 85% accurate
- b) 85% of the variance in the target is explained by the model
- c) The error rate is 15%
- d) The model has 85% precision

**5.** Multicollinearity in linear regression means:
- a) The target variable has multiple values
- b) Two or more features are highly correlated with each other
- c) The model has multiple outputs
- d) The residuals are not normally distributed

### Answers

<details>
<summary>Click to reveal answers</summary>

**1. b) Linear**

Linear regression fits a straight line: y = mx + b. It assumes the relationship between features and target is linear. For curved patterns, you'd need polynomial regression or other models.

**2. b) The change in y for a one-unit change in x**

If slope = 3 for feature "area," then for every 1 sq.ft increase in area, the predicted price increases by 3 units. The slope tells you the strength and direction of each feature's effect.

**3. c) Mean Squared Error (MSE)**

MSE = average of (actual - predicted)². It penalizes larger errors more heavily. Cross-entropy and Log loss are for classification. Hinge loss is for SVMs.

**4. b) 85% of the variance in the target is explained by the model**

R² measures how much of the target's variability is captured by your model. R²=1.0 means perfect fit. R²=0 means the model explains nothing. It's NOT the same as accuracy.

**5. b) Two or more features are highly correlated with each other**

If "height in cm" and "height in inches" are both features, they're perfectly correlated. This makes coefficients unstable and hard to interpret. Fix: remove one, use PCA, or use regularization.

</details>

### Resources

> 
* **Core Concepts & Slope Intuition (MCQ 1 & 2)**
* [StatQuest: Linear Regression Step-by-Step](https://www.youtube.com/watch?v=PaFPbb66DxQ) — The absolute best visual breakdown of how the line is fitted and what the slope actually means.


* **Cost Function: Mean Squared Error (MCQ 3)**
* [MLU-Explain: Linear Regression](https://mlu-explain.github.io/linear-regression/) — An interactive essay where you can move data points and see how the MSE "penalizes" the error visually.
* [Cost Function Mathematical Explanation](https://builtin.com/machine-learning/cost-function)


* **Model Evaluation: R-Squared (MCQ 4)**
* [StatQuest: R-squared Explained](https://www.youtube.com/watch?v=2AQKmw14mHM) — Explains $R^2$ as "Variation explained by the model / Total variation" using clear, simple charts.

* **The Problem of Multicollinearity (MCQ 5)**
* [Towards Data Science: Multicollinearity in Regression](https://towardsdatascience.com/handling-multi-collinearity-6579eb99fd81/) — Explains why correlated features make coefficients "unstable" and how to detect it using VIF (Variance Inflation Factor).
* [Statistics by Jim: Multicollinearity](https://statisticsbyjim.com/regression/multicollinearity-in-regression-analysis/) — A great resource for understanding the "hidden" problems that occur when features overlap.



---

## Day 05 — Regression Assumptions & Diagnostics

### Questions

**1.** Which is NOT an assumption of linear regression?
- a) Linearity between features and target
- b) Independence of residuals
- c) Features must be categorical
- d) Constant variance of residuals (homoscedasticity)

**2.** What is homoscedasticity?
- a) Residuals increase as predictions increase
- b) Residuals have constant variance across all levels of the predictor
- c) All features have the same scale
- d) The target is normally distributed

**3.** If residuals show a clear curved pattern when plotted against predictions, this suggests:
- a) The model is perfect
- b) The linear assumption is violated
- c) The model has low variance
- d) Regularization is needed

**4.** Adjusted R² differs from R² because it:
- a) Is always higher than R²
- b) Penalizes for the number of features used
- c) Only works for classification
- d) Ignores the intercept

**5.** Which metric is more robust to outliers than MSE?
- a) R²
- b) Mean Absolute Error (MAE)
- c) Max Error
- d) Variance

### Answers

<details>
<summary>Click to reveal answers</summary>

**1. c) Features must be categorical**

Linear regression assumptions: linearity, independence of errors, homoscedasticity, normality of residuals. Features can be continuous OR categorical (encoded as dummies). "Must be categorical" is false.

**2. b) Residuals have constant variance across all levels of the predictor**

If errors get larger for bigger predictions (fan shape), that's heteroscedasticity — a violation that makes confidence intervals unreliable.

**3. b) The linear assumption is violated**

Patterned residuals mean the model is missing something — likely a non-linear relationship. Fix: add polynomial features, use a non-linear model, or apply feature transformations.

**4. b) Penalizes for the number of features used**

R² always increases when you add features, even useless ones. Adjusted R² corrects by penalizing extra features. If a new feature doesn't help, adjusted R² can actually decrease.

**5. b) Mean Absolute Error (MAE)**

MSE squares errors, so one huge outlier dominates. MAE takes absolute values — a 100-unit error counts as 100, not 10,000. MAE treats all errors proportionally.

</details>

### Resources

* **Assumptions of Linear Regression and Homoscedasticity**
* [Asssumptions of Linear Regression](https://www.analyticsvidhya.com/blog/2016/07/deeper-regression-analysis-assumptions-plots-solutions/) – This is one of the most comprehensive articles for beginners. It specifically addresses Homoscedasticity (Question 2) and the Independence of residuals (Question 1) with clear "Funnel" and "Random" scatter plot examples.

* **R² and Adjusted R²**
* [How Adjusted R² differs and penalize the features](https://alok05.medium.com/r-squared-and-adjusted-r-squared-in-machine-learning-33df28d54ca4) - A deep understanding of R² and Adusted R² with examples and intuition.

* **Residual analysis**
* [Residual plots and Non-linearity](https://www.geeksforgeeks.org/machine-learning/residual-plots-for-nonlinear-regression/) - This resource explains the residual analysis, it's purposes, how to plot and spot non-linearity in data.

* **MAE and MSE**
* [How MAE is more Robust to ouliers](https://hackernoon.com/my-notes-on-mae-vs-mse-error-metrics) - A Detailed explanaltion of MAE and MSE.

---

## Day 06 — Logistic Regression

### Questions

**1.** Logistic regression is used for:
- a) Regression tasks only
- b) Classification tasks
- c) Clustering tasks
- d) Dimensionality reduction

**2.** The output of logistic regression is:
- a) A continuous value between -∞ and +∞
- b) A probability between 0 and 1
- c) An integer class label
- d) A distance metric

**3.** The sigmoid function maps any real number to:
- a) (-1, 1)
- b) (0, 1)
- c) (-∞, +∞)
- d) (0, +∞)

**4.** The loss function used in logistic regression is:
- a) Mean Squared Error
- b) Binary Cross-Entropy (Log Loss)
- c) Hinge Loss
- d) Huber Loss

**5.** In logistic regression, the decision boundary is:
- a) Always curved
- b) Always a straight line or hyperplane
- c) Determined by the kernel
- d) Non-existent

### Answers

<details>
<summary>Click to reveal answers</summary>

**1. b) Classification tasks**

Despite its name, logistic regression is a CLASSIFICATION algorithm. It predicts the probability of belonging to a class. The "regression" part refers to fitting a function.

**2. b) A probability between 0 and 1**

The sigmoid function squashes the linear output between 0 and 1. This represents probability. If P > 0.5 → class 1, else → class 0 (default threshold).

**3. b) (0, 1)**

Sigmoid: σ(z) = 1/(1 + e^(-z)). At z=0 → 0.5. At z→+∞ → 1. At z→-∞ → 0. Always between 0 and 1, perfect for probability.

**4. b) Binary Cross-Entropy (Log Loss)**

Log Loss = -[y·log(p) + (1-y)·log(1-p)]. It heavily penalizes confident wrong predictions. If the model says 99% spam but it's not → huge penalty.

**5. b) Always a straight line or hyperplane**

Logistic regression creates a linear decision boundary. For non-linear boundaries, you need polynomial features or a different algorithm entirely.

</details>

### Resources


  * **Logistic Regression Overview (MCQ 1 & 2)**

      * [Google ML Crash Course: Logistic Regression](https://developers.google.com/machine-learning/crash-course/logistic-regression/calculating-a-probability) – Interactive module explaining why logistic regression is for classification and how it calculates probability.
      * [Scikit-Learn: Logistic Regression Guide](https://scikit-learn.org/stable/modules/generated/sklearn.linear_model.LogisticRegression.html) – The industry-standard technical documentation for implementation and logic.

  * **The Sigmoid Function (MCQ 3)**

      * [Desmos Interactive Graph: Sigmoid](https://www.desmos.com/calculator/coknirwubg) – A live tool where you can adjust variables to see how the S-curve squashes values into the (0, 1) range.
      * [Wolfram MathWorld: Sigmoid Function](https://mathworld.wolfram.com/SigmoidFunction.html) – Concise mathematical definition and properties of the sigmoid.

  * **Binary Cross-Entropy / Log Loss (MCQ 4)**

      * [ML-Cheatsheet: Logistic Regression Loss](https://www.datacamp.com/tutorial/loss-function-in-machine-learning) – A clean, visual breakdown of the math behind Log Loss and how it penalizes errors.
      * [Neptune.ai: Binary Cross Entropy Explained](https://towardsdatascience.com/cross-entropy-negative-log-likelihood-and-all-that-jazz-47a95bd2e81/) – Deep dive into why we use Log Loss instead of MSE for classification.

  * **Decision Boundaries (MCQ 5)**

      * [TensorFlow Playground](https://playground.tensorflow.org/) – Set "Problem Type" to Classification and "Activation" to Sigmoid to interactively see the linear decision boundary in action.
      * [Visualizing Decision Boundaries](https://scikit-learn.org/stable/auto_examples/classification/plot_classifier_comparison.html) – Comparison plots showing the linear nature of Logistic Regression versus non-linear classifiers.

| Concept | Key Property | Mathematical Intuition |
| :--- | :--- | :--- |
| **Output** | Probability | Value between 0 and 1 |
| **Activation** | Sigmoid | $\sigma(z) = \frac{1}{1 + e^{-z}}$ |
| **Loss** | Log Loss | Penalizes confident wrong answers |
| **Boundary** | Linear | A straight line or flat plane |

---

## Day 07 — Confusion Matrix & Classification Metrics

### Questions

**1.** In a confusion matrix, a False Positive means:
- a) Model predicted positive, actual was positive
- b) Model predicted positive, actual was negative
- c) Model predicted negative, actual was positive
- d) Model predicted negative, actual was negative

**2.** Precision is defined as:
- a) TP / (TP + FN)
- b) TP / (TP + FP)
- c) (TP + TN) / Total
- d) TN / (TN + FP)

**3.** Recall (Sensitivity) is defined as:
- a) TP / (TP + FP)
- b) TP / (TP + FN)
- c) TN / (TN + FP)
- d) (TP + TN) / Total

**4.** In cancer detection, which metric is MORE important?
- a) Precision — avoid false alarms
- b) Recall — don't miss actual cancer cases
- c) Accuracy — overall correctness
- d) Specificity — true negative rate

**5.** A model classifies ALL emails as "not spam." If 95% are actually not spam, what is accuracy?
- a) 50%
- b) 95%
- c) 100%
- d) 0%

### Answers

<details>
<summary>Click to reveal answers</summary>

**1. b) Model predicted positive, actual was negative**

False Positive = "false alarm." The model said YES but the truth was NO. Example: healthy patient diagnosed with a disease. The second word (Positive/Negative) is what the MODEL predicted.

**2. b) TP / (TP + FP)**

Precision = "Of everything the model predicted as positive, how many were actually positive?" High precision = few false alarms.

**3. b) TP / (TP + FN)**

Recall = "Of all actual positives, how many did the model catch?" High recall = few missed cases.

**4. b) Recall — don't miss actual cancer cases**

Missing cancer (False Negative) is far more dangerous than a false alarm (False Positive). A false alarm leads to more tests; missed cancer can be fatal. Prioritize RECALL.

**5. b) 95%**

If 95% aren't spam and the model always says "not spam," it's correct 95% of the time. This is why accuracy is misleading for imbalanced datasets — a dumb model gets 95%!

</details>

### Resources

### 🔹 Core Concepts (MCQ 1–3)
* [Google ML Crash Course – Classification Metrics](https://developers.google.com/machine-learning/crash-course/classification/accuracy-precision-recall)
  Clear explanations of confusion matrix, precision, and recall with simple visuals.
* [StatQuest with Josh Starmer – Confusion Matrix](https://www.youtube.com/watch?v=Kdsp6soqA7o)
  Short and visual explanation of TP, FP, TN, FN.

### 🔹 Precision vs Recall (MCQ 2–4)
* [StatQuest with Josh Starmer – Precision & Recall](https://www.youtube.com/watch?v=vP06aMoz4v8)
  Intuition behind precision vs recall and when each matters.
* [Machine Learning Mastery – Precision vs Recall Guide](https://machinelearningmastery.com/precision-recall-and-f-measure-for-imbalanced-classification/)
  Good practical examples, especially for imbalanced data.

### 🔹 Accuracy Pitfall (MCQ 5)
* [Kaggle – Classification Metrics](https://www.kaggle.com/code/alexisbcook/classification-metrics)
  Shows why high accuracy can be misleading.

### 🔹 Optional Visualization
* [TensorFlow Playground](https://playground.tensorflow.org/)
  Visualize classification behavior and model errors interactively.

---

## Day 08 — F1 Score, ROC & AUC

### Questions

**1.** The F1 score is the:
- a) Arithmetic mean of precision and recall
- b) Harmonic mean of precision and recall
- c) Geometric mean of precision and recall
- d) Weighted sum of accuracy and recall

**2.** An AUC of 0.5 means:
- a) The model is perfect
- b) The model performs no better than random guessing
- c) The model has 50% accuracy
- d) The model always predicts positive

**3.** The ROC curve plots:
- a) Precision vs Recall
- b) True Positive Rate vs False Positive Rate
- c) Accuracy vs Threshold
- d) Bias vs Variance

**4.** When is F1 score preferred over accuracy?
- a) When classes are perfectly balanced
- b) When classes are imbalanced
- c) When there are more than 2 classes
- d) When the model is regression

**5.** If AUC = 1.0, the model:
- a) Is overfitting
- b) Perfectly separates the two classes
- c) Has memorized training data
- d) Has zero precision

### Answers

<details>
<summary>Click to reveal answers</summary>

**1. b) Harmonic mean of precision and recall**

F1 = 2×(Precision×Recall)/(Precision+Recall). The harmonic mean punishes extreme imbalance. If precision=1.0 and recall=0.0, F1=0 (not 0.5 like the arithmetic mean would give).

**2. b) The model performs no better than random guessing**

AUC=0.5 means the model's ranking is no better than flipping a coin. AUC=1.0 is perfect. AUC<0.5 is worse than random (predictions are inverted).

**3. b) True Positive Rate vs False Positive Rate**

ROC plots TPR (recall) on the y-axis vs FPR on the x-axis at various classification thresholds. Shows the tradeoff between catching positives and false alarms.

**4. b) When classes are imbalanced**

With 99% negative class, accuracy can be 99% by predicting all negative. F1 considers both precision and recall, exposing poor minority class performance.

**5. b) Perfectly separates the two classes**

AUC=1.0 means the model can perfectly rank all positives above all negatives. On test data this is rare — might indicate data leakage, always investigate.

</details>

### Resources

**F1 Score Harmonic Mean of Precision & Recall (MCQ 1 & 4)**

- [Why F1 uses Harmonic Mean, not Arithmetic Mean — Medium](https://medium.com/@Suraj_Yadav/why-is-the-f1-score-the-harmonic-mean-of-precision-and-recall-rather-than-the-arithmetic-mean-2573ab99e49c) 

- [F1 Score in Machine Learning — Encord](https://encord.com/blog/f1-score-in-machine-learning/) 

- [Scikit-Learn: F1 Score Documentation](https://scikit-learn.org/stable/modules/generated/sklearn.metrics.f1_score.html) 

**ROC Curve — TPR vs FPR (MCQ 3)**

- [StatQuest: ROC and AUC, Clearly Explained!  YouTube](https://www.youtube.com/watch?v=4jRBRDbJemM) 

- [MLU-Explain: ROC and AUC — Interactive](https://mlu-explain.github.io/roc-auc/)

- [Google ML Crash Course: ROC and AUC](https://developers.google.com/machine-learning/crash-course/classification/roc-and-auc) 

**AUC Interpretation — 0.5, 1.0, and What They Mean (MCQ 2 & 5)**

- [DataSchool: ROC Curves and AUC Explained (Video + Transcript)](https://www.dataschool.io/roc-curves-and-auc-explained/) 

- [Evidently AI: How to Explain ROC AUC](https://www.evidentlyai.com/classification-metrics/explain-roc-curve)

- [DataCamp: AUC and ROC Curve Tutorial](https://www.datacamp.com/tutorial/auc) 

## Day 09 — Multi-class Metrics

### Questions

**1.** "Macro-averaged" F1 score for a 3-class problem:
- a) Computes F1 per class and averages equally
- b) Computes F1 weighted by class frequency
- c) Computes a single global F1
- d) Only considers the majority class

**2.** Cohen's Kappa measures:
- a) Agreement between predictions and actuals, adjusted for chance
- b) Correlation between features
- c) The AUC score
- d) Feature importance

**3.** Log loss penalizes:
- a) Only wrong predictions
- b) Confident wrong predictions more heavily
- c) All predictions equally
- d) Only correct predictions

**4.** Specificity (True Negative Rate) is:
- a) TP / (TP + FN)
- b) TN / (TN + FP)
- c) TP / (TP + FP)
- d) FP / (FP + TN)

**5.** "Micro-averaged" precision:
- a) Averages precision per class equally
- b) Aggregates all TP and FP globally, then computes precision
- c) Only looks at smallest class
- d) Always equals macro-averaged precision

### Answers

<details>
<summary>Click to reveal answers</summary>

**1. a) Computes F1 per class and averages equally**

Macro = all classes matter equally. Compute F1 for each class separately, then take a simple average. Useful when minority class performance matters.

**2. a) Agreement between predictions and actuals, adjusted for chance**

Kappa=0 means no better than chance. Kappa=1 means perfect. Useful when classes are imbalanced — a model predicting the majority class gets low Kappa despite high accuracy.

**3. b) Confident wrong predictions more heavily**

Log loss = -log(predicted probability of true class). If model says 99% confident it's class A but it's actually class B → massive penalty. Encourages well-calibrated probabilities.

**4. b) TN / (TN + FP)**

Specificity = "Of all actual negatives, how many did the model correctly identify as negative?" High specificity = few false alarms.

**5. b) Aggregates all TP and FP globally, then computes precision**

Micro pools all predictions across classes: total TP / (total TP + total FP). This favors larger classes. Macro treats each class equally regardless of size.

</details>

### Resources

**Macro vs Micro Averaging — F1 in Multi-class (MCQ 1 & 5)**

- [Micro, Macro & Weighted Averages of F1 Score — Towards Data Science](https://towardsdatascience.com/micro-macro-weighted-averages-of-f1-score-clearly-explained-b603420b292f/)

- [Scikit-Learn: F1 Score Documentation](https://scikit-learn.org/stable/modules/generated/sklearn.metrics.f1_score.html)

- [Understanding Macro F1 Score  Medium](https://medium.com/@sushma.mullamuri420/understanding-the-macro-f1-score-in-multi-class-classification-21ca00c200da)

**Cohen's Kappa — Agreement Beyond Chance (MCQ 2)**

- [Cohen's Kappa Explained  Built In](https://builtin.com/data-science/cohens-kappa)

- [Cohen's Kappa and Its Use in ML  Explained](https://mlexplained.blog/2024/01/08/cohens-kappa-and-its-use-in-ml/)

- [Cohen's Kappa: What It Is, When to Use It  The New Stack](https://thenewstack.io/cohens-kappa-what-it-is-when-to-use-it-and-how-to-avoid-its-pitfalls/)

**Log Loss — Penalizing Confident Wrong Predictions (MCQ 3)**

- [Understanding Binary Cross-Entropy / Log Loss  Towards Data Science](https://towardsdatascience.com/understanding-binary-cross-entropy-log-loss-a-visual-explanation-a3ac6025181a/)

- [A Gentle Introduction to Cross-Entropy  Machine Learning Mastery](https://machinelearningmastery.com/cross-entropy-for-machine-learning/)

**Specificity / True Negative Rate (MCQ 4)**

- [Sensitivity and Specificity - Wikipedia](https://en.wikipedia.org/wiki/Sensitivity_and_specificity)

- [Specificity - GeeksforGeeks](https://www.geeksforgeeks.org/machine-learning/what-is-specificity/)


## Day 10 — Decision Trees

### Questions

**1.** Decision trees split data based on:
- a) Random selection
- b) Feature that maximizes information gain or minimizes impurity
- c) Alphabetical order of features
- d) Feature with the most missing values

**2.** Gini impurity measures:
- a) The depth of the tree
- b) The probability of misclassifying a randomly chosen element
- c) The number of features
- d) The training time

**3.** A decision tree with no depth limit will likely:
- a) Underfit the data
- b) Overfit the training data
- c) Generalize perfectly
- d) Have high bias

**4.** Pruning a decision tree helps to:
- a) Increase training accuracy
- b) Reduce overfitting
- c) Add more features
- d) Speed up data collection

**5.** Which statement about decision trees is TRUE?
- a) They cannot handle categorical features
- b) They require feature scaling
- c) They are prone to overfitting if not controlled
- d) They can only solve binary classification

### Answers

<details>
<summary>Click to reveal answers</summary>

**1. b) Feature that maximizes information gain or minimizes impurity**

At each node, the tree tries every feature and split point, choosing the one that best separates classes. Information Gain and Gini Impurity are the two most common criteria.

**2. b) The probability of misclassifying a randomly chosen element**

Gini = 1 - Σ(pᵢ²). If a node is pure (all one class), Gini=0. If 50/50 split, Gini=0.5. Lower Gini = purer node = better split.

**3. b) Overfit the training data**

An unlimited tree creates a leaf for every training example, memorizing the data perfectly but capturing noise, not patterns. Always limit depth or prune.

**4. b) Reduce overfitting**

Pruning removes branches that add little predictive value. Pre-pruning: set max depth. Post-pruning: grow full tree, then cut back. Both reduce complexity.

**5. c) They are prone to overfitting if not controlled**

Trees handle categoricals natively (a is false), don't need scaling (b is false), and can do multi-class + regression (d is false). But they DO overfit easily — their main weakness.

</details>

### Resources

> 📚 *Resources for this topic will be added here*

---

## Day 11 — Random Forests

### Questions

**1.** Random Forest is an example of:
- a) Boosting
- b) Bagging (Bootstrap Aggregating)
- c) Clustering
- d) Dimensionality reduction

**2.** What makes Random Forest "random"?
- a) It randomly selects the target variable
- b) It uses random subsets of data AND features for each tree
- c) It randomly assigns class labels
- d) It trains for a random number of epochs

**3.** Compared to a single decision tree, Random Forest typically has:
- a) Higher variance
- b) Lower variance and better generalization
- c) Faster training time
- d) Fewer parameters

**4.** Out-of-Bag (OOB) error is:
- a) Error on the training set
- b) Error estimated using samples NOT used in each tree's bootstrap sample
- c) Error after pruning
- d) Always higher than test error

**5.** Increasing number of trees in Random Forest:
- a) Always increases overfitting
- b) Generally improves then plateaus
- c) Decreases training accuracy
- d) Makes the model simpler

### Answers

<details>
<summary>Click to reveal answers</summary>

**1. b) Bagging (Bootstrap Aggregating)**

Bagging trains multiple models on random bootstrap samples and averages/votes. Random Forest adds extra randomness by also selecting random feature subsets at each split.

**2. b) It uses random subsets of data AND features for each tree**

Two sources of randomness: (1) Each tree gets a random bootstrap sample (with replacement). (2) At each split, only a random subset of features is considered. This decorrelates the trees.

**3. b) Lower variance and better generalization**

Averaging many diverse trees reduces variance (overfitting) while keeping bias low. A single tree is unstable — RF smooths this out.

**4. b) Error estimated using samples NOT used in each tree's bootstrap sample**

Each bootstrap uses ~63% of data. The remaining ~37% (OOB) acts as a built-in validation set. A free, unbiased performance estimate!

**5. b) Generally improves then plateaus**

More trees means more stable predictions. After 100-500 trees, diminishing returns. More trees never hurts accuracy, just wastes computation.

</details>

### Resources

> 📚 *Resources for this topic will be added here*

---

## Day 12 — Bagging vs Boosting

### Questions

**1.** Key difference between bagging and boosting:
- a) Bagging uses trees, boosting uses linear models
- b) Bagging trains in parallel, boosting trains sequentially
- c) Bagging is classification only, boosting is regression only
- d) No difference

**2.** In AdaBoost, misclassified samples:
- a) Are removed from the dataset
- b) Get higher weights in the next round
- c) Are duplicated randomly
- d) Are ignored

**3.** Gradient Boosting works by:
- a) Building each new tree to predict residuals of the previous model
- b) Randomly selecting features
- c) Pruning all trees simultaneously
- d) Averaging all trees equally

**4.** Which is more prone to overfitting if not tuned?
- a) Bagging
- b) Boosting
- c) Both equally
- d) Neither

**5.** XGBoost improves on basic gradient boosting by:
- a) Removing all regularization
- b) Adding regularization and efficient tree-building
- c) Using only linear models
- d) No sequential dependency

### Answers

<details>
<summary>Click to reveal answers</summary>

**1. b) Bagging trains in parallel, boosting trains sequentially**

Bagging: independent models averaged together (reduces variance). Boosting: each new model focuses on the previous model's mistakes (reduces bias).

**2. b) Get higher weights in the next round**

AdaBoost upweights misclassified samples so the next weak learner focuses more on the hard cases. Over rounds, the ensemble zeroes in on difficult examples.

**3. a) Building each new tree to predict residuals of the previous model**

Each new tree fits the RESIDUAL errors (actual - current prediction). Over many rounds, the sum of all trees gradually gets closer to the true values.

**4. b) Boosting**

Boosting focuses on hard examples, which can include noise. Key hyperparameters to tune: learning rate, number of trees, max depth.

**5. b) Adding regularization and efficient tree-building**

XGBoost adds L1/L2 regularization on leaf weights, uses approximate split-finding for speed, handles missing values natively, and supports parallel computation of feature splits.

</details>

### Resources

> 📚 *Resources for this topic will be added here*

---

## Day 13 — Support Vector Machines

### Questions

**1.** SVM finds the hyperplane that:
- a) Passes through the most data points
- b) Maximizes the margin between classes
- c) Minimizes the number of features
- d) Maximizes training accuracy regardless of margin

**2.** Support vectors are:
- a) All data points in the dataset
- b) Data points closest to the decision boundary
- c) Centroids of each class
- d) Outliers that are removed

**3.** The kernel trick allows:
- a) Faster training on large datasets
- b) Mapping data to higher dimensions without explicit computation
- c) Reducing the number of features
- d) Eliminating the need for labels

**4.** Which kernel is best for linearly separable data?
- a) RBF
- b) Polynomial
- c) Linear
- d) Sigmoid

**5.** The C parameter in SVM controls:
- a) Number of support vectors
- b) Tradeoff between smooth boundary and correct classification of training points
- c) The kernel type
- d) The learning rate

### Answers

<details>
<summary>Click to reveal answers</summary>

**1. b) Maximizes the margin between classes**

SVM finds the hyperplane with the LARGEST gap between classes. Wider margin = more confidence. That's why SVM is called a "maximum margin classifier."

**2. b) Data points closest to the decision boundary**

Support vectors sit on the edge of the margin. They "support" the hyperplane — remove them and the boundary changes. All other points don't affect the decision.

**3. b) Mapping data to higher dimensions without explicit computation**

The kernel trick computes dot products in high-dimensional space WITHOUT actually transforming the data. The RBF kernel effectively maps to infinite dimensions!

**4. c) Linear**

If data is already linearly separable, a linear kernel is simplest and fastest. Using RBF on linear data wastes computation and risks overfitting.

**5. b) Tradeoff between smooth boundary and correct classification of training points**

High C = narrow margin, fewer training errors (overfitting risk). Low C = wider margin, more errors allowed (smoother, more generalizable).

</details>

### Resources

> 📚 *Resources for this topic will be added here*

---

## Day 14 — K-Nearest Neighbors

### Questions

**1.** KNN is a _____ learning algorithm.
- a) Eager
- b) Lazy (instance-based)
- c) Generative
- d) Reinforcement

**2.** As K increases in KNN:
- a) Decision boundary becomes more complex
- b) Decision boundary becomes smoother
- c) Training time increases
- d) Algorithm becomes faster at prediction

**3.** KNN is sensitive to:
- a) The loss function
- b) Feature scaling
- c) The learning rate
- d) Regularization parameter

**4.** For KNN with K=1:
- a) The model has very high bias
- b) The training error is always 0
- c) The model generalizes well
- d) The model is very smooth

**5.** Most commonly used distance metric in KNN:
- a) Manhattan distance
- b) Cosine similarity
- c) Euclidean distance
- d) Hamming distance

### Answers

<details>
<summary>Click to reveal answers</summary>

**1. b) Lazy (instance-based)**

KNN stores all training data and does computation at prediction time. Training is instant but prediction is slow — it has to search through all points.

**2. b) Decision boundary becomes smoother**

Small K = noisy, wiggly boundary following every point. Large K = smoother. Very large K → everything classified as majority class (underfitting).

**3. b) Feature scaling**

If one feature ranges 0-1000 and another 0-1, the first dominates distance. Always normalize/standardize before KNN.

**4. b) The training error is always 0**

With K=1, each point's nearest neighbor is itself. So training error = 0 always. But this means extreme overfitting — high variance, low bias.

**5. c) Euclidean distance**

√(Σ(xᵢ - yᵢ)²) — straight-line distance between points. Manhattan uses absolute differences. Cosine measures angle. Choice depends on the problem.

</details>

### Resources

> 📚 *Resources for this topic will be added here*

---

## Day 15 — Naive Bayes

### Questions

**1.** The "naive" assumption in Naive Bayes is:
- a) Data is always normally distributed
- b) All features are independent given the class
- c) Prior probability is always equal
- d) Model can only handle two classes

**2.** Naive Bayes works well for:
- a) Image segmentation
- b) Text classification like spam detection
- c) Time series forecasting
- d) Reinforcement learning

**3.** In Bayes' theorem, P(A|B) = P(B|A) × P(A) / P(B). What is P(A)?
- a) The likelihood
- b) The posterior
- c) The prior probability
- d) The evidence

**4.** Gaussian Naive Bayes assumes features follow:
- a) Binary distribution
- b) Normal (Gaussian) distribution
- c) Uniform distribution
- d) Poisson distribution

**5.** If a test word never appeared in training data, what happens?
- a) Model crashes
- b) Probability becomes 0, killing the entire prediction
- c) Model ignores it automatically
- d) Uses backpropagation

### Answers

<details>
<summary>Click to reveal answers</summary>

**1. b) All features are independent given the class**

Features are often correlated in reality (e.g., "free" and "money" in spam). Despite this unrealistic assumption, Naive Bayes works surprisingly well in practice.

**2. b) Text classification like spam detection**

Fast, works well with high-dimensional sparse data like word counts, and needs relatively little training data. Gmail's original spam filter used Naive Bayes.

**3. c) The prior probability**

P(A) = prior — your belief before seeing evidence. P(B|A) = likelihood. P(A|B) = posterior — updated belief. P(B) = evidence — normalizing constant.

**4. b) Normal (Gaussian) distribution**

Gaussian NB estimates mean and variance per feature per class. For binary features → Bernoulli NB. For word counts → Multinomial NB.

**5. b) Probability becomes 0, killing the entire prediction**

Since NB multiplies probabilities, one zero kills everything. Fix: Laplace smoothing — add a small count (usually 1) to all word counts so nothing is ever exactly 0.

</details>

### Resources

-  [Naive Bayes Classifier Explained: Assumptions, Types, and Uses](https://medium.com/@kavyasrirelangi100/naive-bayes-classifier-explained-assumptions-types-and-uses-bef767a758a3)

- [Naive Bayes Classifier Explained With Practical Problems](https://www.analyticsvidhya.com/blog/2017/09/naive-bayes-explained/)
  To understand why assuming features are independent is considered "naive," and why it works so well for high-dimensional text data like spam detection. 

- [Bayes' Theorem Components: The Prior (Q3)](https://www.mathsisfun.com/data/bayes-theorem.html) this page offers one of the clearest mathematical breakdowns of the Prior, Posterior, and Evidence using real-world examples like fire and smoke.

- [Gaussian Distribution (Q4)](https://scikit-learn.org/stable/modules/naive_bayes.html) When working with continuous data (like real-valued measurements) instead of word counts, the model assumes a "Normal" or Gaussian distribution.

- [The "Zero Frequency" Problem (Q5)](https://towardsdatascience.com/laplace-smoothing-in-naive-bayes-algorithm-9c237a8bdece/) This article walks through the math of a zero-probability crash and explicitly shows how adjusting the $\alpha$ (alpha) parameter "smooths" the data so the model doesn't fail on unseen words.

---

## Day 16 — K-Means Clustering

### Questions

**1.** K-Means requires you to specify:
- a) Number of features
- b) Number of clusters (K) in advance
- c) Class labels
- d) Learning rate

**2.** K-Means converges when:
- a) All points are in one cluster
- b) Cluster assignments stop changing
- c) K reaches the number of data points
- d) Maximum iterations only

**3.** The elbow method helps determine:
- a) Best features to use
- b) Optimal number of clusters
- c) Best distance metric
- d) Learning rate

**4.** K-Means is sensitive to:
- a) Feature scaling and initial centroid placement
- b) Order of class labels
- c) Loss function
- d) Batch size

**5.** K-Means works best with:
- a) Irregular, elongated cluster shapes
- b) Spherical (round) clusters of similar size
- c) Crescent-shaped clusters
- d) Clusters with vastly different densities

### Answers

<details>
<summary>Click to reveal answers</summary>

**1. b) Number of clusters (K) in advance**

Major limitation — wrong K gives bad results. Use the elbow method, silhouette score, or domain knowledge to pick K.

**2. b) Cluster assignments stop changing**

K-Means iterates: assign points to nearest centroid → recalculate centroids. Converges when assignments stabilize. May reach a local minimum.

**3. b) Optimal number of clusters**

Plot K vs inertia (sum of distances to centroids). The curve drops steeply then flattens — the "elbow" point is a good K.

**4. a) Feature scaling and initial centroid placement**

Features with larger ranges dominate distance. Always scale first. Bad initial centroids lead to bad local minima. Use K-Means++ for better initialization.

**5. b) Spherical (round) clusters of similar size**

K-Means assumes spherical clusters. For irregular shapes, use DBSCAN or hierarchical clustering instead.

</details>

### Resources

- [The Complete Workflow: Iteration, Elbow Method, and Silhouette Score](https://realpython.com/k-means-clustering-python/) This is an exceptionally thorough guide. It explains the step-by-step convergence loop (Q2), provides the code to calculate and plot inertia to find the "elbow" (Q3), and explains how to use the Silhouette coefficient to double-check your $K$ value (Q1).
- [Centroid Initialization in K-Means Clustering](https://www.kdnuggets.com/2020/06/centroid-initialization-k-means-clustering.html) This article focuses entirely on the vulnerability of the algorithm to random initialization. It breaks down the math behind the K-Means++ algorithm and explains how it forces initial centroids to be far apart to prevent poor convergence.
- [The impact of neglecting feature scaling in k-means clustering](https://pmc.ncbi.nlm.nih.gov/articles/PMC11623793/) It explicitly details how distance-based algorithms like K-Means calculate Euclidean distance, and why leaving a feature unscaled will completely erase the impact of another feature.
- [Demonstration of K-Means Assumptions](https://www.geeksforgeeks.org/machine-learning/demonstration-of-k-means-assumptions/)
- [Scikit-Learn Documentation: Demonstration of K-Means Assumptions](https://scikit-learn.org/stable/auto_examples/cluster/plot_kmeans_assumptions.html) This specific page from the sklearn docs is famous for visually proving Q5. It applies K-Means to crescent-shaped data, elongated blobs, and varying densities, showing exactly how K-Means misclassifies them. It then recommends DBSCAN to solve those specific topological issues.
---

## Day 17 — Clustering Methods

### Questions

**1.** DBSCAN's main advantage over K-Means is:
- a) It's always faster
- b) It can find clusters of arbitrary shape and doesn't need K specified
- c) It works only with text data
- d) It requires labeled data

**2.** In DBSCAN, a "core point" is:
- a) The centroid of a cluster
- b) A point with at least MinPts neighbors within epsilon radius
- c) A point farthest from all clusters
- d) The first point in the dataset

**3.** Hierarchical clustering produces:
- a) A fixed number of clusters
- b) A dendrogram (tree of merges/splits)
- c) Only two clusters
- d) Random cluster assignments

**4.** Silhouette score ranges from:
- a) 0 to 1
- b) -1 to 1
- c) 0 to infinity
- d) -infinity to infinity

**5.** Which clustering method can identify outliers?
- a) K-Means
- b) DBSCAN
- c) Agglomerative clustering
- d) Mini-Batch K-Means

### Answers

<details>
<summary>Click to reveal answers</summary>

**1. b) It can find clusters of arbitrary shape and doesn't need K specified**

DBSCAN finds density-connected regions. Crescents, rings, blobs — no problem. It discovers K automatically.

**2. b) A point with at least MinPts neighbors within epsilon radius**

Core points form cluster interiors. Border points are reachable but don't have enough neighbors. Noise points belong to no cluster.

**3. b) A dendrogram (tree of merges/splits)**

The dendrogram shows how clusters merge at different distances. Cut at your chosen level to get the desired number of clusters.

**4. b) -1 to 1**

Near +1 = well-clustered. Near 0 = on boundary between clusters. Near -1 = probably in the wrong cluster. Average across all points for overall quality.

**5. b) DBSCAN**

DBSCAN labels points that don't belong to any dense region as noise/outliers. K-Means forces every point into a cluster.

</details>

### Resources
**DBSCAN Clustering Algorithm**
- [Master the Popular DBSCAN Clustering Algorithm](https://www.analyticsvidhya.com/blog/2020/09/how-dbscan-clustering-works/) This guide explicitly defines the parameters (epsilon and MinPts). It provides clear diagrams showing the difference between a "Core point" (cluster interior) and a "Noise point" (outlier), proving exactly why DBSCAN succeeds on weirdly shaped data where K-Means fails.

**A dendrogram (tree of merges/splits)**
- [Hierarchical Clustering & Dendrograms](https://www.youtube.com/watch?v=7xHsRkOdVwo) If the concept of "agglomerative merges" feels abstract, this is the best visual breakdown available. It animates exactly how individual data points are paired up into leaves, how those leaves merge into branches, and how the final dendrogram tree is constructed from the bottom up.

**Silhouette Score Range and implementation**
- [What is Silhouette Score](https://www.geeksforgeeks.org/machine-learning/what-is-silhouette-score/)
  
**Difference between K-Means and DBScan Clustering**
- [K-Means Vs DBScan Clustering](https://www.geeksforgeeks.org/dbms/difference-between-k-means-and-dbscan-clustering/) 

---

## Day 18 — Feature Engineering

### Questions

**1.** One-hot encoding is used for:
- a) Scaling continuous features
- b) Converting categorical variables into binary columns
- c) Removing outliers
- d) Filling missing values

**2.** Feature scaling is especially important for:
- a) Decision trees
- b) Random forests
- c) KNN and SVM
- d) Naive Bayes

**3.** What is the problem with label encoding ordinal categories as 1,2,3 for non-ordinal data?
- a) It's too slow
- b) It introduces a false ordering relationship
- c) It removes information
- d) It increases dimensionality

**4.** Log transformation of a feature is useful when:
- a) The feature is normally distributed
- b) The feature is heavily right-skewed
- c) The feature has no outliers
- d) The feature is categorical

**5.** Feature interaction means:
- a) Deleting correlated features
- b) Creating new features by combining existing ones
- c) Standardizing features
- d) One-hot encoding

### Answers

<details>
<summary>Click to reveal answers</summary>

**1. b) Converting categorical variables into binary columns**

"Color" with Red/Blue/Green → three columns: is_Red, is_Blue, is_Green (0 or 1 each). Prevents models from assuming an ordering.

**2. c) KNN and SVM**

These use distance calculations. If one feature ranges 0-1000 and another 0-1, the first dominates. Trees don't care about scale.

**3. b) It introduces a false ordering relationship**

If Red=1, Blue=2, Green=3, the model thinks Green > Blue > Red. For non-ordinal categories, use one-hot encoding instead.

**4. b) The feature is heavily right-skewed**

Log transform pulls in long right tails, making the distribution more symmetric. Useful for income, prices, populations — anything with extreme high values.

**5. b) Creating new features by combining existing ones**

Example: price × quantity = total_spend. Area = length × width. Interactions capture relationships that individual features miss.

</details>

### Resources
**One-Hot Encoding vs. Label Encoding**
- [Why One-Hot Encode Data in Machine Learning?](https://machinelearningmastery.com/why-one-hot-encode-data-in-machine-learning/) This article perfectly explains the "false ordering" problem of integer/label encoding mentioned in Q3. It breaks down why algorithms assume Green > Blue > Red and demonstrates how turning categories into 0 or 1 binary variables (Q1) fixes the mathematical constraint.

**Feature Scaling: Distance Models vs. Trees**
- [Why is Feature Scaling Important in Machine Learning](https://towardsdatascience.com/why-is-feature-scaling-important-in-machine-learning-discussing-6-feature-scaling-techniques-2773bda5be30/) This guide provides explicit algorithm breakdowns. It mathematically demonstrates why calculating Euclidean distance in KNN or SVM requires standardized scales, and dedicates a specific section proving why Random Forests and Decision Trees do not care about feature scales.

**Log Transformation**
- [Feature Transformations in Data Science](https://www.analyticsvidhya.com/blog/2021/05/feature-transformations-in-data-science-a-detailed-walkthrough/) This walkthrough features a specific, detailed section on "Log Transformation." It's explaining that it is primarily applied to right-skewed data with extreme high values to convert additive scales into multiplicative ones, thereby dragging outliers closer to the mean.

**Feature interactions**
- [Feature Interaction](https://towardsdatascience.com/feature-interactions-524815abec81/) This article explores exactly how the effect of one feature often depends on the value of another. It uses clear examples (like calculating BMI from weight and height) to show how manually engineering pairwise interactions helps simpler models capture non-linear relationships.
---

## Day 19 — Feature Selection

### Questions

**1.** Why is feature selection important?
- a) It always improves accuracy
- b) It reduces overfitting, speeds up training, and improves interpretability
- c) It increases model complexity
- d) It eliminates the need for cross-validation

**2.** Removing features with very low variance is a:
- a) Wrapper method
- b) Filter method
- c) Embedded method
- d) Boosting method

**3.** Recursive Feature Elimination (RFE) is a:
- a) Filter method
- b) Wrapper method
- c) Embedded method
- d) Clustering method

**4.** L1 regularization (Lasso) performs feature selection by:
- a) Removing correlated features
- b) Driving some feature coefficients to exactly zero
- c) Sorting features by importance
- d) Increasing all coefficients

**5.** Mutual information measures:
- a) Linear correlation between two variables
- b) How much knowing one variable reduces uncertainty about another
- c) Mean of two features
- d) Variance ratio

### Answers

<details>
<summary>Click to reveal answers</summary>

**1. b) It reduces overfitting, speeds up training, and improves interpretability**

Fewer irrelevant features = less noise for the model, faster training, and easier to explain. Doesn't ALWAYS improve accuracy though.

**2. b) Filter method**

Filter methods rank features by statistical properties (variance, correlation, chi-squared) BEFORE training any model. Simple and fast.

**3. b) Wrapper method**

RFE trains the model, removes the weakest feature, and repeats. It "wraps" around a specific model. More accurate than filters but slower.

**4. b) Driving some feature coefficients to exactly zero**

L1 penalty = λΣ|wᵢ|. It pushes small coefficients to zero, effectively removing those features. Built-in feature selection!

**5. b) How much knowing one variable reduces uncertainty about another**

Mutual information captures ANY relationship (linear or non-linear). MI=0 means independent. Higher MI = stronger dependency.

</details>

### Resources

**Filter, Wrapper, and Embedded Methods**
- [Feature Selection For Machine Learning with implementation](https://machinelearningmastery.com/feature-selection-machine-learning-python/)

**Recursive Feature Elimination Deep Dive**
- [Scikit-Learn Official User Guide: Recursive Feature Elimination](https://scikit-learn.org/stable/modules/generated/sklearn.feature_selection.RFE.html) The official documentation outlines the exact mechanic: the model is trained, coefficients (or feature importances) are calculated, the weakest feature is pruned, and the process repeats until the desired number of features is reached.

**L1 Regularization (Lasso) as an Embedded Method**
- [Embedded Methods: Regularization (Lasso L1)](https://apxml.com/courses/intro-feature-engineering/chapter-6-feature-selection/embedded-lasso-l1) This article provides the mathematical intuition behind why L1 (Lasso) shrinks coefficients to zero while L2 (Ridge) only pushes them close to zero.

**Mutual Information and Uncertainty**
- [Mutual Information](https://www.kaggle.com/code/ryanholbrook/mutual-information) "Mutual information describes relationships in terms of uncertainty." It explains that while standard correlation (like Pearson) only finds linear lines, MI can detect any kind of dependency between two variables.

---

## Day 20 — Handling Missing Data

### Questions

**1.** The simplest way to handle missing values is:
- a) Delete the entire dataset
- b) Impute with mean/median/mode
- c) Always use deep learning
- d) Ignore them

**2.** When is it appropriate to drop rows with missing values?
- a) Always
- b) When the percentage of missing data is very small
- c) When most data is missing
- d) Never

**3.** For a numerical feature with outliers, which imputation is better?
- a) Mean imputation
- b) Median imputation
- c) Mode imputation
- d) Zero imputation

**4.** "MCAR" (Missing Completely At Random) means:
- a) Missingness depends on the missing value itself
- b) Missingness has no relationship with any variable
- c) Missingness depends on observed data
- d) Data was deliberately removed

**5.** Which model can handle missing values natively?
- a) Logistic Regression
- b) KNN
- c) XGBoost
- d) SVM

### Answers

<details>
<summary>Click to reveal answers</summary>

**1. b) Impute with mean/median/mode**

Replace missing numerical values with mean or median. For categorical, use mode. Simple baseline before trying fancier methods.

**2. b) When the percentage of missing data is very small**

If only 1-2% of rows have missing values, dropping is fine. If 30%+ is missing, dropping wastes too much data — impute instead.

**3. b) Median imputation**

Mean is pulled by outliers. Median is robust — it's the middle value. If incomes are [30K, 35K, 40K, 10M], mean is ~2.5M but median is ~37.5K.

**4. b) Missingness has no relationship with any variable**

MCAR: pure random. MAR: depends on observed variables. MNAR: depends on the missing value itself. MCAR is the easiest to handle.

**5. c) XGBoost**

XGBoost learns optimal split directions for missing values during training. No imputation needed. LR, KNN, and SVM all require complete data.

</details>

### Resources
**Handlig Missing Data**
- [Effective Strategies for Handling Missing Values](https://www.analyticsvidhya.com/blog/2021/10/handling-missing-value/) It explains the math behind why deleting rows (listwise deletion) is only safe for very small percentages, how to apply mean/median/mode imputation, and explicitly demonstrates why extreme values (like your $10M income example) break mean imputation but leave the median intact.

**XGBOOST and Missing Values**
- [How XGBoost Handles Missing Values?](https://medium.com/@xwang222/how-xgboost-handles-missing-values-a-proof-of-concept-6aa7afcc8eb9) This article will explain how XGBoost treats missing values and demonstrate the behavior under different scenarios.

---

## Day 21 — Handling Imbalanced Data

### Questions

**1.** With a 99% majority class, a model predicting only the majority class gets:
- a) 1% accuracy
- b) 50% accuracy
- c) 99% accuracy
- d) 0% accuracy

**2.** SMOTE is a technique that:
- a) Removes majority class samples
- b) Creates synthetic minority class samples
- c) Normalizes all features
- d) Increases the learning rate

**3.** Random undersampling:
- a) Creates new synthetic samples
- b) Removes samples from the majority class
- c) Duplicates minority samples
- d) Changes the model architecture

**4.** Which metric should you avoid for imbalanced data?
- a) F1 Score
- b) Accuracy
- c) Precision
- d) AUC-ROC

**5.** Class weights in a model:
- a) Remove minority class samples
- b) Give higher penalty for misclassifying the minority class
- c) Balance feature scales
- d) Increase the dataset size

### Answers

<details>
<summary>Click to reveal answers</summary>

**1. c) 99% accuracy**

A useless model gets 99% by always predicting majority. This is the "accuracy paradox" — why accuracy alone is misleading for imbalanced data.

**2. b) Creates synthetic minority class samples**

SMOTE picks a minority sample, finds its K nearest neighbors, and creates new points along the lines between them. Increases minority representation without simple duplication.

**3. b) Removes samples from the majority class**

Undersampling randomly discards majority examples until balanced. Simple but loses information. Often combined with oversampling.

**4. b) Accuracy**

Accuracy hides poor minority class performance. Use F1, precision, recall, AUC-ROC, or balanced accuracy instead.

**5. b) Give higher penalty for misclassifying the minority class**

class_weight='balanced' makes misclassifying rare cases more costly. The model learns to pay attention to the minority class without changing the data.

</details>

### Resources
**The Accuracy Paradox & Evaluation Metrics**
- [Tour of Evaluation Metrics for Imbalanced Classification](https://machinelearningmastery.com/tour-of-evaluation-metrics-for-imbalanced-classification/) This article explains why accuracy fails and provides a detailed breakdown of when to use Precision, Recall, F1-Score, and the ROC-AUC curve based on what kind of errors you want to avoid (False Positives vs. False Negatives).

**SMOTE**
- [SMOTE for Imbalanced Classification](https://www.analyticsvidhya.com/blog/2020/10/overcoming-class-imbalance-using-smote-techniques/) This guide perfectly explains the mechanics of SMOTE (Q2). It details how the algorithm selects a minority point, calculates the K-Nearest Neighbors, and mathematically creates a new synthetic point along the line connecting them. It also contrasts this with Undersampling (Q3), discussing the danger of losing valuable information.

**Oversampling and Undersampling**
- [handling imbalance data](https://towardsdatascience.com/oversampling-and-undersampling-explained-a-visual-guide-with-mini-2d-dataset-1155577d3091/)

**Using Class Weight to Compensate for Imbalanced Data**
- [Using Class Weight to Compensate for Imbalanced Data](https://medium.com/@bubbapora_76246/using-class-weight-to-compensate-for-imbalanced-data-6eff370185d3)

**Comprehensive Strategy Guide**
- [Credit Fraud || Dealing with Imbalanced Datasets](https://www.kaggle.com/code/janiobachmann/credit-fraud-dealing-with-imbalanced-datasets) 

---

## Day 22 — Dimensionality Reduction

### Questions

**1.** PCA (Principal Component Analysis) finds:
- a) The most important features by name
- b) Directions of maximum variance in the data
- c) Clusters in the data
- d) The best hyperparameters

**2.** The first principal component captures:
- a) The least variance
- b) The most variance in the data
- c) Only categorical features
- d) The mean of all features

**3.** A major drawback of PCA is:
- a) It's too slow
- b) Transformed features are hard to interpret
- c) It only works with two features
- d) It requires labeled data

**4.** t-SNE is mainly used for:
- a) Feature selection
- b) High-dimensional data visualization in 2D or 3D
- c) Model training
- d) Missing data imputation

**5.** The "curse of dimensionality" means:
- a) Datasets are always too small
- b) As features increase, data becomes sparse and distances lose meaning
- c) Models always overfit
- d) Features must be reduced to exactly 2

### Answers

<details>
<summary>Click to reveal answers</summary>

**1. b) Directions of maximum variance in the data**

PCA rotates data to find new axes along directions of maximum spread. First component = most variance, second = next most, and so on.

**2. b) The most variance in the data**

Each subsequent component captures decreasing variance. Often 2-3 components capture 90%+ of total variance, enabling massive dimension reduction.

**3. b) Transformed features are hard to interpret**

PCA creates linear combinations of original features. "PC1 = 0.5×height + 0.3×weight + ..." is hard to explain to stakeholders.

**4. b) High-dimensional data visualization in 2D or 3D**

t-SNE preserves local neighborhood structure, making clusters visible. Great for visualization but not for feature reduction in models.

**5. b) As features increase, data becomes sparse and distances lose meaning**

In high dimensions, all points become roughly equidistant. KNN, clustering, and distance-based methods suffer. You need exponentially more data.

</details>

### Resources

**The Mechanics of PCA: Variance and Components**
- [Principal Component Analysis (PCA): A Step-by-Step Explanation](https://builtin.com/data-science/step-step-explanation-principal-component-analysis) This article walks through the exact mathematical intuition. It explains how eigenvectors determine the "directions" of maximum variance (Q1) and how eigenvalues dictate how much variance that specific component captures, proving why the first few components hold $90\%+$ of the information (Q2).

**Drawback of PCA**
- [The Advantages and Disadvantages of PCA To Consider Before Using It](https://blog.dailydoseofds.com/p/the-advantages-and-disadvantages)
- [Think twice before you use Principal Component Analysis in supervised learning tasks](https://medium.com/data-science/think-twice-before-you-use-principal-component-analysis-in-supervised-learning-tasks-70fbb68ebd0c)
  
**t-SNE for High-Dimensional Visualization**
- [How to Use t-SNE Effectively](https://distill.pub/2016/misread-tsne/) It visually proves why the algorithm is strictly a visualization tool. It explains how the algorithm preserves "local neighborhood structure" to make clusters visible (Q4), while also warning about how it distorts global distances—which is exactly why you shouldn't use it as a preprocessing step for models.

**Curse of Dimensionality**
- [The Curse of Dimensionality in Machine Learning!](https://www.analyticsvidhya.com/blog/2021/04/the-curse-of-dimensionality-in-machine-learning/) In this article, they tackle the Curse of Dimensionality in machine learning, examining its origins and impact on algorithm performance. it also discuss practical strategies, including dimensionality reduction and feature selection, to mitigate its effects, paving the path for more effective data-driven insights.
---

## Day 23 — Regularization

### Questions

**1.** L1 regularization (Lasso) adds a penalty proportional to:
- a) Sum of squared coefficients
- b) Sum of absolute values of coefficients
- c) Number of features
- d) Learning rate

**2.** L2 regularization (Ridge) tends to:
- a) Set coefficients to exactly zero
- b) Shrink coefficients toward zero but not exactly zero
- c) Increase all coefficients
- d) Remove features randomly

**3.** Elastic Net combines:
- a) L1 and L2 regularization
- b) Bagging and boosting
- c) PCA and LDA
- d) Overfitting and underfitting

**4.** Increasing regularization strength (lambda):
- a) Makes the model more complex
- b) Makes the model simpler (more constrained)
- c) Has no effect
- d) Only affects the intercept

**5.** Regularization is a technique to prevent:
- a) Underfitting
- b) Overfitting
- c) Data leakage
- d) Feature scaling

### Answers

<details>
<summary>Click to reveal answers</summary>

**1. b) Sum of absolute values of coefficients**

L1 penalty = λΣ|wᵢ|. The diamond-shaped constraint means some coefficients hit exactly zero — built-in feature selection.

**2. b) Shrink coefficients toward zero but not exactly zero**

L2 penalty = λΣwᵢ². The circular constraint shrinks all coefficients but rarely to exactly zero. Good when all features are potentially useful.

**3. a) L1 and L2 regularization**

Elastic Net = α×L1 + (1-α)×L2. Gets the best of both: L1's feature selection + L2's stability with correlated features.

**4. b) Makes the model simpler (more constrained)**

Higher lambda = stronger penalty for large coefficients = simpler model. Lambda → ∞ forces all coefficients to zero. Lambda = 0 = no regularization.

**5. b) Overfitting**

Regularization constrains model complexity, preventing it from fitting noise. One of the most fundamental tools against overfitting.

</details>

### Resources

**L1 and L2 Regularization**
- [Understanding l1 and l2 Regularization](https://towardsdatascience.com/understanding-l1-and-l2-regularization-93918a5ac8d0/)

  **Elastic Net Regression**
- [Elastic Net Regression](https://machinelearningmastery.com/elastic-net-regression-in-python/)

  **Regularization Strength ($\lambda$) and Overfitting**
- [How Does Ridge Regression Work?](https://www.analyticsvidhya.com/blog/2016/01/ridge-lasso-regression-python-complete-tutorial/) This comprehensive guide specifically explores what happens to the model as lambda approaches $\infty$ (forcing coefficients to zero) versus when lambda is $0$ (reducing the formula back to standard OLS regression). It perfectly backs up Q4 and Q5 by showing how tuning this single hyperparameter controls the entire bias-variance tradeoff.

   **Visual Intuition of Penalties**
- [StatQuest with Josh Starmer: Regularization Part 1 & 2](https://www.youtube.com/watch?v=Q81RR3yKn30)

---

## Day 24 — Probability & Statistics Basics

### Questions

**1.** Bayes' theorem is used to:
- a) Calculate the mean
- b) Update the probability of an event given new evidence
- c) Find the mode
- d) Measure correlation

**2.** The Central Limit Theorem states that:
- a) All data is normally distributed
- b) Sample means approach a normal distribution as sample size increases
- c) Larger samples have more variance
- d) Probability always sums to 1

**3.** A p-value of 0.03 means:
- a) There's a 3% chance the null hypothesis is true
- b) If the null hypothesis were true, there's a 3% chance of seeing results this extreme
- c) The model is 97% accurate
- d) The effect size is 0.03

**4.** The standard deviation measures:
- a) The center of the data
- b) The spread of data around the mean
- c) The maximum value
- d) The number of outliers

**5.** Correlation does NOT imply:
- a) Association
- b) Linear relationship
- c) Causation
- d) Statistical significance

### Answers

<details>
<summary>Click to reveal answers</summary>

**1. b) Update the probability of an event given new evidence**

P(A|B) = P(B|A)P(A)/P(B). Start with a prior belief → observe evidence → update to posterior belief. The foundation of Bayesian ML.

**2. b) Sample means approach a normal distribution as sample size increases**

Even if the original data is skewed, the distribution of sample MEANS becomes normal with enough samples (usually n > 30). A cornerstone of statistics.

**3. b) If the null hypothesis were true, there's a 3% chance of seeing results this extreme**

Common mistake: p-value is NOT "probability that the null is true." It's the probability of the observed data given the null. If p < 0.05, we typically reject the null.

**4. b) The spread of data around the mean**

Small std dev = data clustered near mean. Large std dev = widely spread. Variance = std dev².

**5. c) Causation**

Ice cream sales and drowning are correlated (both rise in summer). But ice cream doesn't cause drowning — the hidden variable is heat/summer.

</details>

### Resources

**Bayes' Theorem**
- [Bayes Theorem for Machine Learning](https://machinelearningmastery.com/bayes-theorem-for-machine-learning/) This resource explicitly maps the mathematical terms to their names (Prior, Likelihood, Evidence, Posterior) and provides a concrete example of how to update probabilities based on new data.

**Central Limit Theorem**
- [Central Limit Theorem : Definition , Formula & Examples](https://www.analyticsvidhya.com/blog/2019/05/statistics-101-introduction-central-limit-theorem/) It explicitly demonstrates how taking repeated samples from a non-normal dataset (like a heavily skewed one) and plotting their means will eventually result in a perfect Gaussian bell curve, making it a cornerstone for hypothesis testing.

**p-value**
- [Mastering P-values in Machine Learning](https://towardsdatascience.com/mastering-p-values-in-machine-learning-bdc5bd0dd8ae/) This resource strictly defines the p-value the same way our answer does: the probability of observing data this extreme if the null hypothesis is already assumed to be true. It distinguishes between prediction (ML) and inference (Statistics), showing exactly why a p-value $< 0.05$ provides evidence to reject the null.

**Standard Deviation**
- [Fooled by Standard Deviation](https://towardsdatascience.com/fooled-by-standard-deviation-6ed52f83d591/) This article goes a step deeper than a basic definition. It explains the math behind why standard deviation is calculated by squaring the differences from the mean (variance) before taking the square root. It illustrates how a small standard deviation proves the data is clustered, while a large one means it is widely spread out or heavily influenced by outliers.

**Correlation and Causation**
- [Machine Learning Is Not Made for Causal Estimation](https://towardsdatascience.com/why-machine-learning-is-not-made-for-causal-estimation-f2add4a36e85/) This article explicitly addresses the limits of ML. It explains that ML algorithms are built for "predictive inference" (exploiting correlations), not "causal inference." It features the exact scenario we mentioned, explaining how hidden variables (confounders) create spurious correlations that can trick basic models.


---

## Day 25 — Probability Distributions

### Questions

**1.** A coin flip follows which distribution?
- a) Normal
- b) Bernoulli
- c) Poisson
- d) Exponential

**2.** The normal (Gaussian) distribution is defined by:
- a) Mean and mode
- b) Mean and standard deviation
- c) Median and range
- d) Min and max

**3.** Poisson distribution models:
- a) Continuous measurements
- b) Count of events in a fixed interval
- c) Binary outcomes
- d) Correlation between variables

**4.** In a normal distribution, approximately 95% of data falls within:
- a) 1 standard deviation of the mean
- b) 2 standard deviations of the mean
- c) 3 standard deviations of the mean
- d) The full range

**5.** The uniform distribution:
- a) Has a bell curve shape
- b) Every value in a range is equally likely
- c) Only has two outcomes
- d) Models rare events

### Answers

<details>
<summary>Click to reveal answers</summary>

**1. b) Bernoulli**

Bernoulli = single trial with two outcomes (success/failure). Multiple flips → Binomial distribution. Each individual flip → Bernoulli.

**2. b) Mean and standard deviation**

Mean (μ) sets the center. Standard deviation (σ) sets the width. Together they fully define the bell curve. ~68% within 1σ, ~95% within 2σ.

**3. b) Count of events in a fixed interval**

Examples: emails per hour, accidents per month, website visits per day. Models rare, independent events in a fixed time window.

**4. b) 2 standard deviations of the mean**

The 68-95-99.7 rule: 68% within 1σ, 95% within 2σ, 99.7% within 3σ. Also called the empirical rule.

**5. b) Every value in a range is equally likely**

Like rolling a fair die — each outcome has equal probability. No peaks or valleys. Completely flat probability distribution.

</details>

### Resources

**Normal Distribution & The Empirical Rule**
- [Normal Distribution](https://www.mathsisfun.com/data/standard-normal-distribution.html) This resource clearly breakdown the Empirical Rule (Q4). It explains exactly why approximately $95\%$ of the data falls within $2$ standard deviations and shows how changing the mean and standard deviation (Q2) mathematically stretches or shifts the bell curve without changing its fundamental properties.

**Probability Distribution in Data Science**
- [6 Types of Probability Distribution](https://www.analyticsvidhya.com/blog/2017/09/6-probability-distributions-data-science/) This is a "cheat sheet" style article. It lines up Bernoulli, Uniform, Poisson, and Normal distributions side-by-side, providing the probability mass/density functions for each and explaining exactly when to apply them based on whether your target variable is continuous, binary, or a time-based count.

---

## Day 26 — Gradient Descent

### Questions

**1.** Gradient descent is used to:
- a) Generate new data
- b) Minimize the loss function by updating parameters
- c) Split data into train and test
- d) Select features

**2.** The learning rate controls:
- a) The number of features
- b) The size of each parameter update step
- c) The number of training samples
- d) The model architecture

**3.** If the learning rate is too large:
- a) Training is very slow
- b) The algorithm may overshoot and diverge
- c) The model underfits
- d) Nothing happens

**4.** Stochastic Gradient Descent (SGD) updates parameters using:
- a) The entire dataset at once
- b) A single random sample per update
- c) Only the test set
- d) The validation set

**5.** Mini-batch gradient descent:
- a) Uses the entire dataset per update
- b) Uses a small random subset per update
- c) Only works with linear models
- d) Requires no learning rate

### Answers

<details>
<summary>Click to reveal answers</summary>

**1. b) Minimize the loss function by updating parameters**

Gradient descent calculates the slope of the loss function and steps in the direction that reduces loss. Repeat until convergence.

**2. b) The size of each parameter update step**

Too small = slow convergence. Too large = overshooting. Finding the right learning rate is crucial. Common values: 0.001, 0.01.

**3. b) The algorithm may overshoot and diverge**

Large steps can jump past the minimum, bounce around, and the loss can increase instead of decrease. Training "explodes."

**4. b) A single random sample per update**

SGD is noisy but fast. Each update uses one random example. The noise can help escape local minima but makes convergence jerky.

**5. b) Uses a small random subset per update**

Mini-batch (e.g., 32 or 64 samples) balances speed and stability. Less noisy than SGD, faster than full-batch. Most common in practice.

</details>

### Resources

**Gradient Descent**
- [Gradient Descent Algorithm and it's Working](https://www.analyticsvidhya.com/blog/2020/10/how-does-the-gradient-descent-algorithm-work-in-machine-learning/) This guide explicitly walks through the math of calculating the slope (derivatives) to minimize the loss function (Q1). It features excellent visual diagrams showing a "ball rolling down a hill," demonstrating exactly what happens mathematically when the learning rate step is too large and bounces out of the valley (Q3), versus finding the optimal step size (Q2).
  
**Impact of Learning Rate**
- [Understand the Impact of Learning Rate](https://machinelearningmastery.com/understand-the-dynamics-of-learning-rate-on-deep-learning-neural-networks/)

**Batch, Mini Batch & Stochastic Gradient Descent**
- [SGD vs. Mini-Batch vs. Full Batch](https://medium.com/data-science/batch-mini-batch-stochastic-gradient-descent-7a62ecba642a)

**Batch Gradient Descent VS Stochastic Gradient Descent**
- [Difference between Batch Gradient Descent and Stochastic Gradient Descent](https://www.geeksforgeeks.org/machine-learning/difference-between-batch-gradient-descent-and-stochastic-gradient-descent/)

---

## Day 27 — Model Selection & Hyperparameters

### Questions

**1.** Hyperparameters are:
- a) Learned from training data automatically
- b) Set before training begins
- c) Always the same for every model
- d) The model's predictions

**2.** Grid search:
- a) Randomly samples hyperparameter combinations
- b) Tries all possible combinations from a predefined grid
- c) Only works with decision trees
- d) Requires no validation set

**3.** Random search advantage over grid search:
- a) It's always more accurate
- b) It can explore the space more efficiently with many hyperparameters
- c) It requires no computation
- d) It always finds the global optimum

**4.** The validation set is used for:
- a) Final performance reporting
- b) Tuning hyperparameters and model selection
- c) Training the model
- d) Data preprocessing

**5.** Which is a hyperparameter of a Random Forest?
- a) The learned split thresholds
- b) Number of trees (n_estimators)
- c) The training data
- d) The predicted labels

### Answers

<details>
<summary>Click to reveal answers</summary>

**1. b) Set before training begins**

Hyperparameters: learning rate, number of trees, max depth, etc. Parameters (weights, coefficients) are learned FROM data. Hyperparameters are set BY you.

**2. b) Tries all possible combinations from a predefined grid**

Grid search is exhaustive. 5 learning rates × 4 depths × 3 estimators = 60 combinations. Thorough but computationally expensive.

**3. b) It can explore the space more efficiently with many hyperparameters**

Random search samples randomly from ranges. With many hyperparameters, it covers more of the space in fewer trials than grid search.

**4. b) Tuning hyperparameters and model selection**

Train on training set → tune using validation set → report final performance on test set. Never tune on test set — that causes optimistic bias.

**5. b) Number of trees (n_estimators)**

n_estimators, max_depth, min_samples_split are hyperparameters you set. Split thresholds and feature importances are learned during training.

</details>

### Resources

**Parameters vs. Hyperparameters**
- [Difference Between a Parameter and a Hyperparameter](https://machinelearningmastery.com/difference-between-a-parameter-and-a-hyperparameter/)

**A Comprehensive Guide on Hyperparameter Tuning**
- [A Comprehensive Guide on Hyperparameter Tuning and its Techniques](https://www.analyticsvidhya.com/blog/2022/02/a-comprehensive-guide-on-hyperparameter-tuning-and-its-techniques/) This guide provides a direct comparison between the two methods. It explains the exact math of Grid Search combinations (Q2) and details why Random Search is statistically proven to find optimal models faster when certain hyperparameters matter more than others (Q3).

**Test and Validation sets**
- [What is the Difference Between Test and Validation Datasets](https://machinelearningmastery.com/difference-test-validation-datasets/) This article addresses the widespread confusion between these two splits. It clearly outlines the standard ML pipeline workflow: Train (to learn parameters) $\rightarrow$ Validate (to tune hyperparameters) $\rightarrow$ Test (for unbiased final evaluation). It explains exactly why using the test set for tuning ruins the integrity of your final metric.

**Hyperparameter Tuning example**
- [Hyperparameter Tuning the Random Forest in Python](https://towardsdatascience.com/hyperparameter-tuning-the-random-forest-in-python-using-scikit-learn-28d2aa77dd74/) It walks through building a hyperparameter grid specifically for a Random Forest model (tying into Q5) and implements a RandomizedSearchCV to show exactly why it explores the space more efficiently than a standard Grid Search.

---

## Day 28 — Practical ML Concepts

### Questions

**1.** The "No Free Lunch" theorem states:
- a) One algorithm always beats all others
- b) No single algorithm works best for every problem
- c) Deep learning is always better
- d) More data is always better

**2.** Occam's Razor in ML suggests:
- a) Use the most complex model
- b) Prefer simpler models that explain the data well
- c) Always use ensemble methods
- d) Remove all features

**3.** A baseline model is important because:
- a) It always gives the best results
- b) It provides a minimum performance benchmark to beat
- c) It replaces cross-validation
- d) It eliminates the need for feature engineering

**4.** "Model drift" refers to:
- a) The model becoming faster over time
- b) Data distribution changing so the model becomes less accurate
- c) The model increasing in size
- d) The learning rate decreasing

**5.** A/B testing in ML is used to:
- a) Compare two models in a real-world setting
- b) Split data into train and test
- c) Perform cross-validation
- d) Select features

### Answers

<details>
<summary>Click to reveal answers</summary>

**1. b) No single algorithm works best for every problem**

The best model depends on data size, type, noise level, and the specific problem. Always try multiple approaches and compare.

**2. b) Prefer simpler models that explain the data well**

If a linear model performs nearly as well as a complex ensemble, prefer the simpler one. Easier to interpret, debug, and deploy.

**3. b) It provides a minimum performance benchmark to beat**

Always start with a simple baseline (mean prediction, majority class). If your fancy model barely beats it, something is wrong.

**4. b) Data distribution changing so the model becomes less accurate**

Real-world data evolves. Customer behavior changes, new products launch. A model trained on old data may fail later. Monitor and retrain regularly.

**5. a) Compare two models in a real-world setting**

A/B testing shows model A to half of users, model B to the other half. Measures actual business impact, not just offline metrics.

</details>

### Resources

**The Philosophy of ML: No Free Lunch & Occam’s Razor**
- [A Gentle Introduction to the No Free Lunch Theorem](https://machinelearningmastery.com/no-free-lunch-theorem-for-machine-learning/) it explains exactly why our answer states "always try multiple approaches and compare"—because without looking at the specific data, a neural network is mathematically no better than a basic decision tree.
- [Ensemble Learning Algorithm Complexity and Occam’s Razor](https://machinelearningmastery.com/ensemble-learning-and-occams-razor/)

**baseline Model**
- [How To Get Baseline Results And Why They Matter](https://machinelearningmastery.com/how-to-get-baseline-results-and-why-they-matter/) This guide explains how to generate the baselines(mean prediction for regression, majority class for classification) so you can prove your "fancy model" is actually learning.

**Model Drift**
- [Why You Should Care About Data and Concept Drift](https://www.evidentlyai.com/blog/machine-learning-monitoring-data-and-concept-drift) This comprehensive guide distinguishes between "Concept Drift" (the meaning of the target variable changes) and "Data Drift" (the input features change). It reinforces our key point: models don't break like traditional software; they decay, meaning you must actively monitor and retrain them.

**A/B testing**
- [A/B Testing Machine Learning Models](https://mlinproduction.com/ab-test-ml-models-deployment-series-08/)
- [The What, Why, and How of A/B Testing in Machine Learning](https://mlops.community/blog/the-what-why-and-how-of-a-b-testing-in-ml)
- These article bridges the gap between data science and product management. It explains how to route half of your live users to Model A (the control) and the other half to Model B (the challenger) to measure the exact "actual business impact" mentioned in your answer key.

---

## Day 29 — Data Preprocessing

### Questions

**1.** Standard scaling (Z-score normalization) transforms features to have:
- a) Range [0, 1]
- b) Mean 0 and standard deviation 1
- c) All positive values
- d) Median 0

**2.** Min-Max scaling transforms features to:
- a) Mean 0, std 1
- b) A fixed range, typically [0, 1]
- c) Log scale
- d) Binary values

**3.** When should you fit the scaler?
- a) On the entire dataset including test
- b) On the training data only
- c) On the test data only
- d) After making predictions

**4.** Outlier detection using the IQR method flags values:
- a) Above the mean
- b) Below Q1 - 1.5×IQR or above Q3 + 1.5×IQR
- c) More than 1 standard deviation from the mean
- d) In the bottom 10%

**5.** Encoding target variable for multi-class classification:
- a) Always use one-hot encoding
- b) Use label encoding (0, 1, 2, ...)
- c) Leave as strings
- d) Convert to continuous values

### Answers

<details>
<summary>Click to reveal answers</summary>

**1. b) Mean 0 and standard deviation 1**

z = (x - mean) / std. Centers data at 0 with unit variance. Important for SVM, KNN, logistic regression, and neural networks.

**2. b) A fixed range, typically [0, 1]**

x_scaled = (x - min) / (max - min). Good when you know the bounds. Sensitive to outliers — one extreme value compresses everything else.

**3. b) On the training data only**

Fit on train, then TRANSFORM both train and test with the same parameters. Fitting on test = data leakage.

**4. b) Below Q1 - 1.5×IQR or above Q3 + 1.5×IQR**

IQR = Q3 - Q1 (interquartile range). This method is robust because it's based on quartiles, not mean/std which are affected by outliers themselves.

**5. b) Use label encoding (0, 1, 2, ...)**

Target variables in classification get integer labels. Scikit-learn's LabelEncoder handles this. One-hot encoding for targets is only used in specific frameworks.

</details>

### Resources

**Standardization & Normalization**
- [Feature Scaling and Why is it Important](https://www.analyticsvidhya.com/blog/2020/04/feature-scaling-machine-learning-normalization-standardization/) This guide provides the exact mathematical formulas for both techniques. It explicitly  shows how a single extreme outlier will completely compress the rest of the data in Min-Max scaling, which is why Z-score normalization (Q1) is often preferred for algorithms like SVMs and Neural Networks.

**Data Leakage**
-  [How to Avoid Data Leakage When Performing Data Preparation][(https://machinelearningmastery.com/data-preparation-without-data-leakage/) This resource breaks down the strict protocol for the .fit() and .transform() methods. It explains exactly why you must fit the scaler on the training data only, and then use that exact same scaler to transform the test data.

**Outlier detection**
- [Outlier Detection Methods](https://www.analyticsvidhya.com/blog/2021/05/feature-engineering-how-to-detect-and-remove-outliers-with-python-code/)
- [Outlier detection methods in Machine Learning](https://towardsdatascience.com/outlier-detection-methods-in-machine-learning-1c8b7cca6cb8/)
  
**Encoding Target Variables**
- [LabelEncoder](https://scikit-learn.org/stable/modules/generated/sklearn.preprocessing.LabelEncoder.html) The official documentation explicitly states the best practice outlined in your answer. It notes that LabelEncoder should be used to transform non-numerical labels (as long as they are hashable and comparable) into integers ($0, 1, 2, ...$), and it strictly warns that this should be used for encoding target values (y), not the input features (X).
- [Detailed Insights on Encoders in Machine Learning](https://code-b.dev/blog/encoders-machine-learning)

---

## Day 30 — ML Pipeline & Final Review

### Questions

**1.** The typical ML pipeline order is:
- a) Model → Data → Evaluate → Deploy
- b) Data Collection → Preprocessing → Training → Evaluation → Deployment
- c) Deploy → Train → Collect Data
- d) Feature Engineering → Data Collection → Deployment

**2.** Why should feature engineering be done BEFORE cross-validation?
- a) To speed things up
- b) It shouldn't — feature engineering inside CV prevents data leakage
- c) To reduce the number of folds
- d) To increase accuracy

**3.** Which step catches data leakage, incorrect preprocessing, and overfitting?
- a) Data collection
- b) Proper validation strategy
- c) Model deployment
- d) Feature selection

**4.** Ensemble methods work best when base models are:
- a) All identical
- b) Diverse and make different errors
- c) All very complex
- d) Trained on the same data without randomization

**5.** The most important skill in practical ML is:
- a) Memorizing every algorithm
- b) Understanding data, asking the right questions, and iterating
- c) Using the newest framework
- d) Having the most GPU power

### Answers

<details>
<summary>Click to reveal answers</summary>

**1. b) Data Collection → Preprocessing → Training → Evaluation → Deployment**

The standard pipeline. In practice it's iterative — you go back and forth. But the logical flow is: get data → clean it → model it → evaluate → deploy.

**2. b) It shouldn't — feature engineering inside CV prevents data leakage**

If you engineer features using the full dataset then split for CV, the validation fold has seen information from the training folds. Always transform INSIDE each fold.

**3. b) Proper validation strategy**

A good validation strategy (stratified CV, proper holdout, no leakage) is your safety net. It catches overfitting, bad preprocessing, and unrealistic metrics.

**4. b) Diverse and make different errors**

If all models make the same mistakes, combining them doesn't help. Diversity is key — different algorithms, different features, different random seeds.

**5. b) Understanding data, asking the right questions, and iterating**

ML is 80% data understanding, 20% modeling. Knowing your data, defining the right problem, and iterating based on results matters more than any fancy algorithm.

</details>

### Resources

**Machine Learning Pipeline**
- [ML pipeline](https://www.ibm.com/think/topics/machine-learning-pipeline) IBM provides a comprehensive breakdown of the standard ML workflow. It explicitly details the three major stages (Data Processing, Model Development, and Model Deployment). It explains why data processing (collecting, wrangling, cleaning) must happen first, followed by model training/evaluation, and finally deployment.

  **Proper validation strategy**
  - [Validation in Machine Learning](https://www.coursera.org/articles/what-is-cross-validation-in-machine-learning) This article details exactly how partitioning data properly prevents a model from memorizing noise. It walks through k-fold cross-validation step-by-step, explaining how evaluating the model across multiple validation datasets catches overfitting (when a model performs perfectly on training data but poorly on the validation folds).

 **Preventing Data Leakage**
 - [12. Common pitfalls and recommended practices](https://scikit-learn.org/stable/common_pitfalls.html)
 - [Data Leakage Tutorial](https://www.kaggle.com/code/alexisbcook/data-leakage)

**Ensemble Diversity**
- [Introduction to Ensemble Diversity for Machine Learning](https://machinelearningmastery.com/ensemble-diversity-for-machine-learning/) This article dives into the specific heuristic of ensemble diversity. It explains the exact logic of Q4: a powerful ensemble strictly relies on contributing models making different errors for the same inputs. It details how to mathematically force this diversity by varying the algorithms, training data subsets, or hyperparameter initializations.

**Rules of Machine Learning**
- [Best Practices for ML Engineering](https://developers.google.com/machine-learning/guides/rules-of-ml) This is an industry-standard manifesto for deploying ML in the real world. It strongly backs up our answer for Q5, specifically through different directives and the emphasis on deeply understanding the data metrics and the exact problem you are trying to solve before ever spinning up a complex deep learning framework.
- 
---

## 🎉 Challenge Complete!

Congratulations on completing 150 ML interview questions! Here's what to do next:

1. **Revisit** topics where you struggled
2. **Check the resources** sections for deeper learning
3. **Practice** explaining concepts in your own words — that's the real test

---

## 🤝 Contributing

Want to improve a question, add resources, or fix an explanation? PRs are welcome!

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

*Built with consistency and community in mind. One question at a time.* 💪
