# VARDIGS

![Difficulty](https://img.shields.io/badge/Difficulty-Medium-yellow)

## Problem

### Varied Digits

A $2$-digit integer is called  *varied*  if it contains two  **different**  digits.

You are given a $2$-digit integer $X$. Decide if $X$ is  *varied*  or not.

### Input Format
- The only line of input will contain a single $2$-digit integer, $X$.
### Output Format

Output the string `Yes` if $X$ is  *varied*  and `No` otherwise.

Each character of the output can be printed in either uppercase or lowercase, i.e. the strings `NO`, `No`, `nO`, and `no` will be considered equivalent.

### Constraints
- $10 \le X \le 99$
### Sample 1:
Input
Output

```
22

```

```
No
```

### Explanation:

$22$ has two equal digits $2$ and $2$, so it's not  *varied*.

### Sample 2:
Input
Output

```
48

```

```
Yes
```

### Explanation:

$48$ has two different digits $4$ and $8$, so it is  *varied*.

## Solution

**Language:** c_cpp  
**Runtime:** N/A  
**Memory:** N/A  
**Submitted:** 2026-10-02T19:08:14.747Z  

```c_cpp
#include <bits/stdc++.h>
using namespace std;

int main() {
	// your code goes here
	int a;
	cin>>a;
	int tens = a/10;
	int ones = a%10;
	if(tens!=ones)
	cout<<"yes"<<endl;
	else
	cout<<"no"<<endl;
	return 0;

}

```

---

[View on CodeChef](https://www.codechef.com/problems/VARDIGS)