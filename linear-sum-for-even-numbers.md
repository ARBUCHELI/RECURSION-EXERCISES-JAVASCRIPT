# LINEAR SUM.

## Sum all values from 0 to given number and display the result.

```
function sumEven(number) {
    if (number===0) {
        return 0;
    } else if (number%2 !== 0) {
        return sumEven(number-1);
    }
    return number + sumEven(number-1);
}

console.log(sumEven(7));
```
![1](https://user-images.githubusercontent.com/13010173/182549628-21a656e6-5dd4-4042-96a1-99ff2316e171.jpg)

![2](https://user-images.githubusercontent.com/13010173/182550046-fe405ce6-1d04-4c49-b904-d5231b983983.jpg)

![3](https://user-images.githubusercontent.com/13010173/182550092-72629c99-f972-4771-954d-1611c2cee73c.jpg)

![4](https://user-images.githubusercontent.com/13010173/182550614-516ceb30-4d0c-4167-ab40-2fa62c949b5e.jpg)

![5](https://user-images.githubusercontent.com/13010173/182550748-d7a7d72f-61bc-4847-81b6-11bf87265e3a.jpg)

![6](https://user-images.githubusercontent.com/13010173/182550909-8d6d0310-d240-464b-8051-b8831891c7ff.jpg)

![7](https://user-images.githubusercontent.com/13010173/182551047-1d0e723e-65ab-4194-9907-754f9cdeec3e.jpg)

![8](https://user-images.githubusercontent.com/13010173/182551238-80a2448a-a92b-4b13-b2ab-b1bcbea88219.jpg)

![9](https://user-images.githubusercontent.com/13010173/182551530-6563b131-7e09-4754-901c-482e70ea8b38.jpg)

