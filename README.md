# Email-categorization
Categorize Emails according to labels

Emails have become one of the major applications in daily life. The continuous growth in the number of email users has led to a massive increase of unsolicited emails, which are also known as spam emails. Managing and classifying this huge number of emails is an important challenge.I  have used two different approaches here—Naïve Bayes classifier and k-nearest neighbors algorithm. The Naïve Bayes classifier is based on a probabilistic model, while the k-nearest neighbors algorithm is based on a similarity measure with the training emails. 

1.Clone the repo
2.Select your directory 
3.pip install -r requirements.txt

Run:-python main.py



Step 1:-
Choose any one option:-
1.Create Dataset
2.Classify using KNN
3.Classify using MNB
4.Exit

Select Otion:-1.Create Dataset
Do you want to create dataset using your email(y/n)?
If yes enter your login credentials(First classify your emails with different labels to provide a training data )
If no,provide a dataset(Dataset should contain different folders with corresonding emails.For e.g. (Folder name:-Jobs,all job emails in txt file)

Step 2:
Once login is successful,
Enter folder name for dataset(e.g.Folder:-Training will be created in your directory)

Step 3(Training Data)
Enter folder name you want in your dataset:-(Select folders from Email (Select the classified folders))
Mails will be fetched from the folder name provided in above line
Two csv files with features will be created

Step 4:Choose any one option as in Step 1
Here select option 2 or option 3 to classify based on the algorithm
After any choice selection,
Enter the name of data set to be used as training set:-(Here enter the folder name you eneterd in Step 2 For e.g. training)

Step 5.(Testing Data)
Do you want to get unread emails from your email id(y/n) :-Select 'y'to fetch the testing data 
Enter login credentials
Enter a folder name to store new emails(e.g.Testing ,all new emails will be fetched)
After fetching all the new emails will be classified into different folders


If your facing authentication error while entering your gmail credentails,then go to-
1.Manage Your Google Account
2.Security
3.Less secure app access(Turn on)






