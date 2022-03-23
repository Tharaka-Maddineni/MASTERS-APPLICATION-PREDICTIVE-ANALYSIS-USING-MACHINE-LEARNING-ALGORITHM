# Masters-Admission-Prediction
Masters-Admission-Prediction is a Machine Learning based web application. This application was built with the purpose of helping students in shortlisting universities with their profiles. The predicted output gives them a fair idea about their chances for a particular university.

Context : This app is created for the prediction of Graduate Admissions from an Indian perspective.
Content : The dataset contains several parameters which are considered important during the application for Masters Programs.

The parameters included are :
- GRE Scores ( out of 340 )
- TOEFL Scores ( out of 120 )
- University Rating ( out of 5 )
- Statement of Purpose Strength ( out of 5 )
- Letter of Recommendation Strength ( out of 5 )
- Undergraduate GPA ( out of 10 )
- Research Experience ( either 0 or 1 )

Output : 
- Chances of Admission :  range in ( 0% - 100 %)


## How to run the app.
1. Either fork or download the app and open the folder in any IDE or CLI.
2. Install all the dependencies mentioned in the requirements.txt file.
3. Start the web server using `python application.py` in the terminal/CLI or run the application in the IDE.
4. The app will be served at http://localhost:5000/.
5. Go to http://localhost:5000/ in your browser and pass required input fields and get results.

## Dependencies
- Python 3.6
- flask
- pandas
- psycopg2
- scipy
- scikit-learn
- sklearn
