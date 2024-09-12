#include <iostream>
using namespace std;

class MyClass {
public:
    int x;

    // Constructor
    MyClass(int val) {
        x = val;
    }
};

int main() {
    MyClass obj(10);  // Create an object with value 10
    cout << obj.x;
    return 0;
}
