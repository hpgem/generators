## Generators for simulating data for `nanomesh`

Split off from: https://github.com/hpgem/nanomesh/tree/194e95d8df9ba6b297b58dd53b8895dc5444619a

### Pygalmesh (linux only)

To use some of the additional functionality depending on pygalmesh,
first install the dependencies for pygalmesh (CGAL and EIGEN3)

```
sudo apt-get install libcgal-dev libeigen3-dev
```

Someof the functions in this notebook needs
[our fork of pygalmesh](https://github.com/hpgem/pygalmesh). To install:

```
pip install git+http://git@github.com/hpgem/pygalmesh
```
