[Problem Statement](https://www.hackerrank.com/challenges/30-data-types/problem)

### *Code*

``` c++
#include <iostream>
#include <iomanip>
#include <limits>

using namespace std;

int main() {
    int i = 4;
    double d = 4.0;
    string s = "HackerRank ";

    int i1;
    double d1;
    string s1;

    cin >> i1 >> d1;
    getline(cin >> ws, s1);

    cout << i + i1 << endl;
    cout << fixed << setprecision(1) << d + d1 << endl;
    cout << s + s1;

    return 0;
}

```

### Things I learned - 

1. `ws in getline` Extracts as many whitespace characters as possible from the current position in the input sequence. The extraction stops as soon as a non-whitespace character is found. These extracted whitespace characters are discarded. We can also use `cin.ignore()` instead of `ws`

2. `setprecision()` Setprecision when used along with `fixed` provides precision to floating point numbers correct to decimal numbers mentioned in the brackets of the setprecison.

**Note** - When the value mentioned in the setprecision() exceeds the number of floating point digits in the original number then 0 is appended to floating point digit to match the precision mentioned by the user. 