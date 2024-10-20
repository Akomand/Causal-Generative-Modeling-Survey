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
1. **CausalVAE: Disentangled Representation Learning via Neural Structural Causal Models**, *CVPR 2021* [[paper](https://openaccess.thecvf.com/content/CVPR2021/html/Yang_CausalVAE_Disentangled_Representation_Learning_via_Neural_Structural_Causal_Models_CVPR_2021_paper.html)]
  
2. **Weakly Supervised Disentangled Generative Causal Representation Learning**, *JMLR 2022* [[paper](https://arxiv.org/abs/2010.02637)]

3. **SCM-VAE: Learning Identifiable Causal Representations via Structural Knowledge**, *IEEE Big Data 2022* [[paper](https://ieeexplore.ieee.org/document/10021114)]

4. **Learning Causally Disentangled Representations via the Principle of Independent Causal Mechanisms**, *IJCAI 2024* [[paper](https://arxiv.org/abs/2306.01213)]

5. **Unpaired Multi-Domain Causal Representation Learning**, *NeurIPS 2023* [[paper](https://openreview.net/forum?id=zW1uVN6Mbv)],

6. **Causal Representation Learning Made Identifiable by Grouping of Observational Variables**, *ICML 2024* [[paper](https://openreview.net/forum?id=SL6V527p1F&referrer=%5Bthe%20profile%20of%20Aapo%20Hyvarinen%5D(%2Fprofile%3Fid%3D~Aapo_Hyvarinen1))]

7. **Multi-View Causal Representation Learning with Partial Observability**, *ICLR 2024* [[paper](https://openreview.net/forum?id=OGtnhKQJms)]

8. **Learning Temporally Causal Latent Processes from General Temporal Data**, *ICLR 2022* [[paper](https://openreview.net/forum?id=RDlLMjLJXdq)]

9. **Temporally Disentangled Representation Learning**, *NeurIPS 2022* [[paper](https://openreview.net/forum?id=Vi-sZWNA_Ue)]

10. **Temporally Disentangled Representation Learning under Unknown Nonstationarity**, *NeurIPS 2023* [[paper](https://openreview.net/forum?id=V8GHCGYLkf&noteId=jgG1mMzOkD)]

   
### Interventional
1. **Interventional Causal Representation Learning**, *ICML 2023* [[paper](https://arxiv.org/abs/2209.11924)]

2. 


### Counterfactual



## Controllable Counterfactual Generation (CCG)



