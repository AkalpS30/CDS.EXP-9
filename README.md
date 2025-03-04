# CDS.EXP-9
# EXP-9

## Aim:
**To study and implement C++ Pointer basics..**

## Software:
`Microsoft VSCode`

## Theory:
Pointers are symbolic representations of ddresses.
They enable programs to stimulate call-by-preference as well as to create and manipulate dynamic data structures.
Iterating over elements in arrays or other data structures is one of the main use of pointers.
The address of the variable that we are working with is assigned to the pointer variable that points to the same data type.
## Code: 9A
```
// Program to illustrate pointers. 

#include <bits/stdc++.h> 
using namespace std;
void geeks()
{
    int var = 5;

    int* ptr;                  // Declaring pointer variable. 

    ptr = &var;

    cout<<"Value at ptr = "<<ptr<<"\n";
    cout<<"Value at var = " <<var<<"\n";
    cout<<"Value at *ptr = "<<*ptr<<"\n";

}

// Driver Program 

int main()
{
    geeks();
    return 0;
} 
```
## Output:
![Output9A](https://github.com/user-attachments/assets/60a14e7a-de59-48e6-b7fd-fe0b466dde15)
## Code: 9B 
```
// Program to create one-dimensional array of pointers. 

#include <iostream> 
using namespace std; 

int main() 
{
    int* p=new int[7];  // Creating an array 

    for (int i=0; i<5; i++)  // Initializing the aray p[]
    {
        p[i]=10*(i+1);
    }

    cout<<*p<<"\n"; 
    cout<<*p+1<<"\n";
    cout<<*(p+1)<<"\n";
    cout<<2[p]<<"\n";
    cout<<p[2]<<"\n";
    *p++;

    cout<<*p;                 // Pointing to next location. 

    return 0; 
}
```
## Output:
![Output9B](https://github.com/user-attachments/assets/e0fdc7d4-131b-4e4e-89d4-e88f9a1be612)

### Conclusion:
Learnt about pointers in C++.
