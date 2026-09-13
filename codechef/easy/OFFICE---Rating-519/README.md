# OFFICE - Rating 519

![Difficulty](https://img.shields.io/badge/Difficulty-Easy-green)

## Problem

_Description not available._

## Solution

**Language:** c_cpp  
**Runtime:** N/A  
**Memory:** N/A  
**Submitted:** 2026-09-13T10:12:14.734Z  

```c_cpp
#include <bits/stdc++.h>
using namespace std;

int main() {
	int t;
	float x, y,z;
	cin>>t;
	while(t--){
	    cin>>x>>y>>z;
	    if(((x*y)/2.0)<z){
	        cout<<"YES"<<endl;
	    }else{
	        cout<<"NO"<<endl;
	    }
	}

}

```

---

[View on CodeChef](https://www.codechef.com/problems/OFFICE)