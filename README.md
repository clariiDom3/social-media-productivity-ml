# social-media-productivity-ml


Social Media Usage and Productivity Analysis

Author: Clarissa Dominguez
Program: M.S. Artificial Intelligence

⸻

Project Overview

This project looks at how social media usage relates to productivity loss and a concept often referred to as “brain rot,” which describes reduced focus and mental engagement due to excessive digital consumption.

Using machine learning, I trained a classification model to predict whether a user is experiencing brain rot based on their social media habits and productivity-related features.

⸻

Problem Description

Social media platforms are built to keep users engaged, but overuse can negatively affect focus and productivity. The goal of this project was to see whether patterns in social media behavior could be used to predict productivity-related cognitive decline.

This was framed as a binary classification problem:
	•	0 – No brain rot
	•	1 – Brain rot

⸻

Data Used

Two datasets were used in this project:
	•	Brain Rot Dataset
Contains labels indicating whether a user is experiencing brain rot.
	•	Time Wasters on Social Media Dataset
Includes information such as time spent, number of sessions, engagement levels, and productivity loss.

The datasets were cleaned, combined, and prepared for machine learning.

⸻

Approach
	1.	Cleaned and preprocessed the data
	2.	Selected relevant features related to usage and productivity
	3.	Split the data into training and testing sets
	4.	Trained a supervised classification model
	5.	Evaluated the model using accuracy, precision, recall, and F1-score

⸻

Results

The model performed very well on the test data:
	•	Accuracy: ~99.7%
	•	Only one sample was misclassified
	•	Both classes achieved high precision and recall

These results suggest that social media behavior patterns can strongly indicate productivity-related cognitive effects.

⸻

Tools & Technologies

	•	Python
	
	•	pandas
	
	•	numpy
	
	•	scikit-learn
	
	•	Jupyter Notebook

⸻

How to Run the Project
	1.	Clone the repository:

  git clone https://github.com/your-username/your-repo-name.git
  
  2. Open the notebook:
  
  jupyter notebook Final_Project_ML_ClarissaDominguez.ipynb
  
  3. Run the cells in order.
