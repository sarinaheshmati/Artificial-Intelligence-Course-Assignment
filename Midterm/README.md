# AI Midterm Practical Exam: Clustering Football Players & Farsi Digits Classification

This repository contains the solutions to the midterm practical exam for the Artificial Intelligence course. The exam focused on two key AI tasks: **Clustering** and **Minimum Distance Classification (MDC)**. Below is a summary of the tasks and the approach used to solve them.

## 1. Clustering Football Players: Is Mbappé More Similar to Ronaldo Than Messi?

### Overview
In this task, we explored clustering techniques to analyze the playing styles of football players based on FIFA 23 ratings. The dataset includes 87 features for over 18,000 players, and the focus was on identifying clusters of players with similar attributes, especially comparing Kylian Mbappé to Lionel Messi and Cristiano Ronaldo.

### Steps:
1. **Data Preprocessing:**
   - Selected players with a rating above 85, resulting in 91 players.
   - Removed non-numeric features.
   - Normalized the data.
   - Applied Principal Component Analysis (PCA) to reduce the dimensions to 2.

2. **Clustering with K-Means:**
   - Performed K-means clustering with `k = 5`.
   - Visualized the clusters, attaching player names to each data point.

3. **Comparison of Player Styles:**
   - Analyzed and compared the clusters to determine the similarity of Mbappé's playing style to that of Messi and Ronaldo.
   - Extended the analysis to include Mehdi Taremi.

4. **Clustering Based on Positions:**
   - Clustered all players using `k = 16` (representing 16 distinct positions).
   - Calculated the clustering accuracy.
   - Identified which positions were clustered most accurately.

### Results:
- The clustering results provide insights into the similarities and differences between the playing styles of top football players. Additionally, clustering accuracy was evaluated to see how well the approach categorizes players based on their on-field positions.

## 2. Minimum Distance Classifier (MDC) for OCR: Classifying Farsi Digits

### Overview
This task focused on applying the Minimum Distance Classifier (MDC) to the problem of Optical Character Recognition (OCR) for Farsi digits. The dataset used was a subset of the Hoda dataset, containing binary images of handwritten digits.

### Steps:
1. **Prototype Calculation:**
   - Used the training set to calculate the prototype (mean vector) for each digit class.
   - Displayed the prototypes for visual inspection.

2. **Evaluation of MDC Classifier:**
   - Applied the MDC classifier to the test set.
   - Calculated the error rate of the classifier.
   - Displayed five examples of erroneous predictions to analyze misclassifications.

### Results:
- The MDC classifier provided a straightforward yet effective approach for classifying Farsi digits. The error rate and examples of misclassifications offer insights into the limitations and potential improvements for the classifier.

## Conclusion
This exam covered important AI concepts like clustering and MDC, applied to real-world datasets. The results showcase the practical use of AI techniques in analyzing sports data and recognizing handwritten digits.

