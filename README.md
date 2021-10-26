# Enron Personalization Validation Set

The data collected here is email text taken from the [Enron email dataset](https://www.cs.cmu.edu/~./enron/), assembled in such a way that all text in a single file was written by the same author, organized chronologically.  Files are organized into dev (45 author) and test (44 author) partitions, and into separate text and metadata files for each author.

The data was originally assembled and used for evaluation of personalization methods in [Fowler et al. (2015)](https://dl.acm.org/doi/pdf/10.1145/2702123.2702503), citation below. If you use this data, please cite that paper. Supplementary material for that paper (available [here](https://dl.acm.org/doi/10.1145/2702123.2702503)) details the preprocessing that was done to produce the data, including: restriction of message to those in sent directories; removal of forwarded/replied-to messages and signatures at bottom of emails; duplicate removal; heuristics to remove non-user-generated content; whitespace and linebreak normalization; and simple sentence segmentation.  We refer the reader to the supplementary material for further details.

We follow the [policy](https://www.cs.cmu.edu/~./enron/DELETIONS.txt) of the Enron email dataset of removing author emails if requested by the authors. This led to emails from one individual being removed from the test partition that were included in the original paper.

This dataset is being released for benchmarking purposes only.  Given the paucity of useful comparable benchmarks in this space, we are releasing this dataset despite reservations about how the original dataset was constructed. We ask that users of this dataset use it only for benchmarking purposes, as that's our intention in its release.

Any third party content or data is provided "As Is" without any warranty, express or implied.

## Reference:

```bibtex
  @inproceedings{fowler-etal-2015,
      author    = {Andrew Fowler and Kurt Partridge and Ciprian Chelba and Xiaojun Bi and Tom Ouyang and Shumin Zhai},
      title     = {Effects of Language Modeling and its Personalization on Touchscreen Typing Performance},
      booktitle = {Proceedings of the 33rd ACM SIGCHI Conference on Human Factors in Computing Systems},
      doi       = {10.1145/2702123.2702503},
      isbn      = {978-1-4503-3145-6},
      pages     = {649--658},
      publisher = {ACM},
      address   = {Seoul, Korea},
      year      = {2015},
  }
```

## Contacts

- roark [at] google.com
- agutkin [at] google.com
