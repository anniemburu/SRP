# Student Research Project

This repository holds the experiment log, a to do list, links to relevant repositories, relevant input data, results and whatnot of the SRP. May also include other related personal research ideas of mine. 

## To Do Lists

Work on BiasCon [[3]](#3) paper. 
- [ ] Fork the BiasCon repository.
- Assuming you have access to bias labels for colored MNIST data:
- [ ] Implement true negative sampling [[2]](#2) and hard positive sampling [[5]](#5).
- [ ] Implement a way of saving the loss and accuracy trajectories. 
- [ ] Run the experiments for the original BiasCon, True Negative Sampling and Hard Sampling for different correlations.
- [ ] Do t-sne representations for each 3.
- [ ] Try these steps on other biased datasets such as Corrupted CIFAR10.  

Work on Supervised Contrastive Learning [[4]](#4) paper.
- [ ] Fork the SupCon repository.
- [ ] Implement true negative sampling [[2]](#2) and hard positive sampling [[5]](#5).
- [ ] Run experiments for these 3 variants on regular, unbiased datasets such as MNIST, CIFAR10, CIFAR100. 
- [ ] Formulate Hard Positives and write the to do list for that. 

## References

<a id="1">[1]</a> 
Ting Chen, Simon Kornblith, Mohammad Norouzi, and Geoffrey Hinton. A simple
framework for contrastive learning of visual representations. In *Proceedings of the
37th International Conference on Machine Learning*. PMLR, 2020.

<a id="2">[2]</a> 
Ching-Yao Chuang, Joshua Robinson, Yen-Chen Lin, Antonio Torralba, and Stefanie
Jegelka. Debiased contrastive learning. In *Advances in Neural Information Processing
Systems*, 2020.

<a id="3">[3]</a>
Youngkyu Hong and Eunho Yang. Unbiased classification through bias-contrastive
and bias-balanced learning. In *Advances in Neural Information Processing Systems*,
2021.

<a id="4">[4]</a> 
Prannay Khosla, Piotr Teterwak, Chen Wang, Aaron Sarna, Yonglong Tian, Phillip Isola, Aaron Maschinot, Ce Liu and Dilip Krishnan. Supervised Contrastive Learning. In *Advances in Neural Information Processing Systems*, 2020. 

<a id="5">[5]</a> 
Joshua David Robinson, Ching-Yao Chuang, Suvrit Sra, and Stefanie Jegelka. Contrastive learning with hard negative samples. In *International Conference on Learning Representations*, 2021.

