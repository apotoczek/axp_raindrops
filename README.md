# axp_raindrops

Convert a number into a string per below instructions from CLI.

Usage:
```
$ python raindrops.py
Enter an integer: 30
PlingPlang
```

```
$ pytest test_raindrops.py
============================================================ test session starts =============================================================
platform darwin -- Python 3.8.2, pytest-6.2.5, py-1.10.0, pluggy-1.0.0
rootdir: /Users/axp/git/axp_raindrops
collected 4 items

test_raindrops.py ....                                                                                                                 [100%]

============================================================= 4 passed in 0.02s ==============================================================
```

Requirements:
```
Python 3.4+
pytest
```

### Kata Instructions

Your task is to convert a number into a string that contains raindrop sounds corresponding to certain potential factors. A factor is a number that evenly divides into another number, leaving no remainder. The simplest way to test if a one number is a factor of another is to use the modulo operation.

*The rules of raindrops are that if a given number:*

- has 3 as a factor, add 'Pling' to the result.
- has 5 as a factor, add 'Plang' to the result.
- has 7 as a factor, add 'Plong' to the result.
- does not have any of 3, 5, or 7 as a factor, the result should be the digits of the number.

### Kata Examples

- 28 has 7 as a factor, but not 3 or 5, so the result would be "Plong".
- 30 has both 3 and 5 as factors, but not 7, so the result would be "PlingPlang".
- 34 is not factored by 3, 5, or 7, so the result would be "34".