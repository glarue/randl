### Dependencies

This script needs the [biogl](https://github.com/glarue/biogl) module to function properly. If you use (or can get) `pip`, you can simply do

```python3 -m pip install biogl```

to add the package to a location reachable by your Python installation. 

Otherwise, you can clone the `biogl` repo and source it locally (to run from anywhere, you'll need to add it to your PYTHONPATH environmental variable, a process that varies by OS):

```git clone https://github.com/glarue/biogl.git```

### Usage info

```
usage: randl [-h] [-s SEED] file n

Retrieves a random sample of lines from a file.

positional arguments:
  file                  input file. If FASTA, will retrieve random
                        header/sequence pairs.
  n                     size of sample to retrieve.

optional arguments:
  -h, --help            show this help message and exit
  -s SEED, --seed SEED  seed value for the pseudo-random algorithm
```
