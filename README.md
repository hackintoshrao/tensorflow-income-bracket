# tensorflow-income-bracket
Predicting whether the income > 50K based on the information about the individuals.

Here are the input parameters available in the dataset 
'age', 'workclass', 'fnlwgt', 'education', 'education_num','marital_status', 'occupation', 'relationship', 'race', 'gender',
'capital_gain', 'capital_loss', 'hours_per_week', 'native_country',
    
The output named 'income_bracket' tells us  predict whether the income is greater than 50K    
   
Here is the sample dataset

age          workclass  fnlwgt   education  education_num  \
0   50   Self-emp-not-inc   83311   Bachelors             13
1   38            Private  215646     HS-grad              9
2   53            Private  234721        11th              7
3   28            Private  338409   Bachelors             13
4   37            Private  284582     Masters             14

        marital_status          occupation    relationship    race   gender  \
0   Married-civ-spouse     Exec-managerial         Husband   White     Male
1             Divorced   Handlers-cleaners   Not-in-family   White     Male
2   Married-civ-spouse   Handlers-cleaners         Husband   Black     Male
3   Married-civ-spouse      Prof-specialty            Wife   Black   Female
4   Married-civ-spouse     Exec-managerial            Wife   White   Female

   capital_gain  capital_loss  hours_per_week  native_country  income_bracket
0             0             0              13   United-States               0
1             0             0              40   United-States               0
2             0             0              40   United-States               0
3             0             0              40            Cuba               0
4             0             0              40   United-States               0
