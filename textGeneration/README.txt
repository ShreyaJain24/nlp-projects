Word based Text Generation

Input:
seq len - 16 (padded)

Number of training examples/ Length of corpus - 905
Vocabulary size - 2513

Hyperparameters:
hidden layer - 100
Epochs - 100
optimizer - adam (lr=0.001, beta_1=0.9, beta_2=0.999, epsilon=None, decay=0.0, amsgrad=False) [Default]


Output:
probability of each word from vocab to be the next word (softmax applied )
number of next words as parameter

Basic model




# To-Do
- Word-level RNN (Bidrectional , Attention based)
-  Char-level RNN
- GAN pytorch
- VAE tensorflow



