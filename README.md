Machine-Learning-Natural-Language-Processing-and-Deep-Learning-in-Clinical-Trials

# NLP to summarize the protocol document and ML to predict the trial’s completion

Abstarct:

Clinical trials are one of the most discussed topics in the global pandemic crisis as they are the first step towards finding new approaches to diagnosing and treating diseases. However, a single clinical study often takes six to seven years to complete and costs millions. Therefore, it is essential to simplify this lengthy procedure and make it more efficient. This paper proposes a model to predict a clinical trial’s likelihood of being ’Completed’ or ’Not Completed’ based on its study protocol document. A study protocol document is a complete description of the research before the trial begins. The dataset considered is available on clinicaltrials.gov, a clinical trial registry managed by the United States National Library. First, the critical information from the protocol document is extracted and later summarized using a longformer. After that, Doc2Vec is used to transform the summary and remaining metadata into a feature vector. Machine learning predicts a clinical trial’s completion status using the feature vector in the second part. In this paper, four different machine learning classification models Logistic Regression, Decision Tree Classifier, Support Vector Classifier and Random Forest Classifier are tried for comparison. The Random Forest Classifier showed the highest accuracy among these four models, at 64.38 percent.
