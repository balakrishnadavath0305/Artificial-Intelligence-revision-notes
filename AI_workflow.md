# **AI workflow:**

***1)Data Collection***

***2)Data preparation***

***3)Model selection and training***

***4)Model evaluation***

***5)Deploy model***

***6)Monitor and improve***



***In Data collection***, the collected data can be of three types:

***1)Structured data:*** with rows and columns

***2)Unstructured data:*** Messy data like videos and emails

***3)Semi-structured data:*** Json data



***Which model to select***

***1)ML model:*** Stuructured data(labeled or unlabeled); Cleaning, encoding, scaling

***2)DL model:*** Unstructed + Large scale data(can be labeled or unlabeled); Resizing, Tokenizing

***3)Data science:*** May include labeled/unlabeled, Structured/Unstructured; Data wrangling, reshaping

***4)Gen AI model:*** Unstructured,Internet-scale; Cleaning, Chunking, Tokenizing



***In Data preparation,***

 ***Cleaning:*** Changing error in values like ages

&nbsp;***Transformation:*** Making into a single format

&nbsp;***Normalization/Scaling:*** Making into similar range of values(0-1)

&nbsp;***Encoding:*** Replacing letters like S,M,L with values instead

&nbsp;***Text preprocessing:*** removing stop words

&nbsp;***Image/Audio Resize/Compression:*** fixed values of size 



***Select the Model and Train it***

***1)Classification:*** spam detection

***2)regression:*** House price prediction

***3)Clustering:*** Customer Segmentation

***4)Generation:*** Image/text creation



***Evaluate the Model***

First step is to split the data into Training and Testing

After training we compare predicted values to the truth values



***Deploying the model:*** Integrating the model for real world predictions or tasks

Steps:

1)Hosting in the cloud

2)exposed via API or embedded in an app

3)Received live data and returns predictions



***Monitor and improve:*** Model may not work better overtime since new data comes and opinions and interest changes so the model is trained again with new data

