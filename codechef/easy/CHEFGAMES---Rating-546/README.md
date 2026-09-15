# CHEFGAMES - Rating 546

![Difficulty](https://img.shields.io/badge/Difficulty-Easy-green)

## Problem

_Description not available._

## Solution

**Language:** c_cpp  
**Runtime:** N/A  
**Memory:** N/A  
**Submitted:** 2026-09-15T08:48:38.248Z  

```c_cpp
#include <iostream>
using namespace std;

int main() {
	int t;
	cin>>t;
	while(t--){
	   int n,x;
	   cin>>n>>x;
	   if(n*x%4!=0)
	   cout<<((n*x)/4)+1<<endl;
	   else
	   cout<<(n*x)/4<<endl;
	}
	return 0;
}
```

---

[View on CodeChef](https://www.codechef.com/problems/CHEFGAMES)