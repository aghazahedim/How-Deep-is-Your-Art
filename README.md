<div align="center">
  
# **How Deep is Your Art: An Experimental Study on the Limits of Artistic Understanding in a Single-Task, Single-Modality Neural Network**
Mahan Agha Zahedi<sup>1</sup>, Niloofar Gholamrezaei<sup>2</sup>, [Alex Doboli](http://www.ece.stonybrook.edu/~adoboli/)<sup>1</sup>

<sup>1</sup>Stony Brook University, <sup>2</sup>Texas Tech University

Preprint available on [Arxiv](https://arxiv.org/abs/2203.16031)

[![DOI](https://zenodo.org/badge/798355329.svg)](https://zenodo.org/doi/10.5281/zenodo.11167489)

## Abstract
</div>

<div align="justify">
Computational modeling of artwork meaning is  complex and difficult. This is because art interpretation is multidimensional and highly subjective. This paper experimentally investigated the degree to which a state-of-the-art Deep Convolutional Neural Network (DCNN), a popular Machine Learning approach, can correctly distinguish modern conceptual art work into the galleries devised by art curators. Two hypotheses were proposed to state that the DCNN model uses Exhibited Properties for classification, like shape and color, but not Non-Exhibited Properties, such as historical context and artist intention. The two hypotheses were experimentally validated using a methodology designed for this purpose. VGG-11 DCNN pre-trained on ImageNet dataset and discriminatively fine-tuned was trained on handcrafted datasets designed from real-world conceptual photography galleries. Experimental results supported the two hypotheses showing that the DCNN model ignores Non-Exhibited Properties and uses only Exhibited Properties for artwork classification. This work points to current DCNN limitations, which should be addressed by future DNN models.



![Fig_1_updated](https://github.com/aghazahedim/How-Deep-is-Your-Art/assets/38115241/b7239a28-69c6-48a1-a9a9-4b25ef606173) 

###### Art analysis using Levinson’s definition of art. (a) Art consists of Exhibited Properties (EXPs) and None-Exhibited Properties (NEXP). (b) Art understanding is gained by relating EXPs to NEXPs rather than merely looking at EXPs. (c) The difficulty in art understanding is shown as a spectrum with an example for each end: top, "Fountain” by Marcel Duchamp, a conceptual piece with a greater significance of NEXPs, and bottom: “The Accident,” by William Geet, a figurative piece with a more literal visual narrative and therefore more significance of EXPs.
</div>

## Contact
Please feel free to reach out to any of the authors or me at [Mahan.AghaZahedi@stonybrook.edu](mailto:Mahan.AghaZahedi@stonybrook.edu)


## Citation
If you find this project useful in your research, please consider citing:
```
@article{zahedi2022deep,
  title={How Deep is Your Art: An Experimental Study on the Limits of Artistic Understanding in a Single-Task, Single-Modality Neural Network},
  author={Zahedi, Mahan Agha and Gholamrezaei, Niloofar and Doboli, Alex},
  journal={arXiv preprint arXiv:2203.16031},
  year={2022}
}
