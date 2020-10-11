[Problem Statement](https://www.hackerrank.com/challenges/30-conditional-statements/problem)

### **Code**

``` c++
#include <bits/stdc++.h>
using namespace std;

int main()
{
    int n;
    cin >> n;

    if (n % 2 == 0) {
        if (n >= 2 & n <= 5) {
            cout << "Not Weird";
        } else if (n >= 6 & n <= 20) {
            cout << "Weird";
        } else {
            cout << "Not Weird";
        }
    } else {
        cout << "Weird";
    }

    return 0;
}
```

### Things I learned - 

Nothing so much, but some use of if-else statement...