The project is called Medical Pattern prediction. It is a Machine Learning project. This project is created using ASP.NET, C#, SQL. In this system we collect real time health posts from reputed websites, where patients express their views, including their experiences and side-effects on drugs used by them.

We propose to perform Summarization of user posts per drug, and come out with useful conclusions for medical fraternity as well as patient community at a glance.  Proposed system makes use of “Association Learning” for pattern discovery.

In the Literature survey we had chosen some IEEE papers. 

In proposed system and methodologies we performed:

Summarization - patients opinions are analyzed and a symptoms, diseases and drugs are identified using NLP.
Pattern prediction - where system predicts the relationship b/w symptoms-diseases-drugs.
Sentimental Analysis - where system classify patient opinion as either to positive or negative.

Coming to the working of the project:
Patients opinions are inputted to the proposed system and opinions are in the paragraph formats, opinions will have words related to disease symptoms, disease types and treatment details and also will have positive or negative words related to the drug taken. Opinions will have words related to disease symptoms, disease types and treatment details.
Proposed system accepts these opinions and processes using data science algorithms and initially will identify the symptoms, disease types and treatment details using NLP technique (lesk based algorithm), then the output of NLP is inputted to “Eclat algorithm” which is an unsupervised leaning algorithm and processes these medical words and finds the correlation between symptoms , disease types and treatment details.
Classifies the patient opinion either to positive or negative.

In the project we use “eclat algorithm” to find the relationship between medical objects such as symptoms-diseases-drugs. Eclat algorithm is one of the efficient algorithm and takes less time for data processing. This algorithm works fine for small data-sets as well as large data-sets.

Input - Patient Opinions [drug, disease, symptoms related information]
Output - Summarization, Discovering patterns and Sentiment analysis

Coming to the advantages:

This work will help patients to find out association among different drugs, diseases and symptoms.
It will help doctors to find out side-effects of different drugs so they can prescribe better drugs to other patients with similar disease.
Pharmaceutical companies will be also benefited as we are classifying users of particular drug into different classes like depressed and satisfied.
This will be indirect input to companies to decide which drug is popular, whether to produce alternative drug to this etc.
