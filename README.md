# Vector Dot-Product Implementation

This repository contains the implementation of the **vector dot-product** algorithm in C++.

---

## Mathematical Expression
The dot product of two vectors **A** and **B** is defined as:  
$$A \cdot B = \sum_{i=1}^{n} A_i \times B_i$$

---

## Example Code
```cpp
#include <iostream>
#include <vector>
using namespace std;

int main() {
    vector<int> A = {1, 2, 3};
    vector<int> B = {4, 5, 6};
    int dot_product = 0;

    for (int i = 0; i < A.size(); ++i)
        dot_product += A[i] * B[i];

    cout << "Dot Product: " << dot_product << endl;
    return 0;
}
