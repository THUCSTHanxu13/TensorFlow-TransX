# TensorFlow-TransX

The implementation of TransE [1], TransH [2], TransR [3], TransD [4] for knowledge representation learning (KRL). The overall framework is based on TensorFlow.

# Evaluation Results

More results about models can be found in ("https://github.com/thunlp/KB2E").

# Data

Datasets are required in the following format, containing three files:

triple2id.txt: training file, the first line is the number of triples for training. Then the follow lines are all in the format (e1, e2, rel).

entity2id.txt: all entities and corresponding ids, one per line. The first line is the number of entities.

relation2id.txt: all relations and corresponding ids, one per line. The first line is the number of relations.

You can download FB15K from [[Download]](http://pan.baidu.com/s/1eRD9B4A), and the more datasets can also be found in ("https://github.com/thunlp/KB2E").

# Compile

bash make.sh
python transX.py

# Citation

If you use the code, please kindly cite the papers listed in our reference.

# Reference

[1] Bordes, Antoine, et al. Translating embeddings for modeling multi-relational data. Proceedings of NIPS, 2013.

[2]	Zhen Wang, Jianwen Zhang, et al. Knowledge Graph Embedding by Translating on Hyperplanes. Proceedings of AAAI, 2014.

[3] Yankai Lin, Zhiyuan Liu, et al. Learning Entity and Relation Embeddings for Knowledge Graph Completion. Proceedings of AAAI, 2015.

[4] Guoliang Ji, Shizhu He, et al. Knowledge Graph Embedding via Dynamic Mapping Matrix. Proceedings of ACL, 2015.
