classifier = XGBClassifier

feature used = review_title , review_description , points , price 

** I avoided using country , provience , region columns in the final model as i had to encode the values but the values were too diverse 
and if i use label encoding it would result in data leakage or throw 
unseen value error while encoding ***

accuracy = 88% 