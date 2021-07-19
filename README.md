# mlqe-pe
Multilingual Quality Estimation and Automatic Post-editing Dataset.
This is an updated version of the <a href="https://github.com/facebookresearch/mlqe">MLQE dataset</a> to include 
post-editing data, as well Ru-En data. Please refer to the MLQE repo for the NMT models that generated the data.
The multilingual NMT models used to generate translations for the zero-shot language pairs can be found here:
<a href="https://github.com/pytorch/fairseq/tree/master/examples/multilingual#mbart50-models">mBART50</a> (many-to-one for Ps-En and Km-En, 
and one-to-many for En-Cs and En-Ja).

## Citation

If you use this data in your work, please cite:

```bibtex
@article{fomicheva2020mlqepe,
    title={{MLQE-PE}: A Multilingual Quality Estimation and Post-Editing Dataset}, 
    author={Marina Fomicheva and Shuo Sun and Erick Fonseca and Fr\'ed\'eric Blain and Vishrav Chaudhary and Francisco Guzm\'an and Nina Lopatina and Lucia Specia and Andr\'e F.~T.~Martins},
    year={2020},
    journal={arXiv preprint arXiv:2010.04480}
}
```

```bibtex
@article{tacl2020,
    title = {Unsupervised Quality Estimation for Neural Machine Translation},
    author = {Fomicheva, Marina and Sun, Shuo and Yankovskaya, Lisa and Blain, Frédéric and Guzmán, Francisco and Fishel, Mark and Aletras, Nikolaos and Chaudhary, Vishrav and Specia, Lucia},
    journal = {Transactions of the Association for Computational Linguistics},
    volume = {8},
    pages = {539-555},
    year = {2020}
}
```
