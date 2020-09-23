usage: randl [-h] [-s SEED] file n

Retrieves a random sample of lines from a file.

positional arguments:
  file                  input file. If FASTA, will retrieve random
                        header/sequence pairs.
  n                     size of sample to retrieve.

optional arguments:
  -h, --help            show this help message and exit
  -s SEED, --seed SEED  seed value for the pseudo-random algorithm
