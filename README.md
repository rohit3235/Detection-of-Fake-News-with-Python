# Detection-of-Fake-News-with-Python
This advanced python project of detecting fake news deals with fake and real news. 
Using sklearn, we build a TfidfVectorizer on our dataset.Then, we initialize a PassiveAggressive Classifier and fit the model. In the end, the accuracy score and the confusion matrix tell us how well our model fares.
The dataset we’ll use for this python project- we’ll call it news.csv. This dataset has a shape of 7796×4. The first column identifies the news, the second and third are the title and text, and the fourth column has labels denoting whether the news is REAL or FAKE. 
You’ll need to install the following libraries with pip:

pip install numpy, 
pip install pandas, 
pip install sklearn,
