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
![1](https://user-images.githubusercontent.com/13010173/182547002-eb22608d-4770-4317-ba15-c7e116bbe89f.jpg)

![2](https://user-images.githubusercontent.com/13010173/182547034-b6291e12-fd11-413d-ab19-c850e404fff8.jpg)

![3](https://user-images.githubusercontent.com/13010173/182547072-cd61f43b-79f9-44f5-9824-203e5ac52134.jpg)

![4](https://user-images.githubusercontent.com/13010173/182547407-81788a27-c453-4362-936b-58302e3c06f6.jpg)

![5](https://user-images.githubusercontent.com/13010173/182547561-a7eb74f7-43ad-4a3f-96dd-f7e8367da3df.jpg)




