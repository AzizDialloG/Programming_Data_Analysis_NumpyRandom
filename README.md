# Programming for Data Analysis
#### By Thierno Aziz Diallo G00265250

The following assignment concerns the numpy.random package in Python

## Installation

Use the package manager [pip](https://pip.pypa.io/en/stable/) to install numpy, matplotlib and seaborn.

```bash
pip install numpy
pip install matplotlib
pip install seaborn
```

## Usage of Numpy Random Package

```python
import numpy as np
```

### Simple Data Distribution Functions:
```python
array = np.random.randint(2, size=10)
array2 = np.random.random_integers(low=2, high=10, size=10)
rand = np.random.random()
rand_choice = np.random.choice(10, 3)
rand_byte = np.random.bytes(4)
```

### Permutation Functions:
```python
np.random.shuffle(array)
arr = np.random.permutation(arr)  
```

### Distribution Functions:
```python
binomial_dist = np.random.binomial(n=10, p=0.5, size=1000)
normal_dist = np.random.normal(size=1000)
poisson_dist = np.random.poisson(lam=2, size=1000)
uniform_dist = np.random.uniform(size=1000)
exponential_dist = np.random.exponential(size=1000)
```

### Numpy Random Seed Functions:
```python
print("using Seed function")
np.random.seed(0) 
print(np.random.rand(4))
np.random.seed(0)
print(np.random.rand(4))

print("Without Seed function")
np.random.seed(0) 
print(np.random.rand(4))
print(np.random.rand(4))
```

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.
## Reference:
#### [1]. Random Numbers in NumPy
##### https://www.w3schools.com/python/numpy_random.asp
#### How to Generate Random Numbers in Python
##### https://machinelearningmastery.com/how-to-generate-random-numbers-in-python/
##### https://realpython.com/python-random/
#### [2]. Generate all permutations of a list in Python
##### https://www.w3resource.com/python-exercises/list/python-data-type-list-exercise-18.php
#### Permutations and Combinations using Python
##### https://www.askpython.com/python/permutations-and-combinations-using-python
#### [3]. Distributions
##### https://data-flair.training/blogs/python-probability-distributions/
##### https://docs.scipy.org/doc/scipy/reference/tutorial/stats.html
#### [4] The Python Tutorial
##### https://docs.python.org/3/tutorial/



## License
[MIT](https://choosealicense.com/licenses/mit/)
