# NUMBER EXPONENT (POWER).

## Returns the value of exponent operation from given number and grade.

```
function pow(number, power) {
    if (power===1) {
        return number;
    }
    return number * pow(number, power-1);
}

pow(2,2);
```
![1](https://user-images.githubusercontent.com/13010173/182785708-3d38199d-8891-44aa-bce0-54d770e94fe9.jpg)

![2](https://user-images.githubusercontent.com/13010173/182785899-a8b140d6-a7bf-4a29-ac0d-11f082023bd8.jpg)

![3](https://user-images.githubusercontent.com/13010173/182786221-5fde66f5-9813-40ae-acf8-7b4a5a89256c.jpg)

![4](https://user-images.githubusercontent.com/13010173/182786375-8246fa50-eabf-485f-b687-81f5ecc02380.jpg)
