# Alignment Data

|                                            Dataset                                            | # sentences | # alignments |
|:---------------------------------------------------------------------------------------------:|:-----------:|:------------:|
| [en-it](https://drive.google.com/drive/folders/1rjsHkiE4FhX7nYY_UwEksR3FKbmbHfN8?usp=sharing) |     300     |    3719     |
| [en-es](https://drive.google.com/drive/folders/1zJzfj5qRHYHthI_fbz8kNtIEwcZO4PeT?usp=sharing) |   300    |    3914     |
| [en-fr](https://drive.google.com/drive/folders/1lKIetXbxg2ZfYAlAqB7K80go45EIVs_w?usp=sharing) |   300    |    4882     |

The format of these data is a simple tsv structured as follows:
```
<source-parallel-sentence> <\t> <target-parallel-sentence> <\t> <source-token>-<target-token> ...
```
Where the final space-separated field lists the tokens aligned. For instance:
```
I have a dog <\t> Io ho un cane <\t> 0-0 1-1 ...
```
