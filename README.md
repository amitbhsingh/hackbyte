# hackbyte _Preparation_

# Electron modern desktop application
# This repo has all the files that were created used during the hackbyte event organized by the loblaws and microsoft
Resources: 
> ## [Provided by Microsoft & Loblaws](https://github.com/amitbhsingh/hackbyte/tree/master/HBinstructions)
> ## 
## Meet our team on Linkedin.
* [Sundeep Pothula - Image labeling and modeling with azure](https://www.linkedin.com/in/sundeeppothula/)
* [Mubtaseem Zaman - Core backend and deploying](https://www.linkedin.com/in/mubtaseemz/?originalSubdomain=ca)
* [Amit Singh - Image labeling and modeling with azure](https://www.linkedin.com/in/mubtaseemz/?originalSubdomain=ca)
* [Novina Wong - Front End | UI/UX](https://www.linkedin.com/in/novinawong/)
* [Weqi Liu - Front End](https://www.linkedin.com/in/sundeeppothula/)
## _Phase 1_ : Business problem framing
* Brainstorming for ideation
* Communicating with clients to list the key challenges
* Listing the plans by team
* Sorting the best plan with collective team feedback
* Business Problem framed: Solving the buffer between warehouse and self life of the product
## _Phase 2_ : Planning the layout / wireframe of the idea 
* [Built a front end web app and hosted on github pages](https://novinaw.github.io/user-list.html)
 
## _Phase 3_ : Data Preparation
* Preparing synthetic dataset and manually labelling them with microsoft azure custom vision api 
## _Phase 4_ : Modeling
* Created 5 version of model with the synthetically created and manually labelled data using azure custom vision api
* Highest accuracy we acheived was 92.9 percent 
## _Phase 5_ : Deploying
* Deploying model was most challenging
* Succesfully deployed the model on microsoft custom vision api and kept building the dataset by taking photos and manually labelling all the products to be able to train the model
* After 7 Iterations this is the score we got
> chocomini	96.8%	81.1%	84.4%	100
> vegetablebabyfood	94.7%	72.0%	86.9%	110
> apple	94.6%	62.5%	82.0%	153

### DAT263X file includes lab from the course Introduction to AI on EDX.
### Microsoft azure machine learning studio 
* Upload dataset set visualize the dataset
* Tune hyperparameter and see the performance of model
* Upload the model
* Publishing a predictive web service
* Consuming a predictive web serive
## Introduction to text analytics
## Term Frequancy Inverse document ferquency
## Stemming : from nltk.stem.porter import PorterStemmer
## Sentiment analysis 

# Introduction to NATURAL LANGUAGE PROCESSING
* text analytics API
* (for English)Speech to text and text to speech just search for speech in  azure services
* (For Translation) Search Translate text 
## LUIS (Language understanding intelligent servies) 
> * LUIS PORTAL : Create new app, intent: light on> switch the light on
> Create new entity: light
> Create new intent: Light off
> switch the light off
> publish to production, The key string use the key. 
> Assign a key to your app
# How to consume the app:
> 
