# From Identifiable Causal Representations to Controllable Counterfactual Generation: A Survey on Causal Generative Modeling

This is the github supplement to the paper [From Identifiable Causal Representations to Controllable Counterfactual Generation: A Survey on Causal Generative Modeling](https://openreview.net/forum?id=PUpZXvNqmb) published in the Transactions on Machine Learning Research (TMLR).


**Abstract:** Deep generative models have shown tremendous capability in data density estimation and data generation from finite samples. While these models have shown impressive performance by learning correlations among features in the data, some fundamental shortcomings are their lack of explainability, tendency to induce spurious correlations, and poor out-of-distribution extrapolation. To remedy such challenges, recent work has proposed a shift toward causal generative models. Causal models offer several beneficial properties to deep generative models, such as distribution shift robustness, fairness, and interpretability. Structural causal models (SCMs) describe data-generating processes and model complex causal relationships and mechanisms among variables in a system. Thus, SCMs can naturally be combined with deep generative models. We provide a technical survey on causal generative modeling categorized into causal representation learning and controllable counterfactual generation methods. We focus on fundamental theory, methodology, drawbacks, datasets, and metrics. Then, we cover applications of causal generative models in fairness, privacy, out-of-distribution generalization, precision medicine, and biological sciences. Lastly, we discuss open problems and fruitful research directions for future work in the field.



## Causal Representation Learning (CRL)
1. [**CausalVAE: Disentangled Representation Learning via Neural Structural Causal Models**](https://openaccess.thecvf.com/content/CVPR2021/html/Yang_CausalVAE_Disentangled_Representation_Learning_via_Neural_Structural_Causal_Models_CVPR_2021_paper.html), *CVPR*, 2021.

     Mengyue Yang, Furui Liu, Zhitang Chen, Xinwei Shen, Jianye Hao, Jun Wang.
  
2. [**Weakly Supervised Disentangled Generative Causal Representation Learning**](https://arxiv.org/abs/2010.02637), *JMLR*, 2022. 

      Xinwei Shen, Furui Liu, Hanze Dong, Qing Lian, Zhitang Chen, and Tong Zhang.

3. [**SCM-VAE: Learning Identifiable Causal Representations via Structural Knowledge**](https://ieeexplore.ieee.org/document/10021114), *IEEE Big Data*, 2022. 

      Aneesh Komanduri, Yongkai Wu, Wen Huang, Feng Chen, and Xintao Wu.

4. [**Learning Causally Disentangled Representations via the Principle of Independent Causal Mechanisms**](https://arxiv.org/abs/2306.01213), *IJCAI*, 2024.

      Aneesh Komanduri, Yongkai Wu, Feng Chen, and Xintao Wu.

## Controllable Counterfactual Generation (CCG)



