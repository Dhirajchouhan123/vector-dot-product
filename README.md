# Vector Dot-Product Implementation

This repository contains the implementation of the **vector dot-product** algorithm in C++.

---

## Mathematical Expression
The dot product of two vectors **A** and **B** is defined as:  
**A ⋅ B = Σ (Aᵢ × Bᵢ) for i = 1 to n**

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
........
![image](https://github.com/user-attachments/assets/0e2c8bb7-ff5a-4332-b8a9-d98395c2fc18)

