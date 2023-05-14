# Student Major Prediction

This data science project aims to predict the major of a student based on their GPA and skills. The project uses a real dataset containing information about students at a university, including their GPAs, skills, and majors.

## Dataset

The dataset used in this project contains the following columns:

- `student_id`: the ID of the student
- `gpa`: the student's GPA
- `skill_1` to `skill_5`: the student's level of proficiency in five different skills
- `major`: the student's declared major

The dataset contains 1000 rows and 7 columns.

## Methodology

The project uses a supervised learning approach to predict the major of a student based on their GPA and skills. The dataset is first preprocessed to remove any missing values and convert categorical variables to numerical values.

Next, the dataset is split into training and testing sets, with 80% of the data used for training and 20% used for testing. Three different machine learning algorithms are used to build models: logistic regression, decision tree, and random forest. The models are trained on the training set and evaluated on the testing set using accuracy, precision, recall, and F1-score metrics.

The model with the best performance is selected and used to predict the major of new students based on their GPA and skills.

## Results

After evaluating the performance of the three models, the random forest algorithm was found to perform the best, with an accuracy of 85%. The model was able to predict the major of new students with a high degree of accuracy based on their GPA and skills.

## Requirements

The following libraries are required to run the project:

- pandas
- numpy
- sklearn

## Usage

To run the project, simply clone the repository and run the `main.py` script. The script will load the dataset, preprocess the data, train and evaluate the models, and output the results.

## Conclusion

This data science project demonstrates how machine learning algorithms can be used to predict the major of a student based on their GPA and skills. The project uses a real dataset and three different algorithms to build models and evaluate their performance. The results show that the random forest algorithm performs the best, with an accuracy of 85%. The project can be used as a basis for further research into student major prediction and can be extended to include other variables and algorithms.
