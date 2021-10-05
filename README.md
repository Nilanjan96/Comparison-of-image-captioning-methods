# Comparison-of-image-captioning-methods
We compare 2 widely used image captioning methods, with and without attention 

ImageCaptioningBasicBest.ipynb:- This contains the best model we got so far by training
on flickr8k dataset (70% train and 30% test sets). For generation, we have
used greedy search here.


Image_Captioning.ipynb:- This notebook contains implementation of image captioning with visual attention

ImageCaptioningBasicGreedy_Beam.ipynb:- This notebook includes our implementation of beam search and compares the performance of greedy and beam search in generation of sentence.

ImageCaptioning.ipynb:- Here, we have implemented the model and trained
on just 100 images from the flickr30k dataset. This was to test the working
soundness of the architecture
