This package (MIDR) calculates global edit distance and local edit distance.
how to use:
1. Import Midr class from midr package:
    ```from midr import Midr```
2. create object giving 4 parameters (M - match score, I - insert score, D - delete score, 
R - replace score, default: 0, 1, 1, 1 - Livenstein distance):
    ```obj = Midr(1, -1, -1, -1)```
3. Calculate distance between 2 strings:
    ```obj.global_edit_distance(word1, word2)```
    ```obj.local_edit_distance(word1, word2)```