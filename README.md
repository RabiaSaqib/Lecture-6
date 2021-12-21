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

    
    
    
    //Else if statements
#include <iostream>
#include <string>

using namespace std;

int main()
{

    bool monday = true;
    bool sunday = false;
    if (monday == true)
    {
        cout << "Set alarm for 10 gotta be in CodeLab 1" << endl;
    }
    else if (sunday == true) {
        cout << "Set alarm for 10 gotta be in CodeLab 1" << endl;
    }
    else
    {
        cout << "No session for codelab 1" << endl;
    }
    return 0;
}

    
    
    
    
    
//Multiple Else IF statement

#include <iostream>
#include <string>

using namespace std;

int main()
{

    bool sunday = true, monday = false, tuesday = false, wednesday = false, thursday = false;
    if (sunday == true) {
        cout << "Set alarm for 10 gotta be in CodeLab 1 session" << endl;
    }
    else if (monday == true) {
        cout << "Set alarm for 10 gotta be in CodeLab 1 session" << endl;
    }
    else if (tuesday == true) {
        cout << "No session for CodeLab1 ;Check timetable for other modules" << endl;
    }
    else if (wednesday == true) {
        cout << "No session for CodeLab1 ;Check timetable for other modules " << endl;
    }
    else if (thursday == true) {
        cout << "No session for CodeLab1 ;Check timetable for other modules " << endl;
    }
    else {
        cout << "Must be the weekend :Holiday Time" << endl;
    }
    return 0;
}

    
    
    
    //EXERCISE IT'S my birthday

#include <iostream>
#include <string>
using namespace std;

int main()
{

    bool myBirthday = true;
    int age = 18;
    if (myBirthday == true) {
        age++;
        cout << "It is my birthday. I am " << age << " years old" << endl;
    }
    else {
        cout << "It is not my birthday" <<endl;
    }
    return 0;
}

    
    
    #include<iostream>
using namespace std;
int main()
{
	cout << "Enter the time in 24 hour pattern to see whether it Morning, Afternoon, Evening or Night\n";
	double time;
	cin >> time;
	if (time < 12)
	{
		cout << "Good Morning";
	}
	else if (time >= 12 && time < 18)
	{
		cout << "Good Afternoon";
		}
	else if (time >=18 && time < 21)
	{
		cout << "Good Evening";
	}
	else if (time >=21 && time <24)
	{
		cout << "Good Night";
	}
	else
	{
		cout << "Incorrect input";
    }
}
                
                
                
 // Exercise I can VOTE
#include <iostream>
using namespace std;

int main()
{
    cout << "Kindly enter your age to see whether you can vote or not!\n";
    int age;
    cin >> age;
    if (age >= 18)
    {
        cout << "You can vote";

    }
    else
    {
        cout << "Sorry not today";
    }
    return 0;
}


    
    
    
    
    
   // Exercise ODD or EVEN 

#include <iostream>
using namespace std;
int main()
{
    cout << "Enter the number to see whether its even or odd" << endl;
    int number;
    cin >> number;
    if (number % 2 == 0)
    {
        cout << "The entered number is Even" << endl;
    }
    else if (number % 2 != 0)
    {
        cout << "The number entered is odd" << endl;
    }
    else
    {
        cout << "Incorrect" << endl;
    }
    return 0;
}

  
    
    
    //EXERCISE NUMBER CHECKER

#include <iostream>
using namespace std;
int main()
{
    cout << "Enter the number to see whether its positive, negative or zero" << endl;
    double number;
    cin >> number;
    if (number == 0)
    {
        cout << "The number you entered is zero" << endl;
    }

    else  if (number > 0)
    {
        cout << "The number you entered is positive" << endl;
    }
    else  if (number < 0)
    {
        cout << "The number you entered is negative" << endl;

    }
    else(number != 0); 
    {
        cout << "Incorrect input" << endl;
    }
    return 0;
}

                                         
                                         
                                         
                                         
  //EXERCISE PROFIT / LOSS
#include<iostream>
using namespace std;
int main()
{
    double Purchase;
    double sale;

    cout << "Enter the purchase price: " << endl;
    cin >> Purchase;
    cout << "Enter the sale price: " << endl;
    cin >> sale;
    int x;
    x = sale - Purchase;
    if (x > 0)
    {
        cout << "You have a Profit of " << x << endl;
    }
    else if (x < 0) // For loss
    {
        cout << "You had a Loss of " << x << endl;
    }
    else if (x == 0)
    {
        cout << "No loss no profit." << endl;
    }
    else
    {
        cout << "Incorrect input";
    }
    return 0;
}

                
  //EXERCISE ENTER THE SHAPES        
#include <iostream>
#include <string>
using namespace std;
int main()
{
    double side;
    cout << "Enter the sides number to see the shape name (minimum 3 sides, maximum 10) " << endl;
    cin >> side;

    if (side <= 2)
    {
        cout << "You enter 2 as side, which is incorrect input" << endl;
    }
    else if (side == 3)
    {
        cout << "Triangle  has " << side << " sides" << endl;
    }
    else if (side == 4)
    {
        cout << "Square | Rectangle has " << side << " sides" << endl;
    }
    else if (side == 5)
    {
        cout << "Pentagon has " << side << " sides" << endl;
    }
    else if (side == 6)
    {
        cout << "Hexagon have " << side << " sides" << endl;

    }
    else if (side == 7)
    {
        cout << "Hepaton have " << side << " sides" << endl;

    }
    else if (side == 8)
    {
        cout << "Octagon have " << side << " sides" << endl;

    }

    else if (side == 9)
    {
        cout << "Nonagon have " << side << " sides" << endl;

    }
    else if (side == 10)
    {
        cout << "Decagon have " << side << " sides" << endl;

    }
    else
    {
        cout << "Incorrect";

    }

    return 0;
}
             
                
                
                
                
                
                
                
                
                
                
                
                
                
                
                
                
                                         
                                         
                                         
                                         
                                         
                                         
                                         
                                         
                                         
                                         
                
           
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
