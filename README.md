# MultiMirror: Neural Cross-lingual Word Alignment for Multilingual Word Sense Disambiguation

This repo hosts the resources released in [MultiMirror: Neural Cross-lingual Word Alignment for Multilingual Word Sense Disambiguation](https://www.ijcai.org/proceedings/2021/539), 
a paper we presented at IJCAI 2021. MultiMirror is a cross-lingual sense projection approach for multilingual WSD based on a novel discriminative
word alignment model. The sense-tagged datasets it produces lead a standard WSD classifier to achieve state-of-the-art performances
on established benchmarks in French, German, Italian, Spanish and Japanese.

In *data/mwsd/* you can find instructions to download the generated sense-tagged corpora in the afore-mentioned languages.
Furthermore, *data/alignment/* also reports how to download the manually-annotated word alignments datasets we produced for
French, German, Italian and Spanish.

To train the WSD models, we suggest using [wsd](https://github.com/edobobo/wsd), the library we developed for WSD classification.

If you find our resources useful in your work, please cite us with:
```
@inproceedings{ijcai2021-539,
  title     = {MultiMirror: Neural Cross-lingual Word Alignment for Multilingual Word Sense Disambiguation},
  author    = {Procopio, Luigi and Barba, Edoardo and Martelli, Federico and Navigli, Roberto},
  booktitle = {Proceedings of the Thirtieth International Joint Conference on
               Artificial Intelligence, {IJCAI-21}},
  publisher = {International Joint Conferences on Artificial Intelligence Organization},
  editor    = {Zhi-Hua Zhou},
  pages     = {3915--3921},
  year      = {2021},
  month     = {8},
  note      = {Main Track}
  doi       = {10.24963/ijcai.2021/539},
  url       = {https://doi.org/10.24963/ijcai.2021/539},
}
```

## License
This project is released under the CC-BY-NC-SA 4.0 license (see `LICENSE`).

## Acknowledgements
The authors gratefully acknowledge the support of the [ERC Consolidator Grant MOUSSE](http://mousse-project.org) No. 726487 and the [ELEXIS project](https://elex.is/) No. 731015 under the European Union’s Horizon 2020 research and innovation programme.

This work was supported in part by the MIUR under the grant "Dipartimenti di eccellenza 2018-2022" of the Department of Computer Science of the Sapienza University of Rome.
