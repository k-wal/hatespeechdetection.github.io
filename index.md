## Structure Based Hate Speech Detection

### Hate Speech
Hate speech is a kind of writing that disparages and is likely to cause harm or danger to the victim. It is a kind of speech that demonstrates a clear intention to be hurtful, to incite harm, or to promote hatred.

#### Why automated hate speech detection?
While manual checking for such comments exists on social media, manual checking can never match to the speed of generation of comments on these sites and hence an automated solution is required.

## Dataset
Used a data-set with a corpus of tweets predominantly having offensive language. It consists of a total of 24783 tweets. The data-set is skewed as there are relatively lesser number of data points under the hate-speech category.

## Our Approach
We use more than the traditional Machine Learning and Deep Learning techniques that use bag of words featurizer. We use models that utilize the grammatical structure of a sentence. 

### Dataset Preprocessing 
Convert tweet to lower case, remove 'RT' from retweets, remove special characters and URLs.

### Models

#### Baseline Models
- SVM
- Logistic Regression

#### LSTM Models
- LSTM Model
- Tree LSTM
