# SNDMAX - Rating 299

![Difficulty](https://img.shields.io/badge/Difficulty-Easy-green)

## Problem

_Description not available._

## Solution

**Language:** c_cpp  
**Runtime:** N/A  
**Memory:** N/A  
**Submitted:** 2026-09-12T17:33:25.930Z  

```c_cpp
#include <iostream>
using namespace std;

int main() {
    int T;
    cin >> T;

    while (T--) {
        int N, X;
        cin >> N >> X;

        if (X >= N)
            cout << "YES" << endl;
        else
            cout << "NO" << endl;
    }

    return 0;
}
```

---

[View on CodeChef](https://www.codechef.com/problems/SNDMAX)