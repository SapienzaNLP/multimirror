# MWSD Data

|    Dataset   | # instances | # distinct synsets |
|:------------:|:-----------:|:-----------:|
|   [it](https://drive.google.com/file/d/17-UQV9An7nPUyacYZZL0LaVHph4Fse26/view?usp=sharing)   |    518941   |    36556   |
|   [es](https://drive.google.com/file/d/1sBxw_AFE880QgCFy9j_fV7LyIH56b8kF/view?usp=sharing)   |    551663   |    49933   |
|   [fr](https://drive.google.com/file/d/1M_X82mGJZbZOBfUhTggD6DcaDBhqBmfW/view?usp=sharing)   |    387416   |    28468   |
|   [de](https://drive.google.com/file/d/1p8pdpkkgoECWdutpCzGia91dhzMFeY_q/view?usp=sharing)   |    318222   |    21889   |
|   [ja](https://drive.google.com/file/d/1ufcAdayQEIPawXouvAhqfnIY5ekYRMYU/view?usp=sharing)   |    301498   |    25315   |

As the output format, we follow the scheme introduced in [SemEval 2013 task 12](https://www.aclweb.org/anthology/S13-2040.pdf)
and later chosen as the standard WSD format for the evaluation framework presented in [Raganato et al, 2017](https://www.aclweb.org/anthology/E17-1010.pdf).

A dataset consists of 2 files:
* a .xml file, storing the actual sentences and marking tagged instances (i.e. tokens) with an id
* a .txt file, mapping instances ids with the actual labels (synsets in our case)