# Student Performance Analysis

This project analyzes the student performance dataset to explore various factors affecting students' final grades. It uses Python libraries such as Pandas, Matplotlib, and Seaborn to load, clean, visualize, and analyze the data.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Data Description](#data-description)
- [Key Findings](#key-findings)
- [Visualizations](#visualizations)
- [Contributing](#contributing)
- [License](#license)

## Installation

To run this project, you need to have Python installed along with the following libraries:

- `pandas`
- `matplotlib`
- `seaborn`

## Usage

The script will output basic statistics and visualizations of the data.

## Data Description

The dataset used for this analysis is `student_mat.csv`, which contains the following columns:

- **school**: Student's school
- **sex**: Student's sex
- **age**: Student's age
- **address**: Student's home address type
- **famsize**: Family size
- **Pstatus**: Parent's cohabitation status
- **Medu**: Mother's education level
- **Fedu**: Father's education level
- **Mjob**: Mother's job
- **Fjob**: Father's job
- **reason**: Reason to choose this school
- **guardian**: Student's guardian
- **traveltime**: Travel time to school
- **studytime**: Weekly study time
- **failures**: Number of past class failures
- **schoolsup**: Extra educational support
- **famsup**: Family educational support
- **paid**: Extra paid classes within the course subject
- **activities**: Extra-curricular activities
- **nursery**: Attended nursery school
- **higher**: Wants to take higher education
- **internet**: Internet access at home
- **romantic**: With a romantic relationship
- **famrel**: Quality of family relationships
- **freetime**: Free time after school
- **goout**: Going out with friends
- **Dalc**: Workday alcohol consumption
- **Walc**: Weekend alcohol consumption
- **health**: Current health status
- **absences**: Number of school absences
- **G1**: First period grade
- **G2**: Second period grade
- **G3**: Final grade

## Key Findings

- There is a strong correlation between study time and final grades.
- Female students generally perform better than male students.
- Higher parental education levels are associated with better student performance.
- Students with extracurricular activities tend to have higher final grades.

## Visualizations

The analysis includes the following visualizations:

- **Distribution of Final Grades (G3)**: 
  - Histogram and KDE plot showing the distribution of final grades.
  
- **Boxplot of Final Grades by Gender**: 
  - Comparison of final grades by gender.
  
- **Pair Plot of Grades**: 
  - Scatter plot matrix to visualize relationships between G1, G2, and G3.
  
- **Average Final Grades by Mother's Job**: 
  - Bar plot showing average grades based on the mother's occupation.
  
- **Final Grades by Study Time**: 
  - Box plot comparing final grades based on weekly study time.
  
- **Scatter Plot of Study Time vs. Final Grades**: 
  - Visualizing the relationship between study time and final grades.
  
- **Average Final Grades by Family Size**: 
  - Bar plot comparing average grades based on family size.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request.

## License

This project is licensed under the MIT License. See the LICENSE file for details.



