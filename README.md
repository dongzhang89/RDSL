# CODE-AND-DATA-OF-RDSL
The main code and experimental data for RDSL MATLAB implementat of

Dong Zhang , Yunlian Sun, Qiaolin Ye, Jinhui Tang. Recursive Discriminative Subspace Learning with L1-norm Distance Constraint [J] IEEE Transactions on Cybernetics, 2019.

ABSTRACT: In feature learning tasks, one of the most enormous challenges is to generate an efficient discriminative subspace. In this paper, we propose a novel subspace learning method, named recursive discriminative subspace learning with an ℓ1-norm distance constraint (RDSL). RDSL can robustly extract features from the contaminated images and learn a discriminative subspace. With the use of an inequation-based ℓ₁-norm distance metric constraint, the minimized ℓ₁-norm distance metric objective function with slack variables induces samples in the same class to cluster as close as possible, meanwhile samples from different classes can be separated from each other as far as possible. By utilizing ℓ₁-norm items in both the objective function and the constraint, RDSL can well handle the noisy data and outliers. In addition, the large margin formulation makes the proposed method insensitive to initializations. We describe two approaches to solve RDSL with a recursive strategy. Experimental results on six benchmark datasets, including the original data and the contaminated data, demonstrate that RDSL outperforms the state-of-the-art methods.

The used datasets:
https://github.com/ZHANGDONG-NJUST/Cars-and-CUB-VGG16-features
