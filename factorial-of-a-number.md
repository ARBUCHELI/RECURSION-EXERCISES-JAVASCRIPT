# FACTORIAL OF A NUMBER.

## Returns the product of a given number from 1 to N.

```
function factorial(number) {
    if (number===1) {
        return 1;
    }
    return number*factorial(number-1);
}

factorial(3);
```
