This project on Amazon reviews sentiment analysis utilizes two distinct methods for evaluating sentiment: VADER (Valence Aware Dictionary and Sentiment Reasoner) and the RoBERTa pretrained model.
VADER is a rule-based sentiment analysis tool that assigns sentiment scores to texts based on a predefined lexicon. 
RoBERTa, on the other hand, represents a more advanced approach to sentiment analysis. It is a transformer-based deep learning model pretrained on large corpora of text data, enabling it to capture complex linguistic patterns and context dependencies.
VADER can quickly assess the overall sentiment of a review, providing immediate insights into whether customers perceive the product positively, negatively, or neutrally.
But RoBERTa enhances this analysis by delving deeper into the text, considering factors like sarcasm, negations, and varying intensities of sentiment expressed.
By the end of this project i also compared these two methods using pairplot provided by Seaborn.
Atlast i also used the Hugging Face Transformer Pipeline which is very useful in performing complex NLP tasks with minimal code and configuration.
