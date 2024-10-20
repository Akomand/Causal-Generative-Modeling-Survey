# From Identifiable Causal Representations to Controllable Counterfactual Generation: A Survey on Causal Generative Modeling

This is the github supplement to the paper [From Identifiable Causal Representations to Controllable Counterfactual Generation: A Survey on Causal Generative Modeling](https://openreview.net/forum?id=PUpZXvNqmb) published in the Transactions on Machine Learning Research (TMLR).

```bibtex
@article{komanduri2024survey,
title={From Identifiable Causal Representations to Controllable Counterfactual Generation: A Survey on Causal Generative Modeling},
author={Aneesh Komanduri and Xintao Wu and Yongkai Wu and Feng Chen},
journal={Transactions on Machine Learning Research},
issn={2835-8856},
year={2024},
url={https://openreview.net/forum?id=PUpZXvNqmb},
}
```

**Abstract:** Deep generative models have shown tremendous capability in data density estimation and data generation from finite samples. While these models have shown impressive performance by learning correlations among features in the data, some fundamental shortcomings are their lack of explainability, tendency to induce spurious correlations, and poor out-of-distribution extrapolation. To remedy such challenges, recent work has proposed a shift toward causal generative models. Causal models offer several beneficial properties to deep generative models, such as distribution shift robustness, fairness, and interpretability. Structural causal models (SCMs) describe data-generating processes and model complex causal relationships and mechanisms among variables in a system. Thus, SCMs can naturally be combined with deep generative models. We provide a technical survey on causal generative modeling categorized into causal representation learning and controllable counterfactual generation methods. We focus on fundamental theory, methodology, drawbacks, datasets, and metrics. Then, we cover applications of causal generative models in fairness, privacy, out-of-distribution generalization, precision medicine, and biological sciences. Lastly, we discuss open problems and fruitful research directions for future work in the field.



## Causal Representation Learning (CRL)
### Observational
1. [**CausalVAE: Disentangled Representation Learning via Neural Structural Causal Models**](https://openaccess.thecvf.com/content/CVPR2021/html/Yang_CausalVAE_Disentangled_Representation_Learning_via_Neural_Structural_Causal_Models_CVPR_2021_paper.html),

     *IEEE Conference on Computer Vision and Pattern Recognition (CVPR)*, 2021.

     Mengyue Yang, Furui Liu, Zhitang Chen, Xinwei Shen, Jianye Hao, Jun Wang.
  
2. [**Weakly Supervised Disentangled Generative Causal Representation Learning**](https://arxiv.org/abs/2010.02637),

      *Journal of Machine Learning Research (JMLR)*, 2022. 

      Xinwei Shen, Furui Liu, Hanze Dong, Qing Lian, Zhitang Chen, and Tong Zhang.

3. [**SCM-VAE: Learning Identifiable Causal Representations via Structural Knowledge**](https://ieeexplore.ieee.org/document/10021114),

      *IEEE International Conference on Big Data (BigData)*, 2022. 

      Aneesh Komanduri, Yongkai Wu, Wen Huang, Feng Chen, and Xintao Wu.

4. [**Learning Causally Disentangled Representations via the Principle of Independent Causal Mechanisms**](https://arxiv.org/abs/2306.01213),

      *International Joint Conference on Artificial Intelligence (IJCAI)*, 2024.

      Aneesh Komanduri, Yongkai Wu, Feng Chen, and Xintao Wu.

5. [**Unpaired Multi-Domain Causal Representation Learning**](https://openreview.net/forum?id=zW1uVN6Mbv),

      *Advances in Neural Information Processing Systems (NeurIPS)*, 2023.

      Nils Sturma, Chandler Squires, Mathias Drton, and Caroline Uhler.

6. [**Causal Representation Learning Made Identifiable by Grouping of Observational Variables**](https://openreview.net/forum?id=SL6V527p1F&referrer=%5Bthe%20profile%20of%20Aapo%20Hyvarinen%5D(%2Fprofile%3Fid%3D~Aapo_Hyvarinen1)),

      *International Conference on Machine Learning (ICML)*, 2024.

      Hiroshi Morioka and Aapo Hyvarinen.

7. [**Multi-View Causal Representation Learning with Partial Observability**](https://openreview.net/forum?id=OGtnhKQJms),

      *International Conference on Learning Representations (ICLR)*, 2024.

      Dingling Yao, Danru Xu, Sebastien Lachapelle, Sara Magliacane, Perouz Taslakian, Georg Martius, Julius von Kügelgen, and Francesco Locatello.

8. [**Learning Temporally Causal Latent Processes from General Temporal Data**](https://openreview.net/forum?id=RDlLMjLJXdq),

      *International Conference on Learning Representations (ICLR)*, 2022.

      Weiran Yao, Yuewen Sun, Alex Ho, Changyin Sun, and Kun Zhang.

9. [**Temporally Disentangled Representation Learning**](https://openreview.net/forum?id=Vi-sZWNA_Ue),

      *Advances in Neural Information Processing Systems (NeurIPS)*, 2022.

      Weiran Yao, Guangyi Chen, and Kun Zhang.

10. [**Temporally Disentangled Representation Learning under Unknown Nonstationarity**](https://openreview.net/forum?id=V8GHCGYLkf&noteId=jgG1mMzOkD),

      *Advances in Neural Information Processing Systems (NeurIPS)*, 2023.

      Xiangchen Song, Weiran Yao, Yewen Fan, Xinshuai Dong, Guangyi Chen, Juan Carlos Niebles, Eric Xing, and Kun Zhang.


   
### Interventional

### Counterfactual



## Controllable Counterfactual Generation (CCG)



