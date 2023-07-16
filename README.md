# Text-Analysis-Using-Regression-Modeling-and-Deep-Sentence-Embeddings

In this project, text data was analyzed using regression model to predict scores associated with the text. The following tasks were performed:

Data Preprocessing:

- The train and test datasets were loaded.
- Lowercase conversion, punctuation removal, and stopword removal were applied to the text data.
- Lemmatization was employed to reduce words to their base form.
- The text data was tokenized using CountVectorizer, resulting in a matrix representation of the text.

Supervised Learning:

- Ridge regression was trained on the tokenized train dataset.
- The model's performance was evaluated by calculating the mean squared error (MSE) and visualizing the prediction errors.
- The impact of adding a sentiment feature to the model was explored, and the performance improvement was assessed.
- An alternative regression model, Support Vector Regression (SVR), was applied, and hyperparameters were tuned using GridSearchCV.
- The MSE values of different models were compared, and the comparison was presented through a bar plot.

Deep Sentence Embeddings:

- The text data was embedded using the Universal Sentence Encoder, transforming the text into dense vectors (embeddings).
- Regression modeling (SVR) was performed on the embedded train dataset, and scores were predicted for the embedded test dataset.
- The performance of the model was evaluated by calculating the mean squared error (MSE) and visualizing the prediction errors.

