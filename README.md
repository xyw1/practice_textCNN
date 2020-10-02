## prepare IMDB data

IMDB (Internet Movie Database) datasets are publicly available datasets consisting of 50K movie reviews for binary sentiment classification.
1. Download IMDB data

open url:  http://ai.stanford.edu/~amaas/data/sentiment/aclImdb_v1.tar.gz and downloading will start automaticly.

2.  Extract *tar.gz file into `../data` directory

```shell
cd /path/to/src
cd ../data
tar -xzvf /path/to/aclImdb_v1.tar.gz
```


```shell
$ ls aclImdb
# README  imdb.vocab  imdbEr.txt  test  train
```
