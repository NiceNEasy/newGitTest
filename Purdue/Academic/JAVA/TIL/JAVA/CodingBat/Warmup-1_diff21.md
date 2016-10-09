

# Problem name : Warmup-1 > diff21 
Reference : [CodoingBat](http://codingbat.com/prob/p116624)

# Problem Details 
Given an int n, return the absolute difference between n and 21, except return double the absolute difference if n is over 21.

diff21(19) → 2,
diff21(10) → 11,
diff21(21) → 0


## My Work
```java
public int diff21(int n) {
  int res = 0;
  if (n > 21) {
    res = Math.abs(n-21);
    return res*2;
  } 
  else {
    res = Math.abs(n-21);
    return res;
  }
}
```

## Solution
```java
public int diff21(int n) {
  if (n <= 21) {
    return 21 - n;
  } else {
    return (n - 21) * 2;
  }
}
```


