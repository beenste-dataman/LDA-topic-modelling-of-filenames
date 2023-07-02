# LDA-topic-modelling-of-filenames
This script uses LDA to discern main topics from filenames in a directory. It provides an overview of large file sets via a CSV file and an HTML visualization, making it easier to grasp file content based on names


This script is designed to perform a Latent Dirichlet Allocation (LDA) analysis on a set of text documents stored as files in a directory. 


Specifically, it tokenizes and cleans the filenames by removing stop words, punctuation, special characters, file extensions, underscores, and dashes. The script then uses these cleaned filenames to identify the main topics among the files. It leverages the gensim library to create a dictionary and a document-term matrix, and then to train the LDA model. The output includes an interactive visualization (in HTML format) of the topics using pyLDAvis, and a CSV file listing each file's path, name, dominant topic, and associated keywords. This script is especially useful for understanding the distribution of topics across a large number of files based on their filenames.
