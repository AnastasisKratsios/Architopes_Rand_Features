# Architopes_Rand_Features
Deep Random Feature Architopes

This code create a partition of the input space by:
1. Generating a large number of homeomorphic feed-forward networks,
2. Determine which top N feature maps improve performance most,
3. Train a classifier $s:\mathbb{R}^d \rightarrow \{1,\dots,N\}$ to predict which random feature map works best,
4. Define $K_n\triangleq s^{-1}(n)\cap [-M,M]^d$, for some large $M>0$.  

