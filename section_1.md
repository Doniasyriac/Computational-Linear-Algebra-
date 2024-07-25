##pseudocode for linear algrbra
The following 'pseudocode'shows how to solve a system of linear equations
```python
  FUNCTION Solution(A,b):
    create augmented matrix:k=[A|b]
    reduce in row reduce echleon form
    Rank=number of non-zero rows of RREf
    if Rank(K)!=Rank(A):
      print(system is inconsistent)
    ELSE IF
       solve using both substitution
END FUNCTION
