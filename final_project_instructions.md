Natural Language Processing Final Project
------

Due date: 10-17-17 at 5p
Purpose: Build an end-to-end system to model meaning in text.

After doing this assignment you should be able to:

-   Clean raw text data from the web
-   Create and tune a machine learning model
-   Write working and well-organized code
-   Present your results to a technical audience 

First, perform Exploratory Data Analysis (EDA), cleaning, and preprocessing. Second, model your data. Note - These steps are iterative (a little preprocessing, a little modeling, redo the preprocessing, ...).

Ideally this project would be become a part of your public Data Science portfolio.  

----
Part I Preprocessing and EDA 
----

Address each of the following topics:

__Exploratory Data Analysis (EDA)__:

- What specific munging issues do you have to address (e.g., encoding, missing data, or data to exclude)?
- What descriptive/summary statistics are useful for understanding your data?
- What figures provide insight into your data?

__Preprocessing__: 

- How did you tokenize words? Is “didn’t” one token or two? Why did you make that choice?
- Did you normalize your tokens in any way (case, stemming, lemmatization)? If so, how? Why or why not?
- Explore the frequency counts. Are there any terms that should be removed from your feature set? Why or why not?
- Does removing stop-wording or hapaxes help?
- Did you segment sentences? If so, why and how?

__Vectorizing__:

- How did vectorization effect the modeling step?
- Did tf-idf have an effect? Why or why not?

----
Part II Modeling 
----

Pick at least 1 type of modeling:

__Classification / Sentiment Analysis__:

- How noisey were the labels? How did you handle mislabeled or unlabeled data?
- How did you handle class imbalance?
- How did Naive Bayes, Logistic Regression, and SVM compare?
- What were the most common misclassifications? What are possible reasons?

__Clustering / Topic Modeling__:

- How "clean" were the clusters?
- How did changing the number of clusters effect your results?
- What insights did clustering give you into the data?

__Word embeddings (e.g., word2vec)__:

- Does word embeddings yield meaningful results?
- Could you make corpus specific analogies?
- Are there any meaningful clusters?

__Chatbot__:

- Generate language patterns from the corporus?
- Did you apply: Rule-based, probability, chained, or Deep Learning?

Extra Credit
---
Explore advanced options of your choosing. Suggestions:  

- Did you search the hyperparameters of your models (i.e., optimization)?  
- Did ensembling improve your model's performance?
- Can you explore your data or models through advanced visualizations (e.g., t-sne or network analysis)?
- Can you fit your model to elements within the entire corpus? Can you assign sentiment to individual topics within the review (e.g., “great food, lousy service”)?   
- How would you turn your project in a data product?
- Create automated pipelines to put your project into production.

----

For each of steps, I want both an empirical and a logical justification for the choices you made. That is: show us that the choice you picked is empirically superior to the alternative (better F1 score, etc.) and explain why you think that is.  

The deliverables are an in-class presentation and code. The presentation style, or lack of style, will not be scored. Code style __will be__ scored. 

----
Hints
----

- Make it run, make it right, make it fast. (in that order)
- Go end-to-end as quickly possible. From raw data -> simple model -> evaluation. Then explore options for each stage.
- [Tips if model is not working](https://blog.slavv.com/37-reasons-why-your-neural-network-is-not-working-4020854bd607)
- How do get a "A"? Do something groundbreaking (seriously). Either ground-breaking for the field or for the class.
    + Here is an example. Fit evaluation metrics not covered in class. [Beyond Accuracy, F-score and ROC...](http://transsearch.iro.umontreal.ca/rali/sites/default/files/publis/EvAAAI06finMay10.pdf)