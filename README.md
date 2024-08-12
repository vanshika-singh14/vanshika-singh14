#include <iostream>
using namespace std;

int main() {
     int a,b;

    cout << "Enter the first number: ";
    cin >> a;

    cout << "Enter the second number: ";
    cin >> b;

    cout << "a = " << a << endl;
    cout << "b = " << b << endl;
    cout << "a & b = " << (a & b) << endl;
    cout << "a|b = " << (a | b) << endl;
    cout << "a ^ b = " << (a^b) << endl;
   cout << "a<< b = " << (a<<b) << endl;
    cout << "a>> b = " << (a>>b) << endl;
    return 0;
}

OUTPUT
Enter the first number: 1
Enter the second number: 0
a = 1
b = 0
a & b = 0
a|b = 1
a ^ b = 1
a<< b = 1
a>> b = 1
