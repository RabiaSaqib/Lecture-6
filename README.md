# Lecture-6
//What si the value of a Part -a
#include <iostream>
#include <string>

using namespace std;

int main()
{
    int a = 3;
    int b = 4;
    int c = 5;
    b = c;
    a = b;
    cout << a << endl;



    //Value of a Part - b

    int a1 = 3;
    int b1 = 3;
    int c1 = 4;
    c1 = b1;
    b1 = a1;
    a1 = c1;
    cout << a1 << endl;

    //value of a Part - c
    double a2 = 3.0;
    double b2 = 6.0;
    double c2 = b2 / a2;
    a2 = c2;
    cout << a2 << endl;

    //Value of a Part - d

    int a3 = 1;
    int b3 = 4;
    a3 = a3 * b3;

    cout << a3 << endl;

    //Value of a Part - e
    int a4 = 3;
    int b4 = 2;
    a4 = a4 % b4;
    cout << a4 << endl;
    return 0;
}

