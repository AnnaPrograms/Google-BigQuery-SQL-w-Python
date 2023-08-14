## SQL with Python
This is a refresher reference of what I learned working with SQL and python <br> <br>
A popular database that we'll be using is **Google BigQuery**, this is for personal use. We will be using the popular datasets that Google Cloud has to offer, keep in mind, the possibilities with GBQ are endless. This is just a simple example for indiviual use.<br> 

### How to use Google BigQuery API 
<ul>
    <li>Go to console.google.cloud.com</li><br>
    <li>Create a project, and make sure Google BigQuery API is enabled</li>
    <strong>keep in mind you can use Google BigQuery API free, you should not have to adjust or link your billing account if you intend to use it for indiviual small use, like in this case.</strong><br><br>
    <li>Create a Google Cloud Service Account</li>
    <strong>I highly recommend you to view this video on how to make a service account</strong> <a href = "https://youtu.be/lLPdRRy7dfE?list=PL3JVwFmb_BnRKqcbtl2hHL5GIQOHX-sC5" >Getting Started With Google BigQuery API In Python
</a> <br><br>
    <li>Install Google BigQuery</li>
    <strong>Steps for this process are in this video, </strong>
<a href = "https://www.youtube.com/watch?v=gb0bytUGDnQ&t=0s">How to create a Google Cloud Service Account and download client json file
</a>

</ul>

<h5>If you are using Jupyter Notebooks make sure to add (!) symbol before pip installations as that tells the computer to run it in the shell terminal</h5>

<h5>To view all of the public datasets in bigquery, go to your project dashbord and click run a query, then run a sample query and click "open this query", you are now in the google bigquery public datasets and you can view all of the datasets. To use one just call it like this </h5>

### Note: Common error No Module 'db_dtypes' found
You may get this error saying db_dtypes not found when you try to use the method `to_dataframe()`
to fix this just use `!pip install db_dtypes` and if that still does not work then save your notebook and restart the program and it should fix it
