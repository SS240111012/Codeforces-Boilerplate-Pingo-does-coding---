# ⚙️ Some Major Things to Consider Before Using the Templates

You really want to learn the **keybinds / macros** before spamming `"GGs"` in the question box of a live contest after getting **WA on Pretest 3** of Problem A (lmao). 

---

## Keybinds and Macros

| Macro / Alias | Meaning | Notes |
|----------------|----------|-------|
| `#define fast_io ios::sync_with_stdio(false); cin.tie(nullptr);` | Enables fast input/output | Essential for CP |
| `#define endl "\n"` | Faster line break | Avoids flushing buffer every time |
| `using ll = long long;` | Shortcut for 64-bit integers | Common CP habit |
| `#define T_small()` / `#define T_big()` | For test cases (int / long long) | Helps handle both small and big `t` |
| `void solve()` | Main logic function | Called per test case |
| `#include <bits/stdc++.h>` | Not used intentionally | Instead, all needed STL headers are manually imported |

---

## STL Headers You’ll Commonly Need more than your urge to goon.

| Header | Purpose | Notes |
|---------|----------|-------|
| `<vector>` | Dynamic arrays | Must-have |
| `<map>`, `<set>`, `<unordered_map>`, `<unordered_set>` | Containers | Standard for CP |
| `<queue>`, `<stack>`, `<deque>` | Data structures | Common for BFS/DFS |
| `<algorithm>`, `<numeric>` | Sorting, `accumulate`, `gcd/lcm`, etc. | Core utilities |
| `<cmath>` | Math functions | For sqrt, pow, abs, etc. |
| `<complex>` | Complex numbers | Rare use |
| `<sstream>`, `<regex>` | String parsing & regex | Advanced text ops |
| `<iomanip>` | Formatting | For precision control in float outputs |
| `<array>` | Fixed-size array | Cleaner than C-style arrays |
| `<bitset>` | Binary representation | Bit-level fun or should I say hell ? |
| `<limits>` | For `INT_MAX`, `LLONG_MAX`, etc. | Range constants |

---

## 💡 Tips and tricks

- `ll` → for big integer values (`1e9+7`, `1e12`, etc.)
- `fast_io` → always use in contests to prevent TLE on I/O-heavy problems
- `solve()` → your main logic function per test case
- `T_small()` / `T_big()` → handles multiple test cases automatically
- `endl` → used for **speed**, not the default `std::endl`

---

🔥 **Pro tip:** Keep your template clean and minimal — the shorter it is, the faster you debug under pressure.
