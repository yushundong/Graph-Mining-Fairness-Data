# Graph-Mining-Fairness-Data

Open-source datasets for paper "Fairness in Graph Mining: A Survey" [\[PDF\]](http://yushundong.github.io/files/fairness_survey.pdf).


## Citation

If you find it useful, please cite our paper. Thank you!

```
@article{dong2022fairness,
  title={Fairness in Graph Mining: A Survey},
  author={Dong, Yushun and Ma, Jing and Chen, Chen and Li, Jundong},
  journal={arXiv preprint arXiv:2204.09888},
  year={2022}
}
```



## Usage & Examples



~~~python
from dataloading import load_data

# Load a dataset. 
# Available choices: 'credit', 'german', 'recidivism', 'facebook', 'pokec_z', 'pokec_n', 'nba', 'twitter', 'google+', 'LCC', 'LCC_small', 'cora', 'citeseer', 'pubmed', 'amazon', 'yelp', 'epinion', 'ciao', 'dblp', 'filmtrust', 'lastfm', 'ml-100k', 'ml-1m', 'ml-20m', 'oklahoma', 'unc28'.
adj, features, labels, idx_train, idx_val, idx_test, sens, sens_idx = load_data('credit')

~~~

