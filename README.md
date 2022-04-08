# CPSC 340: Machine Learning and Data Mining (2021W2)

This is the public-facing portion of the course website; also see [the Canvas course](https://canvas.ubc.ca/courses/83421) for links to the course-specific pages for [Piazza](https://piazza.com/ubc.ca/winterterm22022/cpsc3402012022021w2), Gradescope, lecture recordings, and submitting assignments.

### Course documents

* [syllabus](docs/syllabus.md)
* [homework submission instructions](docs/submissionInstructions.pdf)
* [textbooks and online resources](docs/resources.md)
* [CPSC 340 vs. CPSC 330 vs. CPSC 440](docs/340_330_440.md)

### Schedule

Note: In the timetable below, the textbook codes (such as "AI:AMA") are defined [here](docs/resources.md#textbooks).

| # | Date           | Slides       | Instructor | Related Readings and Links    | Homework and Notes    |
| --|------------ | -------------- | ---- | ----------------------------- | ------------ |
| 1 | Mon Jan 10      | [Motivation and Syllabus](lectures/L1.pdf?raw=1) | Both | [What is Machine Learning?](https://www.youtube.com/watch?v=OokV2AX4TKg) [Machine Learning](https://en.wikipedia.org/wiki/Machine_learning)<br>[Rise of the Machines](http://www.economist.com/news/briefing/21650526-artificial-intelligence-scares-peopleexcessively-so-rise-machines) [Talking Machine Episode 1](https://www.thetalkingmachines.com/episodes/hello-world)       | [a1 posted](https://github.com/UBC-CS/cpsc340-2021w2/raw/main/assignments/a1.zip)   |
| 2 | Wed Jan 12      | [Exploratory Data Analysis](lectures/L2.pdf?raw=1)   | Jeff  | [Companion notebook](notebooks/L02_eda.ipynb), [Gotta Catch'em all](http://datagenetics.com/blog/april32016/index.html) [Why Not to Trust Statistics](https://mathwithbaddrawings.com/2016/07/13/why-not-to-trust-statistics/)<br>[Visualization Types](http://guides.library.duke.edu/datavis/vis_types) [Google Chart Gallery](https://developers.google.com/chart/interactive/docs/gallery?hl=en) [Other Tools](http://selection.datavisualization.ch/)    |     |
| 3 | Fri Jan 14    | [Decision Trees](lectures/L3.pdf?raw=1)    | Jeff   | [A Visual Introduction to Machine Learning](http://www.r2d3.us/visual-intro-to-machine-learning-part-1), [Decision Trees](https://en.wikipedia.org/wiki/Decision_tree_learning) [Entropy](https://en.wikipedia.org/wiki/Entropy_(information_theory))<br>AI:AMA 18.2-3, ESL: 9.2, ML:APP 16.2     | [Big-O Notes](https://www.cs.ubc.ca/~schmidtm/Courses/Notes/bigO.pdf), [Week 1 Tutorials](tutorials/week01)
| 4 | Mon Jan 17  | [Fundamentals of Learning](lectures/L4.pdf?raw=1) | Jeff  |  [Companion notebook](notebooks/L04demo_fundamentals.ipynb), [7 Steps of Machine Learning](https://www.youtube.com/watch?v=nKW8Ndu7Mjw) [IID](https://en.wikipedia.org/wiki/Independent_and_identically_distributed_random_variables) [Cross-validation](https://en.wikipedia.org/wiki/Cross-validation_(statistics)) [Bias-variance](https://en.wikipedia.org/wiki/Bias%E2%80%93variance_tradeoff) [No Free Lunch](http://dml.cs.byu.edu/~cgc/docs/mldm_tools/Reading/LCG.pdf)<br>AI: AMA 18.4-5, ESL 7.1-7.4, 7.10, ML:APP 1.4, 6.5 | [Course Notation Guide](https://www.cs.ubc.ca/~schmidtm/Courses/Notes/notation.pdf)<br>  |
| 5 | Wed Jan 19    | [Probabilistic Classifiers](lectures/L5.pdf?raw=1) | Mi Jung |[Conditional probability](https://en.wikipedia.org/wiki/Conditional_probability) ([demo](http://setosa.io/ev/conditional-probability/)) [Naive Bayes](https://en.wikipedia.org/wiki/Naive_Bayes_classifier) [Probabilities and Battleship](http://datagenetics.com/blog/december32011/index.html)<br>ESL 4.3, ML: APP 2.2, 3.5, 4.1-4.2  | Assignment 1 due<br>[a1 solutions](assignments/a1sol.md)<br>[Probability Notes](https://www.cs.ubc.ca/~schmidtm/Courses/Notes/probability.pdf) [Probability Slides](https://www.cs.ubc.ca/~schmidtm/Courses/Notes/probabilitySlides.pdf) |
| 6 | Fri Jan 21  | [Non-Parametric Models](lectures/L6.pdf?raw=1)   | Mi Jung | [Companion notebook](notebooks/L06demo_dt-knn.ipynb), [K-nearest neighbours](https://en.wikipedia.org/wiki/K-nearest_neighbors_algorithm) [Decision Theory for Darts](http://www.datagenetics.com/blog/january12012/index.html) [Norms](https://en.wikipedia.org/wiki/Norm_(mathematics))<br>AI: AMA 18.8, ESL 13.3, ML:APP 1.4     | [Assignment 2 posted](assignments/a2.zip?raw=1)<br>  [Week 2 Tutorials](tutorials/week02) | 
| 7 | Mon Jan 24  | [Ensemble Methods](lectures/L7.pdf?raw=1) | Jeff | [Companion notebook](notebooks/L07demo_random-forests.ipynb), [Ensemble Methods](https://en.wikipedia.org/wiki/Ensemble_learning) [Random Forests](https://en.wikipedia.org/wiki/Random_forest) [Empirical Study](http://jmlr.org/papers/volume15/delgado14a/delgado14a.pdf) [Kinect](https://www.microsoft.com/en-us/research/wp-content/uploads/2016/02/BodyPartRecognition.pdf)<br>AI: AMA 18.10, ESL: 7.11, 8.2, 15, 16.3, ML: APP 6.2.1, 16.2.5, 16.6  |    |
| 8 | Wed Jan 26    | [Clustering](lectures/L8.pdf?raw=1)    | Jeff | [Companion notebook](notebooks/L08demo_clustering.ipynb), [Clustering](https://en.wikipedia.org/wiki/Cluster_analysis) [K-means clustering](https://en.wikipedia.org/wiki/K-means_clustering) ([demo](https://www.naftaliharris.com/blog/visualizing-k-means-clustering/)) [K-Means++](http://ilpubs.stanford.edu:8090/778/1/2006-13.pdf) ([demo](https://www.youtube.com/watch?v=BIQDlmZDuf8))<br>IDM 8.1-8.2, ESL: 14.3  |     |
| 9 | Fri Jan 28 | [More Clustering](lectures/L9.pdf?raw=1)  |Jeff | [Companion notebook](notebooks/L09demo_dbscan.ipynb), [DBSCAN](https://en.wikipedia.org/wiki/DBSCAN) ([video](https://www.cs.ubc.ca/~schmidtm/Courses/Notes/dbscan.mov), [demo](https://www.naftaliharris.com/blog/visualizing-dbscan-clustering/)) [Hierarchical Clustering](https://en.wikipedia.org/wiki/Hierarchical_clustering) [Phylogenetic Trees](https://en.wikipedia.org/wiki/Phylogenetic_tree)<br>IDM 8.4   |   [Week 3 Tutorials](tutorials/week03) | 
| 10 | Mon Jan 31 <br> | [Outlier Detection](lectures/L10.pdf?raw=1)   |Jeff  | [Empirical Study](https://journals.plos.org/plosone/article?id=10.1371%2Fjournal.pone.0152173)<br>IDM 8.3, ESL 14.3.12, ML:APP 25.5  |    |
| 11 | Wed Feb 2<br> | [Least Squares](lectures/L11.pdf?raw=1)   |Mi Jung | [Companion notebook](notebooks/L11demo_linear-reg.ipynb), [Linear Regression](http://datagenetics.com/blog/august12013/index.html) ([demo](http://setosa.io/ev/ordinary-least-squares-regression/), [2D data](https://www.cs.ubc.ca/~schmidtm/Courses/Notes/linear.mp4), [2D video](https://www.cs.ubc.ca/~schmidtm/Courses/Notes/linear2.mp4)) [Least Squares](https://en.wikipedia.org/wiki/Ordinary_least_squares) [Essence of Calculus](https://www.youtube.com/playlist?list=PLZHQObOWTQDMsr9K-rj53DwVRMYO3t5Yr) [Partial Derivative](https://en.wikipedia.org/wiki/Partial_derivative) [Gradient](https://en.wikipedia.org/wiki/Gradient)<br>ESL 3.1-2, ML:APP 7.1-3, AI:AMA 18.6<br> |  |
| 12 | Fri Feb 4 <br>  | [Nonlinear Regression](lectures/L12.pdf?raw=1) | Jeff| [Why should one learn machine learning from scratch?](https://www.quora.com/Why-should-one-learn-machine-learning-from-scratch-rather-than-just-learning-to-use-the-available-libraries) [Essence of Linear Algebra](https://www.youtube.com/playlist?list=PLZHQObOWTQDPD3MizzM2xVFitgF8hE_ab) [Matrix Differentiation](https://atmos.washington.edu/~dennis/MatrixCalculus.pdf) [Fluid Simulation](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.726.8764&rep=rep1&type=pdf) ([video](https://www.youtube.com/watch?v=kGB7Wd9CudA))<br>ESL 5.1, 6.3 | [Linear Algebra Notes](https://www.cs.ubc.ca/~schmidtm/Documents/2009_Notes_LinearAlgebra.pdf)<br>[Linear/Quadratic Gradients](https://www.cs.ubc.ca/~schmidtm/Courses/Notes/linearQuadraticGradients.pdf), [Week 4 Tutorials](tutorials/week04), Assignment 2 due, [Assignment 3 released](assignments/a3.zip?raw=true) |
| 13 | Mon Feb 7 <br>  | [Gradient Descent](lectures/L13.pdf?raw=1)  | Jeff | [Companion notebook](notebooks/L13_grad-descent.ipynb),  [Gradient Descent](https://en.wikipedia.org/wiki/Gradient_descent) [Convex Functions](https://en.wikipedia.org/wiki/Convex_function)    |  [a2 solutions](assignments/a2sol.md)      |
|  | Wed Feb 9 <br> | **Guest Lecture** on reinforcement learning  | Helen Zhang (12pm). Ben Norman (2pm)  |    | [Helen Zhang slides](https://github.com/UBC-CS/CPSC340-2021W2/blob/main/lectures/L15.5a-HelenZhang-RL_Intro-bonus.pdf), [Ben Norman slides](https://github.com/UBC-CS/CPSC340-2021W2/blob/main/lectures/L15.5a-HelenZhang-RL_Intro-bonus.pdf)
| 14 | Fri Feb 11 <br>  | [Robust Regression](lectures/L14.pdf?raw=1)  | Mi Jung   | [Companion notebook](notebooks/L14_loss-basis.ipynb), ML:APP 7.4    |  [Week 5 Tutorials](tutorials/week05)   |
| 15 | Mon Feb 14 <br>  | [Feature Selection](lectures/L15.pdf?raw=1)  | Mi Jung     | [Genome-Wide Association Studies](https://en.wikipedia.org/wiki/Genome-wide_association_study) [AIC](https://en.wikipedia.org/wiki/Akaike_information_criterion), [BIC](https://en.wikipedia.org/wiki/Bayesian_information_criterion)<br>ESL 3.3 , 7.5-7   |  Assignment 3 due <br>[a 3 solutions](https://canvas.ubc.ca/files/17081484/download?download_frd=1)        |
| 16 | Wed Feb 16 <br> | [Regularization](lectures/L16.pdf?raw=1)   | Mi Jung | [Companion notebook](notebooks/L16demo_regularization.ipynb),  ESL 3.4., ML:APP 7.5, AI:AMA 18.4  |   |
|  | Feb 17 (6 - 7:30 pm) <br> |  | MIDTERM | |
| 17 | Fri Feb 18 <br> | [More Regularization](lectures/L17.pdf?raw=1) | Mi Jung  | [Companion notebook](notebooks/L17_more-reg.ipynb),  [RBF video](https://www.cs.ubc.ca/~schmidtm/Courses/Notes/rbf.mp4) [RBF and Regularization video](https://www.cs.ubc.ca/~schmidtm/Courses/Notes/rbf2.mp4)<br>ESL 6.7, ML:APP 13.3-4     |   |
|  | Feb 21 -- 25 <br> |  | MIDTERM BREAK || [a4 posted](https://github.com/UBC-CS/cpsc340-2021w2/raw/main/assignments/a4.zip) (Feb 25)|
| 18 | Mon Feb 28<br> | [Linear Classifiers](lectures/L18.pdf?raw=1)  | Mi Jung | [Companion notebook](notebooks/L19b_lin-classifiers1.ipynb),  [Perceptron](https://en.wikipedia.org/wiki/Perceptron)<br>ESL 4.5, ML:APP 8.5    |        |
| 19 | Wed Mar 2 <br> | [More Linear Classifiers](lectures/L19.pdf?raw=1)  | Mi Jung  | [Companion notebook](notebooks/L20_lin-classifiers2.ipynb),  [Support Vector Machines](https://en.wikipedia.org/wiki/Support_vector_machine)<br>ESL 4.4, 12.1-2, ML:APP 8.1-3, 9.5 14.5, AI:AMA 18.9  |  [Week 6 Tutorials](tutorials/week06) |
| 20 | Fri Mar 4<br> | [Feature Engineering](lectures/L20.pdf?raw=1)   | Jeff | [Gmail Priority Inbox](http://static.googleusercontent.com/media/research.google.com/en//pubs/archive/36955.pdf)  |  |
| 21 | Mon Mar 7 <br> | [Kernel Trick](lectures/L21.pdf?raw=1) | Mi Jung     | [Companion notebook 1](notebooks/L21_kernels.ipynb), [Companion notebook 2](notebooks/L23demo_kernels.ipynb), [Companion notebook 3](notebooks/L22b_rbf.ipynb) ESL 12.3, ML:APP 14.1-4 |   |
| 22 | Wed Mar 9 <br> | [Stochastic Gradient](lectures/L22.pdf?raw=1)  | Jeff  | [Companion notebook](notebooks/L22_sgd.ipynb), [Stochastic Gradient](https://en.wikipedia.org/wiki/Stochastic_gradient_descent)<br>ML:APP 8.5     |  [Week 7 Tutorials](tutorials/week07) |
| 23 | Fri Mar 11 <br>  | [Boosting, start of MLE](lectures/L23.pdf?raw=1)   | Mi Jung  | [AdaBoost](https://en.wikipedia.org/wiki/AdaBoost) ([video](https://www.cs.ubc.ca/~schmidtm/Courses/Notes/adaBoost.mp4)) [XGBoost](https://xgboost.readthedocs.io/en/latest/tutorials/model.html) ([video](https://www.cs.ubc.ca/~schmidtm/Courses/Notes/regressionBoost.mp4))<br>ML:APP 16.4     |a4 due, [a5 posted](https://github.com/UBC-CS/cpsc340-2021w2/raw/main/assignments/a5_2021w2.zip),  [Max and Argmax Notes](https://www.cs.ubc.ca/~schmidtm/Courses/Notes/max.pdf) |
| 24 | Mon Mar 14 <br>  | [MLE and MAP](lectures/L24.pdf?raw=1) | Mi Jung | [Companion notebook](notebooks/L24_mle.ipynb), [Maximum Likelihood Estimation](https://en.wikipedia.org/wiki/Maximum_likelihood_estimation)<br>ML:APP 9.3-4  | |
| 25 | Wed Mar 16 <br>  | [Principal Component Analysis](lectures/L25.pdf?raw=1) | Mi Jung | [Companion notebook](notebooks/L26a_pca1.ipynb),  [Principal Component Analysis](https://en.wikipedia.org/wiki/Principal_component_analysis)<br>ESL 14.5, IDM B.1, ML:APP 12.2  | 
| 26 | Fri Mar 18 <br>  | [More PCA](lectures/L26.pdf?raw=1)     | Mi Jung | [Companion notebook](notebooks/L28demo_pca2.ipynb),  [Making Sense of PCA](https://stats.stackexchange.com/questions/2691/making-sense-of-principal-component-analysis-eigenvectors-eigenvalues) [SVD](https://en.wikipedia.org/wiki/Singular_value_decomposition) [Eigenfaces](https://en.wikipedia.org/wiki/Eigenface)   |  [Week 8 Tutorials](tutorials/week08)   |
| 27 | Mon Mar 21 <br> | [Sparse Matrix Factorization](lectures/L27.pdf?raw=1)  | Mi Jung | [Companion notebook](notebooks/L29demo_pca-nmf.ipynb),  [Non-Negative Matrix Factorization](https://en.wikipedia.org/wiki/Non-negative_matrix_factorization) ([original](http://www.nature.com/nature/journal/v401/n6755/abs/401788a0.html) - access from UBC)<br>ESL 14.6, ML: APP 13.8  |    |
| 28 | Wed Mar 23 <br> | [Recommender Systems](lectures/L28.pdf?raw=1)    | Mi Jung | [Recommender Systems](https://en.wikipedia.org/wiki/Recommender_system), [Netflix Prize](https://en.wikipedia.org/wiki/Netflix_Prize), [Nonlinear Dimensionality Reduction](https://en.wikipedia.org/wiki/Nonlinear_dimensionality_reduction), [t-SNE demo](http://distill.pub/2016/misread-tsne/), ESL 14.8-9, IDM B.2 |   |
| 29 | Fri Mar 25 <br> | [Deep Learning](lectures/L29.pdf?raw=1)   | Jeff    | [Companion notebook](notebooks/L32a_neural-net1.ipynb), [Google Video](https://www.youtube.com/watch?v=bHvf7Tagt18) [What is a Neural Network?](https://www.youtube.com/watch?v=aircAruvnKk) [Interactive Guide](https://jalammar.github.io/visual-interactive-guide-basics-neural-networks)<br>ML:APP 16.5, ESL 11.1-4, AI: AMA 18.7    |   Assignment 5 due, [a6 posted](https://github.com/UBC-CS/cpsc340-2021w2/raw/main/assignments/a6.zip),  [Week 9 Tutorials](tutorials/week09)    |
| 30 | Mon Mar 28 <br> | [More Deep Learning](lectures/L30.pdf?raw=1)  | Jeff   |  [Fortune Article](http://fortune.com/ai-artificial-intelligence-deep-machine-learning/) [Deep Learning References](https://github.com/ChristosChristofidis/awesome-deep-learning), [Alchemy](https://www.youtube.com/watch?v=Qi1Yry33TQE&feature=youtu.be&t=3m)<br>ML:APP 28.3, ESL 11.5   |       |
| 31 | Wed Mar 30 <br> | [Convolutions](lectures/L31.pdf?raw=1)    | Jeff   |  [Companion notebook](notebooks/L34demo_convolution-cnn.ipynb)   |      |
| 32 | Fri Apr 1 <br> | [Convolutional Neural Networks](lectures/L32.pdf?raw=1)  | Jeff  | [Companion notebook](notebooks/L35demo-cnn-pretrained.ipynb), [Convolutional Neural Networks](https://en.wikipedia.org/wiki/Convolutional_neural_network)<br>ML:APP 28.4, ESL 11.7   | [Week 10 Tutorials](tutorials/week10) |
| 33 | Mon Apr 4<br> | [More CNNs](lectures/L33.pdf?raw=1) | Jeff | |  |
|    | Wed Apr 6<br> | [AI Neuroscience (and bonus material)](lectures/L33.5-Bonus-AI-Neuroscience-compressed.pdf?raw=1)    | Jeff  |    |
| 34 | Fri Apr 8<br> | [Conclusion](lectures/L34.pdf?raw=1) |  both |  | Assignment 6 due      |
