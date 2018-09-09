# Malawi Data Science & Machine Learning Workshop Screening Task

## Data Challenge Task

* to identify a digit/number given optical data from handwritten digits

## Data Challenge Bounty
### Invitation to a Data Science & Machine Learning Workshop 
Where we will cover the basics of Data Science and Machine Learning using practical exercises

## Working on the Data Challenge
1.Fork the code challenge repository provided.

2.Make a topic branch. In your github form, keep the master branch clean. When you create a branch, it essentially will be a copy of the master.

>Pull all changes, make sure your repository is up to date

```sh
$ cd MalawiWorkshopScreening
$ git pull origin master
```

>Create a new branch as follows-> git checkout -b [your_github_username], e.g.

```sh
$ git checkout -b Witty-Kitty master
```

>See all branches created

```sh
$ git branch
* Witty-Kitty
  master
```

>Push the new branch to github

```sh
$ git push origin -u Witty-Kitty
```

3.**Remember to only make changes to the branch!**
The folder named **data** contains 2 csv files: 
* train.csv
* test.csv

The folder named **submission** contains 1 csv file:
* sample_submission.csv

The train dataset contains labelled records, ie. their classes are known.
* use the train dataset to train a satisfactory classification model
* use the model to classify the records in the test dataset
* ensure the format of your submission file is similar to the **sample_submission.csv** file in the **submission** folder
* once satisfied with the model and the predictions, name the file containing labelled test data **predictions.csv** and include it in the **submission** folder  
* Add to the base of the existing README file a brief explanation about your solution outlining the algorithm you chose to use, why you chose it and how the algorithm compared to any others you may have tried to use  

4.Commit the changes to your branch.

5.Make a pull request to the **MalawiWorkshopScreening** Repo.

##### Dataset Details

The Handwritten Digits Dataset details: 
* 5620 instances/records 
	* train - 3823 records
	* test  - 1797 records
* 64 attributes/features
* 10 classes

##### Resources
You can use the following resources to to get acquainted with some classification problems:
* [Naive Bayes Classification](https://github.com/jakevdp/PythonDataScienceHandbook/blob/master/notebooks/05.05-Naive-Bayes.ipynb)
* [Support Vector Machines](https://github.com/jakevdp/PythonDataScienceHandbook/blob/master/notebooks/05.07-Support-Vector-Machines.ipynb)


