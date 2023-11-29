# grocery-gems

## Can we cluster products of the same type? 

Let's dive into the OpenFoodFacts data and explore its intricacies. The app's reliance on user input often results in inaccuracies, whether intentional or due to human error. This leads to a plethora of mistakes within the database, ranging from simple typos to more egregious errors, such as negative values for nutritional information.

These inaccuracies pose a significant challenge for the app, hindering its ability to swiftly provide users with accurate product information, a core objective of the platform. To address this issue, we aim to scrutinize the data and identify potential erroneous entries, not just those with blatant errors but also anomalies within the dataset's natural structure using the Gaussian Mixture Model.

Moreover, leveraging this model could unveil inherent patterns within the data, aiding in the classification of products. Simplifying the user's input process by suggesting categories based on existing entries and verifying them could streamline data accuracy within the app.

Once our analysis using the Gaussian Mixture Model is complete, we'll deliberate on why this approach was chosen and evaluate the outcomes. Subsequently, we'll outline potential directions for the app's future enhancement.

Let's tackle these challenges and explore how we can enhance the OpenFoodFacts app's accuracy and usability for its users.

## Table of contents

1. [Loading packages and data](#load) (complete)
2. [Helper methods](#helper) (complete)
3. [The Gaussian Mixture Model](#gmm) (complete)
4. [Excluding missing values](#missing) (complete)
5. [Feature engineering](#featureE) (complete)
6. [Eliminating obvious error sources](#errors) (complete)
7. [Feature scaling and transformation](#preprocessing) (complete)
8. [Generate test data](#test) (complete)
9. [Training](#training) (complete)
10. [Clustering of product types](#clustering) (complete)
11. [Certainty Analysis](#uncertainty) (complete)
12. [Anomaly detection](#anomalies) (complete)
13. [Conclusion](#conclusion) (complete)
14. [Outlook](#outlook) (complete)
