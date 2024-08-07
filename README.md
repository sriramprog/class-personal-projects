# Class and Personal Projects Repository
# Sriram Srinivasan

This repository is an online portfolio of projects <br>
done during my academic career. I will also include side personal projects, <br>
whether it is guided or non-guided.

## Graduate Projects
## Data Science Final Project (see [Walkability Score Code](https://github.com/sriramprog/class-personal-projects/blob/main/Data%20Science%20Project%20Finalized%20Code.ipynb) and [Walkability Score PowerPoint](https://github.com/sriramprog/class-personal-projects/blob/main/Data%20Science%20Group%20Presentation.pdf))
![Screenshot 2022-12-13 224925](https://user-images.githubusercontent.com/61813436/207509544-79f455ac-668a-4bd7-be2e-4b0060defab6.png)

- This is a 6 person team project where we analyzed if there is a relationship between housing prices and neighborhood walkability.
- We used a dataset that takes into account rental prices, crime rate, property prices, school scores, etc. from a particular place in Philadelphia, PA.
- Hypothesis: Does having more accessible features such as post office, grocery stores, gym within a reasonable walking radius help increase or decrease housing prices in the neighborhood?
- Performed EDA (checked for missing values, summary statistics, etc.) and employed feature engineering techniques such as one-hot encoding and binning to ensure a consistent statistical analysis tests.
- Used OLS (Ordinary Least Squares) regression to understand statistical significance of various important features, and performed linearity, homoscedasticity, linearity, and multicollinearity tests to verify if linearity assumptions hold.
- Compared multiple regression algorithms (Lasso, Extreme Gradient Boost, Support Vector, and Random Forest) and found that random forest regression works.
- Results: Overall, walk score is the most statistically significant variable, there is a negative correlation between walk score, crime rates and housing prices. For portions of Philadelphia with high walk scores, it was observed that they have high housing prices.
- Hence, our hypothesis is rejected.
- For future recommendations, we would dive deeper into the negative correlation between walk score and other attributes and gather data from various metropolitan areas - since our initial analysis only used the dataset from Philadelphia.

## Undergraduate Projects
## UG Research Project (see [Autoencoder URE Project Code](https://github.com/sriramprog/class-personal-projects/blob/main/Autoencoder_Code_(Sriram's_data).ipynb))
- Brief Summary: This project basically deals with network traffic and how we can use both a Machine Learning algorithm <br>
and an unsupervised artificial neural network, called an autoencoder, to detect and classify benign from <br>
malicious DoH traffic.

![image](https://user-images.githubusercontent.com/61813436/177605589-3493f4f2-54a9-49ed-90db-7b1855cf6039.png) <br>

- Above image shows how an autoencoder works, it takes input (of any kind, doesn't have to be an image), and input passes through
several hidden layers, just like how a neuron fires up a ton of connections inside a human brain. Also, the output will try to recreate the input. <br>
- The encoder removes noise from the large amounts of data and just focuses on the compressed data. The decoder reconstructs the encoded data back to the original data.
- This project has a twist - we're using autoencoder as a _tool_ to encode, but instead of the output recreating the input, we use it to <br>
separate it into layers - namely Dense, Batch Normalization, and LeakyReLu. That is then passed through the hidden layers and is then used to
create a 2D and 3D visualization plots of the embeddings.

- Background: Domain Name System (DNS) is unencrypted, which shows the entire Internet browsing history for Internet Service Providers (ISP).
To resolve that issue, DNS over HTTPS (DoH) was developed, which is just an enhanced version of DNS. This also isn't helpful as botnets can exploit
to talk with Communication & Control center. We want to detect botnet activity that uses DoH that protects users' privacy.

- Solution: The K-means clustering algorithm is implemented to find clusters of benign & malicious traffic in 3D space. The classification percentages of
91.38% precision, 89.31% accuracy, 87.10% recall, and 89.19% f-score.

