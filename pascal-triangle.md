# PASCAL TRIANGLE

## Display Pascal’s triangular array of the binomial coefficients.

```
function pascal(row, column) {
    if (column>row) {
        return 0;
    }
    if (column<=1 || row<=1) {
        return 1;
    }
    return pascal(row-1, column) + pascal(row-1, column-1);
}

function triangle(number) {
    let string = "";
    for (let row=1; row<=number; row++) {
        for(let column=1; column<=row; column++) {
            string += `${pascal(row, column)} `;
        }
        string += "\n";
    }
    console.log(string);
}

triangle(4);
```
![1](https://user-images.githubusercontent.com/13010173/182797352-befcb6c8-5fb4-4484-993b-6274578b0b91.jpg)

![2](https://user-images.githubusercontent.com/13010173/182797388-16c13690-b68b-4782-8b43-2f7fb133e7fd.jpg)

![3](https://user-images.githubusercontent.com/13010173/182797417-917fe01e-c6c6-4d63-afea-b88c97eac632.jpg)

![4](https://user-images.githubusercontent.com/13010173/182797457-8b7a11ba-756b-4f56-8135-62d35f4be0ab.jpg)

![5](https://user-images.githubusercontent.com/13010173/182797498-d099c288-2ea5-456a-9180-31c9d6d2b308.jpg)

![6](https://user-images.githubusercontent.com/13010173/182797527-16bfa03a-79cd-4fce-828b-752fdb270533.jpg)

![7](https://user-images.githubusercontent.com/13010173/182797556-a17a9077-00bf-42c4-8702-514f44f5ab76.jpg)

![8](https://user-images.githubusercontent.com/13010173/182797586-4615fde4-dd42-457c-8af0-1445615883c5.jpg)

![9](https://user-images.githubusercontent.com/13010173/182797618-5b208b4f-386d-46c7-90b7-33c1fbf2bc48.jpg)

![10](https://user-images.githubusercontent.com/13010173/182797645-daf6dbe6-a4c0-4b08-8e62-b1535126c5e4.jpg)

![11](https://user-images.githubusercontent.com/13010173/182797679-ed2b157c-ce50-4d6e-8e31-607e818e4f51.jpg)

![12](https://user-images.githubusercontent.com/13010173/182797703-fae91af5-700c-47f2-8ed5-be968f3fb129.jpg)

![13](https://user-images.githubusercontent.com/13010173/182797738-f6591199-fae0-4c27-ba81-b5676f87a501.jpg)

![14](https://user-images.githubusercontent.com/13010173/182797763-f220f42e-d406-43fe-a54b-4e53c1001b1e.jpg)

![15](https://user-images.githubusercontent.com/13010173/182797792-7eed7275-7a0a-4e50-ad5a-b7962374b40b.jpg)

![16](https://user-images.githubusercontent.com/13010173/182797820-166516a7-9e27-4a1a-9c96-0d3e14e1e151.jpg)

![17](https://user-images.githubusercontent.com/13010173/182797852-46670a08-afd9-41c4-923d-9c97b7cbf655.jpg)

![18](https://user-images.githubusercontent.com/13010173/182797882-60df45e6-39eb-4a88-bb61-498faec15fbb.jpg)

![19](https://user-images.githubusercontent.com/13010173/182797910-38b6e223-b534-4f77-b0bb-c85a6804f5e7.jpg)

![20](https://user-images.githubusercontent.com/13010173/182797943-138b2907-d648-4df8-8301-2d0a170e16c4.jpg)

![21](https://user-images.githubusercontent.com/13010173/182797971-537c9678-1ab0-405d-be79-6b2a34dd6b32.jpg)

![22](https://user-images.githubusercontent.com/13010173/182797991-1ed07abf-b248-447d-a2a5-ba3ca9405608.jpg)

![23](https://user-images.githubusercontent.com/13010173/182798020-3d852921-c545-4f14-be8f-4160d52b3e2f.jpg)

![24](https://user-images.githubusercontent.com/13010173/182798049-31b6e7a0-7f24-4bd5-9599-a3cbd92ecb5c.jpg)

![25](https://user-images.githubusercontent.com/13010173/182798090-e9c1cbce-6120-4070-b0d2-faf8ab65f82b.jpg)

![26](https://user-images.githubusercontent.com/13010173/182798128-3311ed81-835d-41f6-9389-3794418205af.jpg)

![27](https://user-images.githubusercontent.com/13010173/182798166-4ced5d93-21f0-400c-9420-c24a883c34b2.jpg)

![28](https://user-images.githubusercontent.com/13010173/182798201-23e3c650-3788-4b14-9e63-53cda8a35aad.jpg)

![29](https://user-images.githubusercontent.com/13010173/182798265-e45d5569-2ce3-4c19-8fd6-05546b842ec6.jpg)

![30](https://user-images.githubusercontent.com/13010173/182798295-333a4227-6e7c-47f9-91dd-ed913b129587.jpg)

![31](https://user-images.githubusercontent.com/13010173/182798347-a0a68711-3a68-4121-9632-7df317fc9a3c.jpg)

![32](https://user-images.githubusercontent.com/13010173/182798375-f320044f-fb16-44f1-9667-716683d70463.jpg)

![33](https://user-images.githubusercontent.com/13010173/182798396-09844a41-f6a2-4145-ab26-26790a4d9e0f.jpg)

![34](https://user-images.githubusercontent.com/13010173/182798433-ee4b1aa0-abd3-4ce2-829b-39e4756e636b.jpg)

![35](https://user-images.githubusercontent.com/13010173/182798454-fffbf18e-1bd5-4c0d-a080-f6a2f753acc3.jpg)



