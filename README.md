# IBM-Watson-Retrieve-And-Rank

This repo will help almost everyone that needs help with the Retrieve and Rank service for IBM Watson on Bluemix. This specific example will help you with the GMail FAQ. You enter a query, and it will tell you the FAQ page's title that you need to go to.

Contains:

1. Sample Solr config

2. Example documents as the Data Source

3. Example Questions and Answers to train the "Rank" part of the service.


NOTE: When querying the service, get the "id,body" under the "fl" parameter. If you use "id,title", it won't work, as I have programmed this to put the article titles under "body", not "title".
