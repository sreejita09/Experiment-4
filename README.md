# Experiment 4 

# Aim 
To study and implement C++ Bitwise Operators

# Theory 
Bitwise Operators are the operators that are used to perform operations on the bit level on the integers. While performing this operation integers are considered as sequences of binary digits. In C++, we have various types of Bitwise Operators.

Bitwise AND (&)
Bitwise OR (|)
Bitwise XOR (^)
Bitwise NOT (~)
Left Shift (<<)
Right Shift (>>)

# codes

~~~
#include<iostream>
using namespace std;

int main()
{
    int a,b;
    cout<<"enter the value of a ";
    cin>>a; 
    
    cout<<"enter the value of b: ";
    cin>>b; 

    cout<< "the bitwise AND is: "<<(a&b)<<endl;
    cout<< "the bitwise OR is: "<<(a|b)<<endl;
    cout<< "the bitwise XOR is: "<<(a^b)<<endl;
    cout<< "the bitwise NOT is: "<< (a-b)<<endl;
    cout<< "the bitwise LEFT SHIFT is: "<<(a<<b)<<endl;
    cout<< "the bitwise RIGHT SHIFT is: "<< (a>>b)<<endl;

    return 0; 
}

~~~

# output 
![image](https://github.com/user-attachments/assets/4310a960-c0ee-4d94-b0b0-5f7ea3443ca9)
