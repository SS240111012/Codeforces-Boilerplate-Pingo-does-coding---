# Some major things to consider before using the templates . 
you really want to learn the keybinds / macros before spamming "GGs" in the question Box of a live contest after Getting WA on Prtst 3 on Problem A.

------------------------

# Keybinds and Macros .

Macro / Alias	Meaning	Notes

- #define fast_io ios::sync_with_stdio(false); cin.tie(nullptr);	

-> Enables fast input/output	Essential for CP

- #define endl "\n"	

-> Faster line break	Avoids flushing buffer every time

- using ll = long long;	

-> Shortcut for 64-bit integers	Common CP habit

- #define T_small() / #define T_big()	

-> For test cases (int/long long)	Helps handle both small and big t

- void solve()	

-> Main logic function	Called per test case

- #include <bits/stdc++.h>	

-> Not used intentionally	Instead, all needed STL headers are manually imported
-----------------------------
 <vector>

   <map>, <set>, <unordered_map>, <unordered_set>

-> Containers	Standard for CP

- <queue>, <stack>, <deque>	

-> Data structures	Common for BFS/DFS

- <algorithm>, <numeric>	

-> for Sorting, accumulation, gcd/lcm etc.	
-----------------------------
- <cmath>	

-> Math functions	

- <complex>	

-> Complex numbers (rare use)	

- <sstream>, <regex>	

-> String parsing & regex	Advanced text processing

- <iomanip>	

-> for Formatting	For precision control in floating output

- <array>	

-> Fixed-size array alternative	Cleaner syntax than C-style arrays

- <bitset>	

-> Binary representation	Fun Easter egg 

- <limits>	

->For INT_MAX, LLONG_MAX etc.	



ll → for big integer values (1e9+7, 1e12, etc.)

fast_io → always use in contests to prevent TLE on I/O-heavy problems

solve() → your main function for logic

T_small() and T_big() → handles multiple test cases automatically

endl → used for speed over std::endl
