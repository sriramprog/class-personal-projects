# Class and Personal Projects Repository
# Sriram Srinivasan

This repository is an online portfolio of all class and personal projects <br>
done during my undergraduate career at Wichita State University as a <br>
Computer Science student. All graduate projects done (where acceptable) <br>
according to the institution rules for academic honesty (if permitted) <br>
will be uploaded here throughout my graduate career at Wichita State University.


# Work in progress in updating the README file description ....

## Undergraduate Research Project (put direct link here - see Autoencoder_Code_(Sriram's_data).ipynb file)
Brief Summary: This project basically deals with network traffic and how we can use both a Machine Learning algorithm <br>
and an unsupervised artificial neural network, called an autoencoder, to detect and classify benign from <br>
malicious DoH traffic.

![image](https://user-images.githubusercontent.com/61813436/177605589-3493f4f2-54a9-49ed-90db-7b1855cf6039.png) <br>
Above image shows how an autoencoder works, it takes input (of any kind, doesn't have to be an image), and input passes through <br>
several hidden layers, just like how a neuron fires up a ton of connections inside a human brain. The output will try to recreate the input, and <br>
the encoder removes noise from the large amounts of data and just focuses on the compressed data. <br>
The decoder reconstructs the encoded data back to the original data. <br> 
This project has a twist - we're using autoencoder as a _tool_ to encode, but instead of recreating the input, we use it to   

Background: Domain Name System (DNS) is unencrypted, which shows the entire Internet browsing history for Internet Service Providers (ISP). <br>
To resolve that issue, DNS over HTTPS (DoH) was developed, which is just an enhanced version of DNS. This also isn't helpful as botnets can exploit
to talk with Communication & Control center. We want to detect botnet activity that uses DoH that protects users' privacy.

Solution: In the ipynb notebook, an autoencoder recreates input given by traffic and replicates the input as the output. <br>
The autoencoder is trained to recreate benign and malicious traffic and we obtain 3D visualizations, called embeddings. <br>
Then, I implement a K-means clustering algorithm to find clusters of benign & malicious traffic in 3D space. The classification percentages of <br>
91.38% precision, 89.31% accuracy, 87.10% recall, and 89.19% f-score.

## Data Science Final Project (put direct link here - see .......)
I used the World University Rankings website


## Databases Final Project (put direct link here - see ........)


