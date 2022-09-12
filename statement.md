# Welcome!

This Python template lets you get started quickly with a simple one-page playground.

```python runnable
# A recursive function to find nth catalan number
def catalan(n):
    # Base Case
    if n <= 1:
        return 1
 
    # Catalan(n) is the sum of catalan(i)*catalan(n-i-1)
    res = 0
    for i in range(n):
        res += 
    #finish the missing code in the line above
    
    return res
 
 
# Driver Program to test above function
for i in range(15):
    print(catalan(i), end=' ')
```

# Advanced usage

If you want a more complex example (external libraries, viewers...), use the [Advanced Python template](https://tech.io/select-repo/429)
