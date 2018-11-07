# M3: Individual Assignment

Halloween is over, sure but why not keep a bit of the creepy mood up.

![alt](https://mfaconfessions.files.wordpress.com/2014/01/american-horror-story-coven1.jpg)

You are provided with a training and testset containing short phrases out of horror stories by Edgar Allan Poe (EAP), Mary Shelley (MWS), and HP Lovecraft (HPL)

Your task: Construct a neural! architecture to develop min. 2 classifiers.

Your decide how lean or complex you want to have it. Also preprocessing is up to you (e.g. identify bi-trigrams first etc.)

Options are (and there are many many more):

- Simple TF-IDF + MLP/ANN
- Some easy sentence representation (e.g. using Spacy) + MLP/ANN
- Public domain embedding vector (e.g. GloVe) + Convolution and/or some RNN architecture
- Self trained embeddings + Convolution + RNN + Attention (if you want to go crazy)


Remember, more complex != better

You can evaluate on a slice of training data first

As part of the submission, please also submit a csv with your prediction in the format shown in ```example_submission_from_test.csv```
