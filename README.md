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
## Picture
![alt.txt](https://cdn1.byjus.com/wp-content/uploads/2018/11/maths/2016/06/02115120/Dot-Product-Of-Vectors.jpg)

## Table Showing comparison
> |version|Time complexity|Space Complexity| Remarks|
> |---|---|---|---|
> |v1|O(1)|O(1)|Basic implementation|
> |v2|O(1)|O(1)|optimized using numpy|
> |v3|O(1)|O(1)|parallel computation|

1.**Headings:**
   - Use `#` for the main title (`Vector Dot-Product Algorithm`) and `##` for subsections like `Mathematical Expression`, `Example Code`, `Diagram`, etc.

2.**Styling:**
   - Use `**` for bold text, e.g., **A** and **B**
   - Use `*` or `_` for italics

**3.Quoting text:**
- Use `>` for blockquotes.eg.
> this is blockquote.

**4.Link:**
- use '\[]()' for link.eg
[this is link](https://www.google.com/)

**5.Images:**
- use '!\[]()' for image.eg
![alt text](https://cdn1.byjus.com/wp-content/uploads/2018/11/maths/2016/06/02115120/Dot-Product-Of-Vectors.jpg)

**6.Lists (along with task lists):**
-  Use `-` or `1.` for unordered or ordered lists.

**7.Footnotes:**

 - Footnotes example.
     ```
     [1]: Reference
     ```
**8.Alerts:**
 - Use blockquotes for alerts and warnings,
 > alert

 **9.Tables:**
 - Use `|` to create tables.eg.

 |version|Time complexity|Space Complexity| Remarks|
 |---|---|---|---|

 **10.Code:**
 - use '\```' for code.eg.

 ```python
def dot_product(A, B):
    return sum(a * b for a, b in zip(A, B))

A = [1, 2, 3]
B = [4, 5, 6]
print(dot_product(A, B))  # Output: 32
```

