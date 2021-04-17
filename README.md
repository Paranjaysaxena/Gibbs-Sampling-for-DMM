# Gibbs Sampling for Dirichlet Multinomial Mixture Model
This project is a proof-of-concept implementation of the collapsed Gibbs Sampling algorithm for Dirichlet Multinomial Mixture model as proposed by Yin & Wang [1]. It was built as a part of the course 'Machine Learning' (CS351) at NITK, Surathkal.

## Dataset format
There are four datasets used in the project: [T.json](Datasets/T.json), [S.json](Datasets/S.json), [TS.json](Datasets/TS.json), and [Tweet.json](Datasets/Tweet.json), as obtained from [2]. Each of these files contains data in the following format.
```
{"text": "nokia lumia launch", "cluster": 48}
{"text": "ison comet century", "cluster": 98}
{"text": "impact flu pandemic", "cluster": 118}
```

## References
1. J. Yin and J. Wang, "A dirichlet multinomial mixture model-based approach for short text clustering," *Proceedings of the 20th ACM SIGKDD international conference on Knowledge discovery and data mining*, pp 233–242, ACM, 2014.
2. J. Yin. (2015). "GSDMM," [Online]. Available: https://github.com/jackyin12/GSDMM/tree/master/data
3. R. Walker. (2017). "GSDMM: Short text clustering," [Online]. Available: https://github.com/rwalk/gsdmm
