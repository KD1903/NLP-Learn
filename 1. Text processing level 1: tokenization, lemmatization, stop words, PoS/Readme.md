# Tokenization
- Split text into tokens. 
- where tokens can be senrtances or words.

# Stemming vs Lemmatization

| Stemming | Lemmatization |
| --- | --- |
| get the base word for each word present in given text | get the base word from large collection of words representation |
| compare all words present in given text and take base common availabe word only from the available text | takes original meaningful word from large collection (using `nltk`) |
| some words might not be meaningful | all words will be meaningful and in original form |
| faster processing - because just takes base(commmon) word from available context | slower processing - because for each word compare and finds original base from from collection |
| used in classifier, sentiment analysis, etc | used in chatbots kind of apps where each word should be meaningful |
| e.g. history, historical -> histori | e.g. history, historical -> history |

# Removing Stop Words
- remove such words from text which does not adds any value in decision making
- words can be like a, as, the, an, etc. (using `nltk`)
- This should be done only after carefully analyzing your data as per your use case and task, such that removing stop words does not affect on making the decision.

