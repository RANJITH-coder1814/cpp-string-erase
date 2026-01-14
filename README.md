# cpp-string-erase
This repository contains a simple C++ program that demonstrates the use of the string::erase() function. The program clears all characters from a string and prints the result. It is a beginner-friendly example to understand C++ string manipulation using STL.
# 📌 C++ String erase() Example

This project demonstrates how to use the **`erase()`** function in C++ to remove all characters from a string.

---

## 🧠 Concept Used

- `std::string`
- `erase()` function
- Basic input/output using `cout`

---

## 🛠️ Program Code

```cpp
#include <iostream>
using namespace std;

int main() {
    string s = "ranjith";
    s.erase();
    cout << s << endl;
    return 0;
}
