# Hello World!

<!-- JUDGE_BADGE_START -->
![Judge Result](./badges/AC.svg)
<!-- JUDGE_BADGE_END -->

A fork-friendly sample online judge problem repository using GitHub Actions.

## Problem
Print the following line exactly.

```text
Hello, World!
```

## Input
There is no input.

## Output
Print the following line exactly.

```text
Hello, World!
```

## Notes
- Matching is line-sensitive.
- Extra spaces or a missing newline may cause `WA` depending on the checker.

## Submit your solution
1. Fork this repository.
2. Edit `solution.cpp`.
3. Commit and push to your fork.
4. Open the **Actions** tab or check the badge at the top of this README.

A correct example:

```cpp
#include <bits/stdc++.h>
using namespace std;

int main() {
    cout << "Hello, World!\n";
    return 0;
}
```

## Judge results
This template distinguishes:
- `AC` Accepted
- `WA` Wrong Answer
- `TLE` Time Limit Exceeded
- `MLE` Memory Limit Exceeded
- `RE` Runtime Error
- `CE` Compile Error

## Multiple test cases
This template supports multiple test cases by placing matching files in `tests/`:

- `input1.txt` / `output1.txt`
- `input2.txt` / `output2.txt`
- `input3.txt` / `output3.txt`
- ...

The workflow runs the submitted program once per input file.

## Limits
Default limits in the workflow:
- Time limit per test: 2 seconds
- Memory limit per test: 256 MB virtual address space

You can change these values in `.github/workflows/judge.yml`.
