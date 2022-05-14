# Part-of-Speech-POS-Tagger-for-NLP-tasks
 Associating each word in a sentence with a proper POS (part of speech) is known as POS tagging or POS annotation.
 
# Techniques for POS tagging
There are various techniques that can be used for POS tagging such as:

->Rule-based POS tagging: The rule-based POS tagging models apply a set of handwritten rules and use contextual information to assign POS tags to words. These rules are often known as context frame rules. 

->Transformation Based Tagging:  The transformation-based approaches use a pre-defined set of handcrafted rules as well as automatically induced rules that are generated during training.

->Deep learning models: Various Deep learning models have been used for POS tagging such as Meta-BiLSTM which have shown an impressive accuracy of around 97 percent.

->Stochastic (Probabilistic) tagging: A stochastic approach includes frequency, probability or statistics. The simplest stochastic approach finds out the most frequently used tag for a specific word in the annotated training data and uses this information to tag that word in the unannotated text. But sometimes this approach comes up with sequences of tags for sentences that are not acceptable according to the grammar rules of a language. One such approach is to calculate the probabilities of various tag sequences that are possible for a sentence and assign the POS tags from the sequence with the highest probability. Hidden Markov Models (HMMs) are probabilistic approaches to assign a POS Tag.

Here, we will look over the steps to build a POS tagger using Viterbi Algorithm & modify it using different techniques to account for unknown words, thereby increasing the accuracy considerably.
