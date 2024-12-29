
This notebook demonstrates how to increase the performance of a machine learning model using two transformation techniques: **Yeo-Johnson** and **Box-Cox**. These techniques help in stabilizing variance and making the data more normally distributed, which can improve the performance of many machine learning algorithms.

## Transformation Techniques

### 1. Yeo-Johnson Transformation
The Yeo-Johnson transformation is a power transformation technique that can be applied to both positive and negative data. It is defined as:

![Alt text](images/yj.png)

### 2. Box-Cox Transformation
The Box-Cox transformation is another power transformation technique but it can only be applied to positive data. It is defined as:

![Alt text](images/boxCox.png)

## Observations

- The **Yeo-Johnson transformation** can handle both positive and negative values, making it more versatile.
- The **Box-Cox transformation** is limited to positive values but can be very effective for certain types of data.
- Both transformations help in making the data more normally distributed, which can improve the performance of machine learning models.

## Conclusion

- **Yeo-Johnson** is generally more versatile as it can handle both positive and negative values.
- **Box-Cox** can be more effective for datasets that contain only positive values.
