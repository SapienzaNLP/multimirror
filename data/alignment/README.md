# Alignment Data

|                                            Dataset                                            | # sentences | # alignments |
|:---------------------------------------------------------------------------------------------:|:-----------:|:------------:|
| [en-it](https://drive.google.com/file/d/1Ojh_Gz88AGBsmVQtPLn-StwjrByvrwMG/view?usp=sharing) |     300     |    3719     |
| [en-es](https://drive.google.com/file/d/1xC6VYx_hypOi-uV5-7tDQXTtf1jGeySM/view?usp=sharing) |   300    |    3914     |
| [en-fr](https://drive.google.com/file/d/15uDpZMMy7kJQiEYMRfOoxVwA7OSjaEqe/view?usp=sharing) |   300    |    4882     |

The format of these data is a simple tsv structured as follows:
```
<source-parallel-sentence> <\t> <target-parallel-sentence> <\t> <source-token>-<target-token> ...
```
Where the final space-separated field lists the tokens aligned. For instance:
```
I have a dog <\t> Io ho un cane <\t> 0-0 1-1 ...
```
