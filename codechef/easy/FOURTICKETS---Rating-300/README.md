# FOURTICKETS - Rating 300

![Difficulty](https://img.shields.io/badge/Difficulty-Easy-green)

## Problem

_Description not available._

## Solution

**Language:** c_cpp  
**Runtime:** N/A  
**Memory:** N/A  
**Submitted:** 2026-10-06T05:27:59.627Z  

```c_cpp
#include <bits/stdc++.h>
using namespace std;

int main() {
	// your code goes here
int t;
cin>>t;
while(t--){
    int x,y;
    cin>>x>>y;
    if(y>x){
        cout<<"profit"<<endl;
    }
    else if(x>y){
        cout<<"loss"<<endl;
    }
    else{
        cout<<"neutral"<<endl;
    }
}
return 0;
}

```

---

[View on CodeChef](https://www.codechef.com/problems/FOURTICKETS)