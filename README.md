# 6 Techniques for Feature Engineering in Your Next ML Project

Feature Engineering in machine learning is creating new features from existing data. Often, with raw data, the information contained within may not be sufficient from a learning perspective. Because of this, you may need to transform this data into new features or columns that help you represent the data in a way that is more useful for learning. The general process of building a model is as follows.

1. Exploratory Data Analysis including Data Cleaning
2. Feature Engineering
3. Feature Selection
4. Model Selection
5. Model Training and Evaluation

Of all these steps, **arguably the most important is the Feature Engineering** step. By defaulting only to the raw data, you risk missing out on providing valuable context as to why a behavior is happening. Whether predicting the behavior of a user, or a machine, Feature Engineering is crucial to the success of your project. A few examples of what might need to be done:

1. Scaling numeric data and encoding categorical data
2. Converting long-form text into a numerical values
3. Calculate the difference between dates or times
4. Aggregate data into a single row, such as summing, counting, or calculating averages
5. Creating aggregate date windows
6. Merge data from different sources into a single set of observations

I liked the definition provided on [Wikipedia](https://en.wikipedia.org/wiki/Feature_engineering). It sums up the idea of using domain knowledge to extract new features:

>Feature engineering or feature extraction is the process of using domain knowledge to extract features (characteristics, properties, attributes) from raw data. The motivation is to use these extra features to improve the quality of results from a machine learning process, compared with supplying only the raw data to the machine learning process.

We can start with just that; domain knowledge.
 
Read more here: https://www.dataknowsall.com/featureeng.html
