# _Hackbyte Preparation_

# This repo has all the files that were created used during the hackbyte event organized by the loblaws and microsoft
# **Resources** 
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
* Sorting the best plan with collective team feedback
* [Problem's documentation on google drive colloboratively by team](https://docs.google.com/document/d/1oO5qgP7A-9FBh9zGr0-IfWLH5IveH4zZ1WJUxow8O0M/edit) 


#  Business Problem framed: Solving the buffer between warehouse, shelf life of the product and reducing the friction
## _Phase 2_ : Planning the layout / wireframe of the idea 
* We strategised about the steps we should take to distribute responsibilities and work on them.
* [Built a front end web app and hosted on github pages](https://novinaw.github.io/user-list.html)
 
## _Phase 3_ : Data Preparation
* Preparing synthetic dataset and manually labelling them with microsoft azure custom vision api 
* [Click here to get access to images we took to create dataset to train model,event and team photos](https://drive.google.com/drive/folders/1m75WL8UZR0es2vJ1p69KnRd45iM6l1m9?usp=sharing)
## _Phase 5_ :We visited Loblaw's store at queen's and portland for validating the idea and user testing. 
## _Phase 4_ : Modeling
* Created 5 version of model with the synthetically created and manually labelled data using azure custom vision api
* Highest accuracy we acheived was 92.9 percent 
## _Phase 5_ : Deploying
* Deploying model was most challenging
* Succesfully deployed the model on microsoft custom vision api and kept building the dataset by taking photos and manually labelling all the products to be able to train the model
* After 7 Iterations this is the score that the model was able to make and we used for deploying
## Amazing results with help of microsoft custom vision api
<table>
<thead>
<tr>
<th>Tag</th>
<th>Precision</th>
<th>Recall</th>
<th>A.P</th> 
<th>Image Count</th>
</tr>
</thead>
<tbody>
<tr>
<td>Chocomini</td>
<td>96.8</td>
<td>81.1</td>
<td>84.4</td>
<td>100</td>
</tr>
<tr>
<td>Vegetable baby food</td>
<td>94.7</td>
<td>72.0</td>
<td>86.9</td>
<td>110</td>
</tr>
<tr>
<td>Apple Baby food</td>
<td>94.6</td>
<td>62.5</td>
<td>82.0</td>
<td>153</td>
</tr>
<tr>
</tbody>
</table>


## The model performed well, prototype demo while stage presentationduring hackathon was susccessful and our team got KUDOS three times for the strategy that we adopt. 





# Electron modern desktop application
