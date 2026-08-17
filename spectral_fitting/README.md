Files included here contain summary fits from all spectral fitting of the included galaxies.

In each directory (broken out by subsample)  there is specall_models.pkl, which is a pickled `pandas` dataframe with each row corresponding to an individual spectrum, and specall_models_dict.pkl, which is a pickled version of the dictionary from which the dataframe was created.

To open:

```python
import pickle

specdf = pickle.load(open('specall_models.pkl', 'rb'))
specdict = pickle.load(open('specall_models_dict.pkl', 'rb'))
```
