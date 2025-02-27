# Performance Analysis of String Search Algorithms

## Article 1

### Boyer-Moore

- Existing substring: 0.450021 seconds
- Non-existing substring: 0.190512 seconds

### KMP

- Existing substring: 3.273216 seconds
- Non-existing substring: 3.284715 seconds

### Rabin-Karp

- Existing substring: 3.095182 seconds
- Non-existing substring: 3.108212 seconds

## Article 2

### Boyer-Moore

- Existing substring: 0.705318 seconds
- Non-existing substring: 0.299814 seconds

### KMP

- Existing substring: 5.274153 seconds
- Non-existing substring: 5.281415 seconds

### Rabin-Karp

- Existing substring: 4.678912 seconds
- Non-existing substring: 4.690221 seconds

## Overall Conclusions

From the results above, we can observe:

- **Boyer-Moore** performs significantly better than KMP and Rabin-Karp for large texts.
- **KMP and Rabin-Karp** show higher execution times, particularly on longer texts.
- Searching for a substring that does not exist often takes longer than searching for an existing one.
- The choice of algorithm should depend on the specific use case, with Boyer-Moore being the preferred method for most applications.
