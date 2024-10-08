# Kullback-Leibler Divergence

*KL divergence* aims to measure the difference between two probability distributions.
The *KL divergencel* orginates from Information Theory and it is closely related to Information Entropy. 

## Information Entropy 
The entropy of a random variable quantifies the average level of uncertainty.  If the uncertainty increases, then the information entropy becomes larger. For a probability distribution $p(x)$, entropy is defined : 
$H(x) = -\sum_{x \in X} p(x) \log p(x)$

## KL divergence 
The KL divergence is a slight modification of the entropy fomula. Assuming there is a **true** probability distribution $p(x)$ and a predicted distribution $q(x)$, KL divergence is defined as follow: 
$ D_{KL}(p(x)||q(x)) = \sum_{x \in X}  p(x) (\log p(x) - \log q(x))$

### Properties

* Non-negativity: $D_{KL} \ge 0$ 
* Asymmetry: $D_{KL}(p(x)||q(x)) \ne D_{KL}(q(x)||p(x)) $
* Intuitive: The larger the value of KL divergence, the greater the information loss or error between the true probability and the predicted probability.  




## References 
* https://www.vectorexplore.com/tech/loss-functions/kl-divergence/ 
* https://pytorch.org/docs/stable/generated/torch.nn.KLDivLoss.html
* https://blog.csdn.net/qq_50001789/article/details/128974654
* https://hanj.cs.illinois.edu/cs412/bk3/KL-divergence.pdf