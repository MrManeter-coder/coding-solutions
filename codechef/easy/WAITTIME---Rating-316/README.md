# WAITTIME - Rating 316

![Difficulty](https://img.shields.io/badge/Difficulty-Easy-green)

## Problem

_Description not available._

## Solution

**Language:** c_cpp  
**Runtime:** N/A  
**Memory:** N/A  
**Submitted:** 2026-09-12T18:08:03.954Z  

```c_cpp
#include <iostream>
using namespace std;

int main() {
    int A, B, X, Y;
    cin >> A >> B >> X >> Y;

    int messi = 2 * A + B;
    int ronaldo = 2 * X + Y;

    if (messi > ronaldo)
        cout << "Messi";
    else if (ronaldo > messi)
        cout << "Ronaldo";
    else
        cout << "Equal";

    return 0;
}
```

---

[View on CodeChef](https://www.codechef.com/problems/WAITTIME)