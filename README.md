# Summary App "Money Transfer"

## Definition

Code Define Money.java
int curren balance =2_000_000_000
int transfer = 500_000_000
int total = current + transfer

Expected result: 2 500 000 000

Actual result: -1794967296

Expected result is not as actual. 


## Tests

Positive testing:

2_000_000_000+500_000_000=2 500 000 000

## Результаты

1. 100% failed test
2. https://github.com/alicenetologia/leccion2_task1/issues/1


## Recomendation

For large numbers Uue type long instead type int 