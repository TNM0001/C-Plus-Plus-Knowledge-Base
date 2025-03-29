A **char** is a single character (For example: 1, 6, %, b, p, ., T, etc.)

The string type in C++ is a sequence of characters that can hold multiple chars.

To use strings in C++, you **must** include this at the top of your code:

```cpp
#include <string>
```

**Note: While your code might work without** `#include <string>` **(because other headers like** `<iostream>` **might include it indirectly), it's considered bad practice to rely on indirect includes. Always explicitly include the headers you use directly in your code.**

You **also** need to handle the namespace in one of these two ways:

1. Add this line after your `includes`:

```cpp
using namespace std;
```

2. Don't add the `using namespace` line, but prefix string with `std::`:

```cpp
std::string s1 = "This is a string";// This works because we explicitly used std::
```

Notice that the string variable uses **double quotation marks.** In the above example, a string variable named s1 is initialized.

Both methods require `#include <string>`. The only difference is whether you want to write `std::` before `string` or not.

Here's a complete example:

```cpp 
#include <string>
using namespace std;  // Method 1

int main() {
    string s1 = "Hello";  // Method 1 style
    std::string s2 = "Hello again";  // Method 2 style (still works even with 'using namespace')
    return 0;
}
```
