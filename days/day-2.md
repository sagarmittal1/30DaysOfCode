[Problem Statement](https://www.hackerrank.com/challenges/30-operators/problem)

### *Code*
Here are the two solutions that I find out
``` c++
#include <bits/stdc++.h>

using namespace std;

// Complete the solve function below.
void solve(double meal_cost, int tip_percent, int tax_percent) {
    double tip, tax, total;
    
    tip = (meal_cost * tip_percent) / 100;
    tax = (meal_cost * tax_percent) / 100;
    total =  meal_cost + tip + tax;

    cout << round(total);

}

int main()
{
    double meal_cost;
    int tip_percent;
    int tax_percent;

    cin >> meal_cost >> tip_percent >> tax_percent;

    solve(meal_cost, tip_percent, tax_percent);

    return 0;
}
```

``` C++
#include <bits/stdc++.h>
using namespace std;

int main()
{
	double meal_cost;
	int tip_percent;
	int tax_percent;

	cin >> meal_cost >> tip_percent >> tax_percent;

	double tip = (meal_cost * tip_percent) / 100;
	double tax = (meal_cost * tax_percent) / 100;
	double total = meal_cost + tip + tax;

	cout << round(total);


	return 0;
}
```

### Things I learned - 

`round(var)` - rounds the numbere to the nearest integer useful for finding price etc