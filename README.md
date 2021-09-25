# Identification-of-online-fake-content

This is a repository to create a Website to identify fake online content from new articles, forums etc.

# Tech Stack 
Frontend Stack:</br>
•	HTML / CSS / JavaScript </br>
•	Front End Framework: React.js (JavaScript) </br>

Backend Stack:</br>
•	Operating system -  Windows </br>
•	Programming language -   Python </br>
•	Web development frameworks - Flask (Python) </br> 

# Resources Used
1.Pycharm for frontend stack.</br>
2.Google colab for backend.</br>
3.Tensorflow for ML model.</br>

# API Used 
Yes

# Outcome and How it syncs with our problem Statement
Build a solution that can identify fake content published online in blogs, forums, news articles etc. and shared on social media platforms, along with details of users who post such content.</br>
Problem statement given was to identify fake news shared on blogs, forums etc. based on that
Our program is built to predict if the content in the given URL is fake or genuine. The content on the given URL is tokenized and compared with relevent sources to predict fake news by the help of machine learning model.

# Approach (4 liners)

Step 1: Get Url and Generate tokens for the given content ,get relevent sources and tokenize the content</br>
Step 2: Run those tokens through a model for credibility prediction</br>
Step 3: Return the prediction along with the relevent source</br>
Step 4: If its fake trace back their content and obtain details of the user who post that content

# Developement Pipeline
<h4>Proposed Development Plan in pointers</br></h4>
1.Users input a claim like "Forest fire in Malibu. Ten tourists dead."</br>
2.Our program will get tokens related to the claim from relevent articles.</br>
3.The relevent articles are obtained from Event registry database / through Google API</br>
4.We then pass the tokens to our machine learning model for creadibility prediction.If lots of sources agree, then it is true</br>
5.We show the results as true/ false , and show sources that are relevent.</br>

<h4>Documents To be prepared for installation and evaluation</br></h4>

<h4>Repository Link</br></h4>
https://github.com/Paulinehan13/Identification-of-online-fake-content

<h4>Specify the Third Party used</br></h4>
Event registry API / Google API</br>

<h4>Proposed UI and functional flow in pointers</br></h4>
1. Get URL
2. 

