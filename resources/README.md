# Kullback Leibler Divergence

*KL divergence* aims to measure the difference between two probability distributions.
The *KL divergencel* orginates from Information Theory and it is closely related to Information Entropy. 

## Information Entropy 
The entropy of a random variable quantifies the average level of uncertainty.  If the uncertainty increases, then the information entropy becomes larger. For a probability distribution $p(x)$, entropy is defined : 
$H(x) = -\sum_{x \in X} p(x) \log p(x)$

## KL divergence 
The KL divergence is a slight modification of the entropy fomula. Assuming there is a **true** probability distribution $p(x)$ and a predicted distribution $q(x)$, KL divergence is defined as follow: 
$D_{KL}(p(x)||q(x)) = \sum_{x \in X}  p(x) (\log p(x) - \log q(x))$

### Properties

* Non-negativity: $D_{KL} \ge 0$ 
* Asymmetry: $D_{KL}(p(x)||q(x)) \ne D_{KL}(q(x)||p(x)) $
* Intuitive: The larger the value of KL divergence, the greater the information loss or error between the true probability and the predicted probability.  




## References 
* https://www.vectorexplore.com/tech/loss-functions/kl-divergence/ 
* https://pytorch.org/docs/stable/generated/torch.nn.KLDivLoss.html
* https://blog.csdn.net/qq_50001789/article/details/128974654
* https://hanj.cs.illinois.edu/cs412/bk3/KL-divergence.pdf
* https://pytorch.org/docs/stable/generated/torch.nn.functional.kl_div.html 
* https://blog.csdn.net/jinyi763776890/article/details/131178144


# Equal Error Rate

EER is defined as the point where the True positive rato (TPR) equals to False positive rato (FPR). 
In other words, it is the threshold at which the system is equally likely to wrongly accept a non-matching individual as it is to wrongly reject a matching individual. 


## Code Implementation 
[Wespeaker](https://github.com/wenet-e2e/wespeaker/blob/master/wespeaker/utils/score_metrics.py#L79)

## References
* https://www.cnblogs.com/cdeng/p/3471527.html 

# minimum Detection Cost Function
The minDCF is a more comprehensive metric that takes into account the costs associated with different types of errors (false acceptances and false rejections) and the prior probabilities of the classes (target vs. non-target speakers).
For example, in a military system, we want the system to be stricter and not to mistakenly allow a person to pass.


## Code Implementation 
[Wespeaker](https://github.com/wenet-e2e/wespeaker/blob/master/wespeaker/utils/score_metrics.py#L96)

## References 
* https://blog.csdn.net/weixin_41126303/article/details/114293441 



# Bayes theorem 
Bayes' theorem allows us to update a probability of a hypothesis based on new evidences. 
The theorem is expressed mathematically as:

$P(H|E) = \frac{P(E|H)* P(H)}{P(E)}$,

where H denotes the hypothesis, E denotes the evidence. 
$P(H|E)$: Posterior probablity  
$P(H)$: Prior probability  
$P(E|H)$: Likelihood  
$P(E)$: marginal probability


## References 
* https://www.freecodecamp.org/news/bayes-rule-explained/
* https://liaoxuefeng.com/blogs/all/2023-08-27-bayes-explain/index.html 