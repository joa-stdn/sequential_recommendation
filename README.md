# Sequential Recommendation for e-Commerce Platforms
## Ecole Polytechnique Research Project (Winter 2021)

This project is the result of the collaboration between Léo, Côme, Moustapha, Samuel and Joachim for one of our Ecole Polytechnique Research Projects (Winter 2021).

### Description
With the growth of information technologies, recommendation is occupying an increasingly important place in our lives. Thanks to it, users can grasp a large database more quickly and with greater accuracy. Indeed, recommendation involves predicting the articles that will be most suitable for a given user. This prediction is based on a large database that records interactions between users and articles. In this project, we focus on studying and experimenting with several recommendation methods.

After a fairly comprehensive state-of-the-art review, we identify two different problems, both of significant practical interest: firstly, suggesting new products that may potentially appeal to a given user, and secondly, predicting the next items purchased by a customer, based solely on their recent purchases.

For the first problem, we utilize the *Surprise* library in Python, which also provides evaluation methods. For the second problem, which we dedicate more time to, we first need to build our own evaluation metrics, then implement our models, and finally compare them. We develop a wide range of different models: on one side, deep learning-based models (RNN and CNN), and on the other, Markov models.

### Main references
[1] Francesco Ricci, Lior Rokach, Bracha Shapira, Paul B. Kantor, *Recommender Systems Handbook*

[2] Xiangnan He, Lizi Liao, Hanwang Zhang, Liqiang Nie, Xia Hu, Tat-Seng Chua, *Neural collaborative filtering*

[3] Noveen Sachdeva, Giuseppe Manco, Ettore Ritacco, Vikram Pudi, *Sequential Variational Autoencoders for Collaborative Filtering*

[4] Elham S.Khorasani, Zhao Zhenge, John Champaign, *A Markov Chain Collaborative Filtering Model for Course Enrollment Recommendations*