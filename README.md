# Article-Classifier

## Project Info

This project features an article classifier that uses the unsupervised learning technique known as a topic modeling. A topic modeler uses matrix factorization (nmf here) to factor the input matrix (terms by documents) into two new matrices: one with dimensions of terms by topics, and another with dimensions of topics by documents. 

## Results

This model is 'trained' on a news article dataset. Since we are using nmf, which extracts the topics and words associated with them from the input data, this model does not perform well on documents that are distant semantically or lexically from news articles. 

For example, an excerpt from The Lord of the Rings will not be classifed properly as the model has no frame of reference for fiction. Similarly, a document on sports that does not feature the same terms associated with sporting topics in this model may be misclassified.

## Usage

To use this model, simply run all code. You will be prompted to upload a document when the program reaches the appropiate execution point. In subsequent runs, you may only run everything after the upload section. Note that this program does re-train the model from scratch when run from the start, but the process is quick and stable.

### Special Thanks

Special thanks to [LazyProgrammer](https://www.deeplearningcourses.com) for starter code for this project.

