//using functions for factorial of a number.

#include <iostream>
using namespace std;

int factorial(int);

int main(int argc, const char * argv[]) {
    int num1;
    cout<<"enter a number";
    cin>>num1;
    cout<<factorial(num1);

    return 0;
}

int factorial(int num1)
{ int factorial=1;
    while (num1>0)
    {
        factorial=factorial*num1;
        num1--;
    }
    return factorial;
}
