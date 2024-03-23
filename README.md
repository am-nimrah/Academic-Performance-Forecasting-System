# Academic Performance Forecasting System

This project aims to forecast academic performance based on student demographic and environmental factors. The system utilizes a machine learning model to predict student grades, allowing educational institutions to identify at-risk students and provide targeted interventions.

## Dataset

The dataset used for this project is `student_data.csv`, which contains information about students' demographics, family background, study habits, and academic performance. The dataset includes the following columns:

- `school`: Student's school (binary: 'GP' for Gabriel Pereira or 'MS' for Mousinho da Silveira)
- `sex`: Student's gender (binary: 'F' for female or 'M' for male)
- `age`: Student's age (numeric: from 15 to 22)
- `address`: Student's home address type (binary: 'U' for urban or 'R' for rural)
- `famsize`: Family size (binary: 'LE3' for less or equal to 3 or 'GT3' for greater than 3)
- `Pstatus`: Parent's cohabitation status (binary: 'T' for living together or 'A' for apart)
- `Medu`: Mother's education (numeric: 0 - none, 1 - primary education (4th grade), 2 – 5th to 9th grade, 3 – secondary education or 4 – higher education)
- `Fedu`: Father's education (numeric: 0 - none, 1 - primary education (4th grade), 2 – 5th to 9th grade, 3 – secondary education or 4 – higher education)
- `Mjob`: Mother's job
- `Fjob`: Father's job
- `reason`: Reason to choose this school
- `guardian`: Student's guardian
- `traveltime`: Home to school travel time
- `studytime`: Weekly study time
- `failures`: Number of past class failures
- `schoolsup`: Extra educational support
- `famsup`: Family educational support
- `paid`: Extra paid classes within the course subject
- `activities`: Extra-curricular activities
- `nursery`: Attended nursery school
- `higher`: Wants to take higher education
- `internet`: Internet access at home
- `romantic`: In a romantic relationship
- `famrel`: Quality of family relationships
- `freetime`: Free time after school
- `goout`: Going out with friends
- `Dalc`: Workday alcohol consumption
- `Walc`: Weekend alcohol consumption
- `health`: Current health status
- `absences`: Number of school absences
- `G1`: First period grade (numeric: from 0 to 20)
- `G2`: Second period grade (numeric: from 0 to 20)
- `G3`: Final grade (numeric: from 0 to 20, output target)

## Usage

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/am-nimrah/Academic-Performance-Forecasting-System.git
   ```

2. **Install Dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the Code:**
   ```bash
   python academic_performance_forecasting.py
   ```

## Results

The model achieved a Mean Squared Error (MSE) of approximately 3.49 when evaluated on the test set, indicating good performance in predicting student grades.

## Future Improvements

- Feature engineering to extract more meaningful information from the existing features.
- Experiment with different machine learning algorithms and hyperparameter tuning to improve prediction accuracy.
- Incorporate additional datasets or features that may influence academic performance, such as socio-economic factors or extracurricular activities.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
