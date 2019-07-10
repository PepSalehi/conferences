# Python vs Rust fro simulation
### Simulation scenario
- 100x100 box
- 1 day
- 200 cars
- 1000 users
- 0.2 probability to spawn a request
- random free car is assigned to the first pending request in the dict/hashmap

### Python
##### Tests
only sample tests implemented

#### Lines of code with documentation
in `simulation` folder  run:`find . -name '*.py' | xargs wc -l`


#### Performance
- less straight-forward implementation
```
Benchmark #1: python main.py
  Time (mean ± σ):     111.851 s ±  1.382 s    [User: 111.196 s, System: 1.497 s]
  Range (min … max):   110.063 s … 114.955 s    10 runs
```

- straight-forward implementation
```
Benchmark #1: env/bin/python simple_implementation.py
  Time (mean ± σ):     209.036 s ± 16.916 s    [User: 208.099 s, System: 0.619 s]
  Range (min … max):   193.671 s … 227.164 s    3 runs
```

#### Memory usage
`heaptrack python main.py`
![Memory allocation](python_memory.png "Allocated Heap")


#### Ecosystem
- full support

#### Language versions
- 3.6+ suffice for everything

----
### Rust
##### Tests
only sample tests implemented

#### Lines of code with documentation
in `simulation` folder  run:`find . -name '*.py' | xargs wc -l`


#### Performance


#### Memory usage


#### Ecosystem


#### Language versions