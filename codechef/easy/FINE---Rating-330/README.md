# FINE - Rating 330

![Difficulty](https://img.shields.io/badge/Difficulty-Easy-green)

## Problem

_Description not available._

## Solution

**Language:** c_cpp  
**Runtime:** N/A  
**Memory:** N/A  
**Submitted:** 2026-09-12T18:17:03.935Z  

```c_cpp
#include <iostream>
using namespace std;

int main() {
    int T;
    cin >> T;

    while (T--) {
        int A, B, C;
        cin >> A >> B >> C;

        if (A > B && A > C)
            cout << "Alice" << endl;
        else if (B > A && B > C)
            cout << "Bob" << endl;
        else
            cout << "Charlie" << endl;
    }

    return 0;
}
```

---

[View on CodeChef](https://www.codechef.com/problems/FINE)