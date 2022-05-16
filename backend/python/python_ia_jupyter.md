# Python AI developers test

dezzai python tech test for new hirings.

## The Problem

We have a big csv to process located on this S3 bucket:

```
URL:
https://mmg-hiring-tests.s3-eu-west-1.amazonaws.com/python/mmg_data.csv
URI:
s3://mmg-hiring-tests/python/mmg_data.csv.
```

1. Our client wants a jupyter notebook that will load the csv from this location and calculate the number of lines and the average of the field 'tip_amount'. The customer wants the most efficient solution possible.

2. Using this csv build a machine learning model that allows to make predictions about the total_amount field, and wrap it with an endpoint. The endpoint must receive the necessary values on which the model will work to make the prediction, must return this prediction and, in background, store it in a MongoDB.

   - Feel free to use a known pretrained model.
   - Accuracy does not mind, is just to know that you are familiar with the technology.

## Rules

- Make all the decisions you want.
- Share the solution as a link to a repo
- Ask anything you want to us, you have tech team emails
