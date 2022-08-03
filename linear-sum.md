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
![1](https://user-images.githubusercontent.com/13010173/182546518-52b36c67-2fd8-4130-ae83-923527ccdc20.jpg)
