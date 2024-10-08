# CS313.O21

# Repo Description
- This is our team final project repository for class CS313.021. The main goal of this problem is to label and evaluate courses using machine learning and statistical methods.
- Dataset: MOOCCubeX (https://github.com/THU-KEG/MOOCCubeX/tree/main)
# Team Information 
### Instructor: Ms.C Nguyễn Thị Anh Thư

### Team:
|No.|Member|Student ID|
|:-:|:--|:-:|
|1|[Bui Huynh Kim Uyen](https://github.com/uyenbhku)|21521659|
|2|[Nguyen Nguyen Giap](https://github.com/Paignn)|21522025|
|3|[Nguyen Bui Thanh Mai](https://github.com/mainbt)|21522320|
|4|[Le Thi Nhu Y](https://github.com/lethinhuy20)|21522818|
|5|[Ho Dinh Duy](https://github.com/Hodnduy)|21520769|

# Data preprocessing and labelling
We decided to process the data according to 6 criteria:
- Criterion 1: Average learner's feelings towards the course
- Criterion 2: The school's actual ranking on the US News world rankings.
- Criterion 3: Reputation of lecturers.
- Criterion 4: Ratio of students completing the course out of the total number of students registered for the course.
- Criterion 5: Evaluate student engagement in each course based on average video viewing time.
- Criterion 6: Evaluate student engagement in each course based on average homework completion rate.

# Model
- Based on the input data and the output is the quality of the course labeled from 1 to 5 stars, our model uses a two-dimensional LSTM model and combines its output with meta data.

# Result
- F1-score: 0.71
- Accuracy: 0.72
- The research results have shown the potential application of machine learning methods in analyzing and evaluating courses, thereby bringing significant improvements in managing and improving the quality of education.
- However, to achieve these results, we faced many challenges in data processing and analysis, such as data quality issues, feasibility of machine learning models , and the accuracy of the labeling results.
