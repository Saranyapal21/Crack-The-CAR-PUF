# CS771-course-project
This project focuses on analyzing and breaking the security of Companion Arbiter Physically Unclonable Functions (CAR-PUF) using machine learning techniques. The main objective was to prove that, contrary to the inventor's belief, a linear machine learning model can accurately predict CAR-PUF responses given sufficient challenge-response pairs. 

The project involved developing a mathematical derivation to transform 32-bit challenges into higher-dimensional feature vectors, implementing this feature mapping function in Python, and utilizing linear classifiers from scikit-learn to train predictive models. Extensive experimentation was conducted with various hyperparameters to optimize model performance. The model was trained on 40,000 challenge-response pairs from a public CAR-PUF and tested on 10,000 unseen pairs, achieving high accuracy and demonstrating the vulnerability of CAR-PUFs to machine learning attacks.
