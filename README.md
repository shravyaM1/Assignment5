Which algorithm you got better accuracy? Can you justify why?

Linear SVM has better Accuracy than the Naive bayes Algorithm,
Accuracy can vary depending on the dataset and its inherent characteristics. Generally, Linear SVM tends to perform well when the data has clear linear separability, whereas Naive Bayes is a probabilistic classifier that can work well with simple datasets and when the independence assumption holds (i.e., features are conditionally independent given the class).
The Glass dataset have certain characteristics that favor one algorithm over the other. The data has a linear separation between classes, Linear SVM performed better. On the other hand, if the features are conditionally independent given the class, Naïve Bayes might work well.
Linear SVM doesn't make strong assumptions about feature independence. But, Naive Bayes assumes that features are conditionally independent given the class, which might not hold true in some real-world datasets.
Lastly,  Linear SVM can model complex decision boundaries when used with different kernels, such as polynomial or radial basis function (RBF) kernels. Naive Bayes assumes linear boundaries between classes.
