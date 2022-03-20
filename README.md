# ExaASC
ExaASC is a Target-based Stance detection Corpus on the Arabic Language. 
This corpus contains about 9500 tweets with replies
and target specified in the source tweet. Each sample has at least two stance annotations provided by Exa Corporation annotators. The stance of each reply is
annotated toward the target in the corresponding source tweet. Format of data is as follows
id, main (source tweet), reply, target, label of each annotator id and in the end majority_label.

## Train and Test Files
Training data `train_final.csv` and test data `test_final.csv` are provided in ths repository, please cite our paper if you used our data.

## Request for The Code
If you would like to access our training code, please contact via research@exalab.co with subject: ExaASC Request.

## Citation

If you are using this dataset, please cite the initial [paper](https://ieeexplore.ieee.org/document/9721486):

```
@inproceedings{9721486,
  author={Jaziriyan, Mohammad Mehdi and Akbari, Ahmad and Karbasi, Hamed},
  booktitle={2021 11th International Conference on Computer Engineering and Knowledge (ICCKE)}, 
  title={ExaASC: A General Target-Based Stance Detection Corpus in Arabic Language}, 
  year={2021},
  volume={},
  number={},
  pages={424-429},
  doi={10.1109/ICCKE54056.2021.9721486}
  }
```
