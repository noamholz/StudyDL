# StudyDL

# TODOs
## DL
important notes and conclusions are listed in the docs:
statergy, pipe-line, [DL_libraries](https://docs.google.com/document/d/1Yz1N2-pMnlBIWhfqrXvtjNOEpICcJ_Z8-tgulvlFoqY/edit?usp=sharing), DL theory.

### Courses
1. [Cs231]()
1. [Ng-deep learning](https://www.coursera.org/specializations/deep-learning)
1. [Ng-CNN Tensorflow](https://www.coursera.org/learn/convolutional-neural-networks-tensorflow)
1. [Fast.ai courses](https://www.fast.ai/)
1. [competitive-data-science](https://www.coursera.org/learn/competitive-data-science)
1. [mlcourse.ai](https://mlcourse.ai/)

### Detection
1. Yolo theory (anchors)
1. Mask-R-CNN evolution theory
1. Winning "magentiq" kaggle solution
### Diagnosis
1. Maximum activation?
1. grad cam?
1. ?
### GANs
1. general theory
1. existing algos review
### Kaggle
1. Review 5 winning solutions. [list1](http://ndres.me/kaggle-past-solutions/), [list2](https://www.kaggle.com/sudalairajkumar/winning-solutions-of-kaggle-competitions), [list3](http://www.chioka.in/kaggle-competition-solutions/). Candidates: [Amazon reiver](https://www.kaggle.com/c/planet-understanding-the-amazon-from-space/data), [humpback whales](https://www.kaggle.com/c/humpback-whale-identification), [histopathologic-cancer-detection](https://www.kaggle.com/c/histopathologic-cancer-detection)

1. Study in-depth 2 winning solutions
### Specific stuff
* Augmentation using Homogeneous coordinates
* Motivation for inception block
* Understand inception v3 trick
* Understand Fully connected conv. Motivations: 1. Flexible input size, 2. Equivalent to sliding cnn.
* What exactly happens when I replace the dense layer of a pretrained model with a smaller one? You freeze the non-dense, and train the dense.
* Why *binary* cross entropy on segmentation model?
* Bayesian optimization
* For ensembles: Ridge/Logreg, LGB, Neural network and my favorite scipy.optimize
## C/C++
1. implement 2 algo puzzles
1. basic code design, and writing nicely
1. memory allocation, call by reference, pointers to arrays, etc.
1. standard libs, polymorphism, inhertance, exceptions.
1. arrays, (stl) vectors, matrices, stacks manipulations.

## Cloud DL


....
https://towardsdatascience.com/how-to-farm-kaggle-in-the-right-way-b27f781b78da:
What roughly speaking should be in your pipeline by the end of this stage:

    Various methods for the preprocessing and creation of numeric features — projection, relationship
    Different methods on how to work with categories — Mean target encoding in the right form, frequency, label / ohe
    Various schemes of embeddings for the text (Glove, Word2Vec, Fasttext)
    Various vectorization schemes of text (Count, TF-IDF, Hash)
    Several validation schemes (N*M for the standard cross-validation, time-based, by group)
    Bayesian optimization / hyperopt / something else for the selection of hyperparameters
    Shuffle / Target permutation / Boruta / RFE for feature selection
    Linear models — write a code to run different models in the same style over one processed data set
    LGB/XGB/Catboost — write a code to run different models in the same style over one processed data set
