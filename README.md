# Using-millions-of-emoji-occurrences-to-learn-any-domain-representations-for-detecting-sentiment-emotion and sarcasm

course AFFECTIVE COMPUTING AND EMOTION ANALYSIS winter semester 2018/19

A quick overview of the ideas behind our new paper ‘Using millions of emoji occurrences to learn any-domain representations 
for detecting sentiment, emotion and sarcasm’ and a code example showing how easy it is to apply our model pretrained on 1.2 billion
tweets to new tasks.
Outline
• Motivation - Why emotion analysis?
• Model understanding
• Related work
• Model architecture and benchmarking (technical details)
• Conclusion
• Future of emotion analysis

Why emotion analysis
• Besides chatting, Emojis in NLP: Siri, Alexa, Google Assistant
• More than positive/negative sentiment analysis, human operate with
more nuanced emotion representation.
• This paper try to learn richer representations of emotion content in
text

Model understanding
• The model overcome shortcoming of limited sentiment analysis
capabilities.
• not enough available dataset
• Using pretrained word vector
• The basic idea is to understand the emotional content of that
sentence through emojis
• This model can be extended to target tasks

Model understanding
• Training the model on millions of tweets containing one of the top 64
emojis and ask the model to predict
• The model does have a understanding of related emojis in the test set
• The model learns to group emojis into overall categories


Related work
• Using emotional expressions as noisy labels in text to counter scarcity
of labels (Read, 2005; Go et al., 2009)
• multitask learning with simultaneous training on multiple Dataset
(Collobert and Weston, 2008)
• learn emoji embeddings from the words describing the emojisemantics in official emoji tables (Eisner et al., 2016).

Applying the model
• The model was called DeepMoji and with a website
https://deepmoji.mit.edu/
• Code is available https://github.com/bfelbo/deepmoji
• Code is documented and there’s examples for how to do most things
