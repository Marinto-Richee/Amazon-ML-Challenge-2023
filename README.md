# Product Length Prediction

In this hackathon, the goal is to develop a machine learning model that can predict the length dimension of a product. The length of a product is an essential attribute that customers use to assess the product size before purchasing, and it is also crucial for packaging and storing products efficiently in the warehouse.

## Dataset

The dataset provided consists of two files, `train.csv` and `test.csv`, containing 2.2 million and 734,736 product records, respectively. The data contains the following columns:

- `PRODUCT_ID`: Represents a unique identification of a product
- `TITLE`: Represents the title of the product
- `DESCRIPTION`: Represents the description of the product
- `BULLET_POINTS`: Represents the bullet points about the product
- `PRODUCT_TYPE_ID`: Represents the product type
- `PRODUCT_LENGTH`: Represents the length of the product

## Task

Participants are required to build a machine learning model that can predict the length of a product from the given metadata. The evaluation metric used for this hackathon is the mean absolute percentage error (MAPE), and the score is calculated using the following formula:

```score = max(0, 100*(1 - metrics.mean_absolute_percentage_error(actual, predicted)))
```

## Submission

The submission file must be in CSV format, containing the `PRODUCT_ID` and `PRODUCT_LENGTH` columns only. The file size should be 734,736 x 2.

## Getting Started

To participate in this hackathon, you will need to follow these steps:

1. Download the dataset from the provided link.
2. Train your machine learning model using the `train.csv` file.
3. Predict the length of the products in the `test.csv` file using your trained model.
4. Create a submission file in CSV format containing the `PRODUCT_ID` and `PRODUCT_LENGTH` columns only.
5. Submit your solution on the provided platform.

## Evaluation

The submissions will be evaluated based on the score calculated using the mean absolute percentage error (MAPE) metric. The score can be between 0 and 100, and a higher score indicates better performance. The top submissions will be announced as winners of the hackathon.

## Conclusion

This hackathon is an exciting opportunity to showcase your machine learning skills and compete with other participants to build the best product length prediction model. Good luck and happy coding!
