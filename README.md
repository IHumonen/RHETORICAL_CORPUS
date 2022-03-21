RST-annotated parallel Russian-English corpus
=============================================

This repository holds a corpus of 112 short automatically rst-annotated russian microtexts and corresponding annotation scripts. To create it, we considered the English texts marked with RST and their Russian translations, conducting experiments to improve the existing Russian
parser, as well as to transfer annotation from English using automatic mapping. During our
work, we modified the division into elementary discursive units so that our segmentation
would sufficiently correspond to the English one and developed a gold segmentation standard
for a collection of texts, adapted the annotation instruction on rhetorical relations. After
analysing the performance of the parsers, we made several conclusions regarding the types of
errors and the differences between two languages. 

The project was developed as a part of the first year of HSE University's "Computational lingusistics" master program by students Daria Petrova and Innokentiy Humonen with the help of Polina Gusenkova (University of Potsdam, Student), Svetlana Toldova (HSE University, Associate Professor), Anastasiya A. Bonch-Osmolovskaya (HSE University, Associate Professor) and Manfred Stede (University of Potsdam, Professor).

You can read the full description of our work [here](https://drive.google.com/file/d/1GoGGJI2fLA2tVnlmUo3GvXyC9Sv_GzLy/view).

Scheme of the Russian parser's adaptation:

![text](https://github.com/IHumonen/RHETORICAL_CORPUS/blob/main/adaptation_scheme.png?raw=true)

Source data
-----------

The original parallel text corpus (annotated english texts and non-annotated russian translations) is available [here](https://github.com/PolinaGusenkova/arg-microtexts-multilayer-eng-rus).

License and Citation
--------------------

The corpus, the annotations and the associated code are released under a Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License. You can find a human-readable summary of the licence agreement here:

https://creativecommons.org/licenses/by-nc-sa/4.0/

If you are using our corpus for research purposes, please cite the following paper:

    Humonen I., Petrova D.  
    Developing of the parallel Russian-English corpus with the discourse annotation [Unpublished manuscript].
    Moscow, National Research University Higher School of Economics. 2022

Links
-----

* [Our paper](https://drive.google.com/file/d/1GoGGJI2fLA2tVnlmUo3GvXyC9Sv_GzLy/view)
* [Original corpus](https://github.com/PolinaGusenkova/arg-microtexts-multilayer-eng-rus)
* [Russian RST parser](https://github.com/tchewik/isanlp_rst)
* [Rhetorical structure theory](https://www.sfu.ca/rst/05bibliographies/bibs/Mann_Thompson_1988.pdf)
