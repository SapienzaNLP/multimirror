# MultiMirror: Neural Cross-lingual Word Alignment for Multilingual Word Sense Disambiguation

This repo hosts the resources released in [MultiMirror: Neural Cross-lingual Word Alignment for Multilingual Word Sense Disambiguation](https://www.ijcai.org/proceedings/2021/539), 
our paper accepted at IJCAI 2021. MultiMirror is a sense projection approach for multilingual WSD based on a novel discriminative
word alignment model. The sense-tagged datasets it produces lead a standard WSD classifier to achieve state-of-the-art performances
on established benchmarks in French, German, Italian, Spanish and Japanese.

You can find in *data/mwsd/* instructions to download the generated sense-tagged corpora in the afore-mentioned languages.
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
