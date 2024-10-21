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

7. **Causal Representation Learning from Multiple Distributions: A General Setting**, *ICML 2024* [[paper](https://proceedings.mlr.press/v235/zhang24br.html)]

8. **Learning Linear Causal Representations from General Environments: Identifiability and Intrinsic Ambiguity**, *NeurIPS 2024* [[paper](https://arxiv.org/abs/2311.12267)]

9. **Identifying General Mechanism Shifts in Linear Causal Representations**, *NeurIPS 2024* [[paper]()]

10. **Multi-Domain Causal Representation Learning via Weak Distributional Invariances**, *AISTATS 2024* [[paper](https://proceedings.mlr.press/v238/ahuja24a.html)]

11. **Multi-View Causal Representation Learning with Partial Observability**, *ICLR 2024* [[paper](https://openreview.net/forum?id=OGtnhKQJms)]

12. **A Sparsity Principle for Partially Observable Causal Representation Learning**, *ICML 2024* [[paper](https://proceedings.mlr.press/v235/xu24ac.html)]

13. **Learning Temporally Causal Latent Processes from General Temporal Data**, *ICLR 2022* [[paper](https://openreview.net/forum?id=RDlLMjLJXdq)]

14. **Temporally Disentangled Representation Learning**, *NeurIPS 2022* [[paper](https://openreview.net/forum?id=Vi-sZWNA_Ue)]

15. **Temporally Disentangled Representation Learning under Unknown Nonstationarity**, *NeurIPS 2023* [[paper](https://openreview.net/forum?id=V8GHCGYLkf&noteId=jgG1mMzOkD)]

16. **CaRiNG: Learning Temporal Causal Representation under Non-Invertible Generation Process**, *ICML 2024* [[paper](https://proceedings.mlr.press/v235/chen24ai.html)]

   
### Interventional
11. **Interventional Causal Representation Learning**, *ICML 2023* [[paper](https://arxiv.org/abs/2209.11924)]

12. **Linear Causal Disentanglement via Interventions**, *ICML 2023* [[paper](https://arxiv.org/abs/2211.16467)]

13. **Learning Linear Causal Representations from Interventions under General Nonlinear Mixing**, *NeurIPS 2023* [[paper](https://arxiv.org/abs/2306.02235)]

14. **Identifiability Guarantees for Causal Disentanglement from Soft Interventions**, *NeurIPS 2023* [[paper](https://arxiv.org/abs/2307.06250)]

15. **Nonparametric Identifiability of Causal Representations from Unknown Interventions**, *NeurIPS 2023* [[paper](https://arxiv.org/abs/2306.00542)]

16. **Score-based Causal Representation Learning From Interventions**, *CRL@NeurIPS 2023* [[paper](https://openreview.net/forum?id=MytNJ6lXAV)]

17. **General Identifiability and Achievability for Causal Representation Learning**, *AISTATS 2024* [[paper](https://proceedings.mlr.press/v238/varici24a.html)]

18. **CITRIS: Causal Identifiability for Temporal Intervened Sequences**, *ICML 2022* [[paper](https://arxiv.org/abs/2202.03169)]

19. **Causal Representation Learning for Instantaneous and Temporal Effects in Interactive Systems**, *ICLR 2023* [[paper](https://arxiv.org/abs/2206.06169)]

20. **BISCUIT: Causal Representation Learning from Binary Interactions**, *UAI 2023* [[paper](https://proceedings.mlr.press/v216/lippe23a.html)]

21. **Disentanglement via Mechanism Sparsity Regularization: A New Principle for Nonlinear ICA**, *CLeaR 2022* [[paper](https://arxiv.org/abs/2107.10098)]

22. **Identifying Linearly-Mixed Causal Representations from Multi-Node Interventions**, *CLeaR 2024* [[paper](https://arxiv.org/abs/2311.02695)]

23. **Linear Causal Representation Learning from Unknown Multi-node Interventions**, *NeurIPS 2024* [[paper](https://arxiv.org/abs/2406.05937)]


### Counterfactual
22. **Self-Supervised Learning with Data Augmentations Provably Isolates Content from Style**, *NeurIPS 2021* [[paper](https://arxiv.org/abs/2106.04619)]

23. **Weakly supervised causal representation learning**, *NeurIPS 2022* [[paper](https://arxiv.org/abs/2203.16437)]


## Controllable Counterfactual Generation (CCG)

### GAN-based

1. **CausalGAN: Learning Causal Implicit Generative Models with Adversarial Training**, *ICLR 2018* [[paper](https://openreview.net/forum?id=BJE-4xW0W)]

2. **Counterfactual Generative Networks**, *ICLR 2021* [[paper](https://arxiv.org/abs/2101.06046)]

3. **Counterfactual Generation under Confounding**, *CML4Impact@NeurIPS 2022* [[paper](https://arxiv.org/abs/2305.18183)]


### Flow/VAE-based

4. **Deep Structural Causal Models for Tractable Counterfactual Inference**, *NeurIPS 2020* [[paper](https://arxiv.org/abs/2006.06485)]

5. **High Fidelity Image Counterfactuals with Probabilistic Causal Models**, *ICML 2023* [[paper](https://arxiv.org/abs/2306.15764)]

6. **Deep Backtracking Counterfactuals for Causally Compliant Explanations**, *TMLR 2024* [[paper](https://openreview.net/forum?id=Br5esc2CXR)]


### Diffusion-based

6. **Diffusion Causal Models for Counterfactual Estimation**, *CLeaR 2022* [[paper](https://arxiv.org/abs/2202.10166)]

7. **Causal Diffusion Autoencoders: Toward Counterfactual Generation via Diffusion Probabilistic Models**, *ECAI 2024* [[paper](https://arxiv.org/abs/2404.17735)]

8. **Modeling Causal Mechanisms with Diffusion Models for Interventional and Counterfactual Queries**, arXiv [[paper](https://arxiv.org/abs/2302.00860)]

## Evaluation Metrics



## Datasets



## Libraries


## Applications

**Marrying Causal Representation Learning with Dynamical Systems for Science**, *NeurIPS 2024* [[paper](https://arxiv.org/abs/2405.13888)]

**Learning Identifiable Factorized Causal Representations of Cellular Responses**, *NeurIPS 2024* [[paper]()]

