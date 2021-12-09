Explanation:

Method : Multinomial Naive Bayes Algorithm

Here in the dataset we have multiple classes with independent features so if we calculate the occurance of each element i.e the number of times it appears.
Then it will be easy for us to classify all the classes .

Training Datasets: 20188 records
Testing Datasets : 10094 records
Total no of classes: 2

Approach 1:

1. First I remove all the "None" features from the training dataset
2. Normalize the texts
3. Use count_vectorizer for feature extraction
4. Split the train & test set.
5. Applying multinomial bayes algorithm for training.
6. Got accuracy of 82% .


Approach 2:

1. Considering the "None" features from the training dataset.(Considering random 4123 data for "None" feature)
2. Normalize the texts
3. Use count_vectorizer for feature extraction
4. Split the train & test set.
5. Applying multinomial bayes algorithm for training.
6. Got accuracy of 55%.
