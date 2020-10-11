[Problem Statement](https://www.hackerrank.com/challenges/30-loops/problem)

### **Code**

``` c++
#include <bits/stdc++.h>
using namespace std;

int main()
{
    int n;
    cin >> n;
    int multiply = 0;

    for (int i = 1; i <= 10; i++) {
        multiply = n * i;
        cout << n << " x " << i << " = " << multiply << endl;
    }

    return 0;
}
```

### Things I learned - 

Just about printing table using for loop. Missed that same assignment in college lab so, do today :smirk: