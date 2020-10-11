[Problem Statement](https://www.hackerrank.com/challenges/30-hello-world/problem)

### *Code*

``` c++
#include <bits/stdc++.h>
using namespace std;

int main()
{
    string input_string;
    getline(cin, input_string);
    cout << "Hello, World." << endl;
    cout << input_string;

    return 0;
}

```

### Things I learned - 

`getline(cin, var` is used to get a string until it stopped, like if use cin then it will stopped if it encounter a whiesapce or enter.