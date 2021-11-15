# PRASE-Python
The code of paper _**Unsupervised Knowledge Graph Alignment by Probabilistic Reasoning and Semantic Embedding**_ [[arxiv](https://arxiv.org/pdf/2105.05596.pdf)] [[ijcai](https://www.ijcai.org/proceedings/2021/0278.pdf)] in Proceedings of IJCAI 2021.

## Package
The packages of PRASE-Python is presented below.

      ├─PRASE-Python
      │  ├─data: necessary data for running the test script
      │  ├─model: the implementation of PARIS
      │  ├─objects: Entity/Relation/KG/KGs objects of PRASE
      │  ├─test.py: a test script example

## Installation
### Dependencies
- Python 3.x
- Numpy

### Start
Use the following command to get a quick start:

    python test.py

This test script performs PRASE on D-W-15K-V2 with both the embedding and the mapping feedback from SE module (i.e., BootEA).
You can revise the code to customize the PRASE model.

### Usage
The core of this package is actually the Python-version implementation of [PARIS](http://webdam.inria.fr/paris/).
Since this package does not contain the implementations of embedding-based approaches, you should adopt the embedding-based implementations from external libraries to run PRASE, such as [OpenEA](https://github.com/nju-websoft/OpenEA "OpenEA").

## Citation

If you use this model or code, please cite it as follows:

```
@inproceedings{ijcai2021-278,
  title     = {Unsupervised Knowledge Graph Alignment by Probabilistic Reasoning and Semantic Embedding},
  author    = {Qi, Zhiyuan and Zhang, Ziheng and Chen, Jiaoyan and Chen, Xi and Xiang, Yuejia and Zhang, Ningyu and Zheng, Yefeng},
  booktitle = {Proceedings of the Thirtieth International Joint Conference on
               Artificial Intelligence, {IJCAI-21}},
  publisher = {International Joint Conferences on Artificial Intelligence Organization},
  editor    = {Zhi-Hua Zhou},
  pages     = {2019--2025},
  year      = {2021},
  month     = {8},
  note      = {Main Track}
  doi       = {10.24963/ijcai.2021/278},
  url       = {https://doi.org/10.24963/ijcai.2021/278},
}
```
