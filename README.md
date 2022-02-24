# Understanding the VAE Model

Example codes for my blog post: [Understanding the VAE Model](https://mistylight.github.io/posts/10593/).

NOTE: The visualizations below are generated using the CNN-based model.

## Latent Space

A visualization of the latent space of VAE trained on MNIST, projected to 2-dimension with PCA:

<img src="https://raw.githubusercontent.com/mistylight/picbed/main/Hexo/2022_02_24_CQhubeEzrB3yx9i.png" alt="" style="width: 400px;" />

## Reconstruction

Input image x (left) and its corresponding VAE reconstruction x-hat (right):

<img src="https://raw.githubusercontent.com/mistylight/picbed/main/Hexo/2022_02_24_uWyOZ7R18fl5B6F.png" alt="" style="width: 800px;"/>

## Interpolation

The interpolation between two test images xA, xB. From left to right: xA, xA-hat, the 3 interpolations in between, xB-hat, xB:

<img src="https://raw.githubusercontent.com/mistylight/picbed/main/Hexo/2022_02_24_MCAf5Jl4jw2kaDL.png" alt="" style="width: 400px;" />

## Sample and Generate

Novel hand-written digit images generated by VAE:

<img src="https://raw.githubusercontent.com/mistylight/picbed/main/Hexo/2022_02_24_6aSbuw3ThYD1jB8.png" alt="" style="width: 400px;" />

## License

Distributed under the MIT License. See LICENSE for more information.

## Contact

@mistylight - mistylight.cs@gmail.com

## Acknowledgements

[1] Tutorial on Variational Autoencoders. Doersch et al., 2016. https://arxiv.org/pdf/1606.05908.pdf

[2] Auto-Encoding Variational Bayes. Kingma et al., 2014. https://arxiv.org/pdf/1312.6114.pdf

[3] Variational inference. Stanford CS228. https://ermongroup.github.io/cs228-notes/inference/variational/

[4] Deriving the KL divergence loss for VAEs. Stack Exchange user user3658307 and Wei Zhong. 2020. https://stats.stackexchange.com/questions/318748/deriving-the-kl-divergence-loss-for-vaes

[5] VAE Approximation Error: ELBO and Exponential Families. Shekhovtsov et al., ICLR 2022. https://openreview.net/forum?id=OIs3SxU5Ynl

[6] Inference Suboptimality in Variational Autoencoders. Cremer et al., ICML 2018. https://arxiv.org/pdf/1801.03558.pdf

[7] Variational autoencoders. Jeremy Jordan, 2018. https://www.jeremyjordan.me/variational-autoencoders/

[8] 【Learning Notes】变分自编码器（Variational Auto-Encoder，VAE）. CSDN user MoussaTintin, 2016. https://blog.csdn.net/JackyTintin/article/details/53641885
