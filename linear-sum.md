# LINEAR SUM.

## Sum all values from 0 to given number and display the result.

```
function sum(number) {
    if (number===0) {
        return 0;
    }
    return number + sum(number-1);
}

console.log(sum(3));
```

![image](https://user-images.githubusercontent.com/13010173/182546138-e7242f7f-7854-4e9e-9b95-41ec665d16f1.png)

