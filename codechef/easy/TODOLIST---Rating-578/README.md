# TODOLIST - Rating 578

![Difficulty](https://img.shields.io/badge/Difficulty-Easy-green)

## Problem

_Description not available._

## Solution

**Language:** c_cpp  
**Runtime:** N/A  
**Memory:** N/A  
**Submitted:** 2026-09-18T10:26:31.002Z  

```c_cpp
#include <bits/stdc++.h>
using namespace std;

int main() {
	int t,a,b,c,d;
	cin>>t;
	
	while(t--){
	    cin>>a>>b>>c>>d;
	    if(a+b+c<d || b+c+d<a || c+d+a<b || a+b+d<c){
	        cout<<"YES"<<endl;
	    }else{
	        cout<<"NO"<<endl;
	    }

	}

}

```

---

[View on CodeChef](https://www.codechef.com/problems/TODOLIST)