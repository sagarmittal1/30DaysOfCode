# Day 7: Arrays

[Problem Statement](https://www.hackerrank.com/challenges/30-arrays/problem)

### **Code**

``` c++
#include <bits/stdc++.h>
using namespace std;

int main()
{
    int n;
    cin >> n;
    int arr[n];

    for (int i = 0; i < n; i++) {
        cin >> arr[i];
    }

    for (int i = n - 1; i >= 0; i--) {
        cout << arr[i] << " ";
    }

    return 0;
}
```

### Things I learned - 

This problem can also be solved using vector but I don't know why I took so, much time in solving with just arrays. This shows that I need more practice otherwise I will never be so good in it.