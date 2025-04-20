Srinivas Therapati
700755602

1. Basic NLP Preprocessing (Tokenization, Stopword Removal, Stemming)
This script demonstrates fundamental NLP preprocessing using NLTK:

Tokenizes the sentence into individual words and punctuation marks.

Removes stopwords like "the", "in", "are" to keep only meaningful tokens.

Applies stemming using the Porter Stemmer to reduce words to their root forms. It prints the original tokens, the tokens without stopwords, and the final list after stemming for the sentence:
"NLP techniques are used in virtual assistants like Alexa and Siri."

2. Named Entity Recognition (NER) with spaCy
This program uses the spaCy library to extract named entities from a sentence:

Loads the small English model en_core_web_sm.

Identifies entities like PERSON, DATE, and ORGANIZATION along with their text span (start & end positions).

Prints each entity's text, label, and character position. Used example:
"Barack Obama served as the 44th President of the United States and won the Nobel Peace Prize in 2009."

3. Scaled Dot-Product Attention (Transformer Mechanism)
This script implements the core attention mechanism used in transformer architectures:

Computes the dot product of the Query (Q) and the transpose of Key (K).

Scales the result by √d to maintain stable gradients.

Applies softmax to get attention weights.

Multiplies the weights by the Value (V) matrix to produce the final attention output. It showcases the mathematical steps behind attention using small numpy arrays for demonstration.

4. Sentiment Analysis using HuggingFace Transformers
This script performs sentiment classification using the HuggingFace transformers library:

Loads a pre-trained pipeline("sentiment-analysis") model.

Analyzes sentiment of the sentence:
"Despite the high price, the performance of the new MacBook is outstanding."

Outputs the sentiment label (POSITIVE/NEGATIVE) and its confidence score. This demonstrates the power of transfer learning using models like BERT and DistilBERT.
