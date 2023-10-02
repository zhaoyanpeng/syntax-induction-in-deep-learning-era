
## Dataset

[WSJ](https://catalog.ldc.upenn.edu/LDC99T42), [CTB](https://catalog.ldc.upenn.edu/LDC2005T01), [SPMRL](https://dokufarm.phil.hhu.de/spmrl2014/), and [UD](https://universaldependencies.org/) are widely used. You can check out [XCFG](https://github.com/zhaoyanpeng/xcfg) for treebank preprocessing.

## Dependency Grammar Induction

## Constituency Grammar Induction

Compound Probabilistic Context-Free Grammars for Grammar Induction, [paper](https://arxiv.org/abs/1906.10225), [code](https://github.com/harvardnlp/compound-pcfg).

Unsupervised Recurrent Neural Network Grammars, [paper](https://arxiv.org/abs/1904.03746), [code](https://github.com/harvardnlp/urnng).

Unsupervised Latent Tree Induction with Deep Inside-Outside Recursive Autoencoders, [paper](https://arxiv.org/abs/1904.02142), [code](https://github.com/iesl/diora).

Unsupervised Learning of PCFGs with Normalizing Flow. [paper](https://www.aclweb.org/anthology/P19-1234/). [code](https://github.com/lifengjin/acl_flow).

## Emerging Topics in Unsupervised Grammar Induction

### Visually Grounded Grammar Induction

- Visually Grounded Neural Syntax Acquisition, [[paper](https://arxiv.org/abs/1906.02890)], [[code](https://github.com/ExplorerFreda/VGNSL)].
- Visually Grounded Compound PCFGs, [[paper](https://arxiv.org/abs/2009.12404)], [[code](https://github.com/zhaoyanpeng/vpcfg)].
- VLGrammar: Grounded Grammar Induction of Vision and Language, [[paper](https://arxiv.org/abs/2103.12975)], [[code](https://github.com/evelinehong/VLGrammar)].

### Grammar Induction with Language Models

#### Specialized LMs

- Neural Language Modeling by Jointly Learning Syntax and Lexicon, [[paper](https://arxiv.org/abs/1711.02013)], [[code](https://github.com/yikangshen/PRPN)].
- Ordered Neurons: Integrating Tree Structures into Recurrent Neural Networks, [[paper](https://arxiv.org/abs/1810.09536)], [[code](https://github.com/yikangshen/Ordered-Neurons)].

#### General-Purpose LMs

- Are Pre-trained Language Models Aware of Phrases? Simple but Strong Baselines for Grammar Induction, [[paper](https://arxiv.org/abs/2002.00737)], [[code](https://github.com/galsang/trees_from_transformers)].
- Perturbed Masking: Parameter-free Probing for Analyzing and Interpreting BERT, [[paper](https://arxiv.org/abs/2004.14786)], [[code](https://github.com/LividWo/Perturbed-Masking)].

### Neural Lexicalized Grammar Induction

- The Return of Lexical Dependencies: Neural Lexicalized PCFGs, [[paper](https://arxiv.org/abs/2007.15135)], [[code](https://github.com/neulab/neural-lpcfg)].
- Neural Bi-Lexicalized PCFG Induction, [[paper](https://arxiv.org/abs/2105.15021)], [[code](https://github.com/sustcsonglin/TN-PCFG)].

### Transfer Learning for Grammar Induction

#### Cross-Lingual Transfer

- Multilingual Grammar Induction with Continuous Language Identification, [[paper](https://aclanthology.org/D19-1576/)], [[code]()].

#### Cross-Domain Transfer
  
- On the Transferability of Visually Grounded PCFGs, [[paper]()], [[code](https://github.com/zhaoyanpeng/cpcfg)].

### Language Acquisition

Bootstrapping Language Acquisition, [paper](https://doi.org/10.1016/j.cognition.2017.02.009), [code](). 

## Syntax for Downstream Tasks

Scalable Syntax-Aware Language Models Using Knowledge Distillation. [paper](https://www.aclweb.org/anthology/P19-1337/). [code](#).

Language Modeling with Shared Grammar. [paper](https://www.aclweb.org/anthology/P19-1437/). [code](#).

Learning to Compose Task-Specific Tree Structures, [paper](https://arxiv.org/abs/1707.02786), [code](https://github.com/jihunchoi/unsupervised-treelstm).

Learning Latent Trees with Stochastic Perturbations and Differentiable Dynamic Programming, [paper](https://arxiv.org/abs/1906.09992), [code](https://github.com/FilippoC/diffdp).
