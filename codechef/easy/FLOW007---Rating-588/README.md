# FLOW007 - Rating 588

![Difficulty](https://img.shields.io/badge/Difficulty-Easy-green)

## Problem

### Reverse The Number

Given an Integer  **N**, write a program to reverse it.

### Input

The first line contains an integer  **T**, total number of testcases. Then follow  **T**  lines, each line contains an integer  **N**.

### Output

For each test case, display the reverse of the given number  **N**, in a new line.

### Constraints
- 1 ≤ T ≤ 1000
- 1 ≤ N ≤ 1000000
### Sample 1:
Input
Output

```
4
12345
31203
2123
2300
```

```
54321
30213
3212
32
```

## Solution

**Language:** c_cpp  
**Runtime:** N/A  
**Memory:** N/A  
**Submitted:** 2026-09-22T09:49:51.039Z  

```c_cpp
#include<bits/stdc++.h>
using namespace std;

int reverseNum(int n){
    int res = 0;
    while(n > 0){
        int d = n % 10;
        res = res * 10 + d;
        n /= 10;
    }
    return res;
}
int main() { 
    int t;
    cin >> t;
    while(t--){
        int n;
        cin >> n;
        cout << reverseNum(n) << endl;
    }
    return 0;
}

```

---

[View on CodeChef](https://www.codechef.com/problems/FLOW007)