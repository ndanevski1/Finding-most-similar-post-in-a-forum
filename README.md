# Finding-most-similar-post-in-a-forum
In this mini-project I scrape the official Atom editor forum and apply Natural Language Processing techniques to find the most similar post in the forum to each one.

# Description

I used Python for this project.

Firstly, I use BeautifulSoup to scrape the forum for 250 data points (posts) and save them in a CSV file with information about a post's title, discussion and tag.

After that, I apply two different NLP techniques, TF-IDF and BERT to get the most similar post in the forum to the one looking at now. Due to the different implementation of the NLP techniques, I get different results on some of the posts. This is expected because TF-IDF is a bagging model, unlike BERT, that has syntactic abilities.