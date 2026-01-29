# assignment-mariyamazeem2585
cout << "HOME ITEMS CONTROL SYSTEM" << endl;
cout << "1. Fan" << endl;
cout << "2. Light" << endl;
cout << "3. Refrigerator" << endl;
cout << "4. Air Conditioner" << endl;
cout << "5. Television" << endl;

cout << "\nEnter your choice (1-5): ";
cin >> choice;

cout << "Enter 1 to ON or 0 to OFF: ";
cin >> status;

if (choice == 1)
{
    if (status == 1)
        cout << "Fan is ON. Cooling the room." << endl;
    else
        cout << "Fan is OFF. Electricity saved." << endl;
}
else if (choice == 2)
{
    if (status == 1)
        cout << "Light is ON. Room is bright." << endl;
    else
        cout << "Light is OFF. Electricity saved." << endl;
}
else if (choice == 3)
{
    if (status == 1)
        cout << "Refrigerator is ON. Food is cooling." << endl;
    else
        cout << "Refrigerator is OFF. Food may spoil." << endl;
}
else if (choice == 4)
{
    if (status == 1)
        cout << "AC is ON. Room is cold." << endl;
    else
        cout << "AC is OFF. Power saved." << endl;
}
else if (choice == 5)
{
    if (status == 1)
        cout << "TV is ON. Enjoy watching." << endl;
    else
        cout << "TV is OFF. Screen is closed." << endl;
}
else
{
    cout << "Invalid choice!" << endl;
}

return 0;
# loop-program-
PROGRAM #1
#include <iostream>
using namespace std;
int main() {
for (int i = 1; i <= 4; i++) {
 for (int s = 4; s > i; s--) {
 cout << " ";
  }
 for (int j = 1; j <= i; j++) {
 cout << "*";
  }
cout << “\n;
 }
 return 0;
}
OUTPUT:
      *
    **
  ***
****
PROGRAM #2
#include <iostream>
using namespace std;
int main() {
 for (int i = 4; i >= 1; i--) {
 for (int j = 1; j <= i; j++) {
 cout << "* ";
}
 cout << endl;
 }
  return 0;
}
OUTPUT:
* * * *
* * *
* *
*




PROGRAM #3
#include <iostream>
using namespace std;
int main() {
 for (int i = 1; i <= 3; i++) {
 for (int j = 1; j <= 3; j++) {
 cout << "* ";
  }
  cout << endl;
  }
 return 0;
}
OUTPUT:
* * *
* * *
* * *
PROGRAM #4
#include <iostream>
using namespace std;
int main() {
for (int i = 2; i <= 4; i++) {
for (int j = 1; j <= i; j++) {
cout << "*";
}
cout << endl;
}
for (int i = 3; i >= 2; i--) {
for (int j = 1; j <= i; j++) {
cout << "* ";
 }
cout << endl;
  }
return 0;
}



OUTPUT:
**
***
****
***
**

PROGRAM #5
#include <iostream>
using namespace std;
int main() {
int n = 4;
for (int i = 1; i <= n; i++) {
for (int s = n; s > i; s--) {
 cout << " ";
}
for (int j = 1; j <= i; j++) {
cout << "* ";
}
cout << endl;
  }
for (int i = n - 1; i >= 1; i--) {
for (int s = n; s > i; s--) {
cout << " ";
}
 for (int j = 1; j <= i; j++) {
cout << "* ";
}
cout << endl;
}
return 0;
}
OUTPUT:
   *
  * *
 * * *
* * * *
 * * *
  * *
   *

# paper-solution
PAPER SOLUTION 
Here are complete solved answers for all questions from the exam paper
Q1. Match the C++ Statements with the Type of Error
    Column A (Code)	                                              Error Type
1.	cout "Hello";                   → a. Missing operator (<<)
2.	cin << a;                       → b. Wrong direction of extraction (should be cin >> a)
3.	int 2num = 5;                  → c. Invalid identifier name
4.	cout << "Hello\nWorld; → d. Missing quotation mark
5.	if(x>0); cout<<"Yes";      → e. Logical error (semicolon after if)
6.	cout << a + b >> c;          → f. Invalid operator usage

Q2. Write the Output of Conditional Statements (True/False)
Code	Output
1.	!(4 > 6)	                                True
2.	(12 >= 11)                              	True
3.	!(a != b)	                                False
4.	(12%3==0||12%5==0)                       	True 
	a=10,b=20,c=15;           
6.	(a>b&&a>c)                               	False
7.	(10!=5*2)                               	False
  
Q3. Data Types Selection
Value	Data Type
1. “25.75”	  string
2. 23	          int
3.'A'         	char
4. "Ali"	    string

Q4. Trace Output of Programs
1. Program
cout << "Hello\tWorld\n";
cout << "C++\\Program\nming";
cout << "C++\bProgramm\b\bing";
Output:
Hello      World
C++\Program
mingC+Programing
2. Program
int a = 10, b = 4;
cout << a % b;
Output:
2
3. Program
int x = 3;
x = x + 4;   // x = 7
cout << x + 2;
Output:
9
4. Program
int a = 2.3;
cout << a;
2.3 → stored as int → 2
Output:
2
5. Program
int x=3, y=4, z=5;

if(x>y)
 z += x;
else if(y > z)
 z = z - y;
else
 z = z * 2;
cout << z;
}
Output:
10
6. Program
int age;
cout << "Enter age: ";
cin >> age;
cout << "Your age is " << age;
Output:
(Depends on user input)
If input = 20:
Your age is 20
7. Program

if(a > 5)
cout << "A";
cout << "B";}
Output :
[Error] 'a' was not declared in this scope.
8. Program
int x = 2, y = 3, z = 4;
cout << x + y *z/x;
Output:
8
9. Program
int a = 5, b = 10;
cout << (a > b ? a : b);
a > b? → No → prints b = 10
Output:
10
10. Program
int x = 2, y = 3;
cout << (x+1 * y+1) + (y - 1);}
Output:
8
11. Program
float lrate = 10.5;
cout << lrate;
Output:
10.5

12. Program
if (a = 5) {
  cout << "Five";
}
Output:
[Error] 'a' was not declared in this scope
13.Program
int main(){
    int a;
    cout << a;
}
 Output: Garbage value
(Because a is declared but not initialized.)
14.Program
int main(){
    cout << "She said "Hello"";
}
Output:
[Error] expected ';' before 'Hello'

15.Program 
int main(){
    int  = 5;
}
 Output:
[Error] expected unqualified-id before '=' token
16.Program
int main(){
    int num = "5";
}
 Output:
 Error (Cannot assign a string "5" to an int.)
18.Program
int main(){
    cout << "Area = ";
    cout << “3.14*r*r”;
}
 Output:
Area = 3.14*r*r
19.Program
int main(){
    if(x > 0){
        cout << "Positive";
    }
}
Output:
 Error (x is not declared)
20.
int main(){
    cin >> number;
    if(number = 10)
        cout << "Equal";
}
Output:
Equal
Reason: number = 10 is assignment (NOT comparison). It always becomes true, so "Equal" prints.
21.
int main(){
    if(x > y)
        cout << "Greater";
    else if(x < y)
        cout << "Smaller";
}
Output:
(No output — x and y are not declared.)
21 (second one).
int main(){
    if(x < 5 && x > 2)
        cout << "Range";
}
 Output:
(No output — x is not declared.)
22.
int main(){
    int result = 10 / 2*;
}
 Output:
[Error] expected primary-expression before ';' token
23.
int main(){
    cout << 1 + 4 >> 7;
}
Output:
 Error
Because:
(1 + 4) >> 7 uses right shift operator incorrectly with cout.
24.
int main(){
    cout << "Path: C:\\newfolder";
}
 Output:
Path: C:\newfolder
Q5. Write the answer of following short Questions

1. Explain the difference between cin and cout in C++.
•	cin is used to take input from the user.
•	cout is used to display output on the screen.

2. What happens if a user inputs a value of the wrong data type using cin?
•	The input fails.
•	The variable keeps its previous (or default) value.
•	The program may skip further input statements.
•	The fail state is set (cin.fail()).

3. Differentiate between float and double.
Feature	float	double
Size	4 bytes	8 bytes
Precision	~6 digits	~15 digits
Accuracy	Less accurate	More accurate

4. What happens if you use an uninitialized variable in an expression?
•	It contains garbage (random) value.
•	The result of the expression becomes unpredictable.
•	It may cause logical errors.

5. What is an escape sequence in C++ and why is it needed?
•	An escape sequence starts with \ and represents special characters.
•	It is needed because some characters (like newline, tab, backslash) cannot be typed directly.
Example:
•	\n → new line
•	\t → tab
•	\\ → backslash

6. Why can't we simply press Enter inside a string to create a new line instead of using "\n"?
Because strings must be written on a single continuous line in code.
Pressing Enter would break the string and cause a compilation error.
So C++ uses \n to represent a new line.

7. Explain the purpose of the modulus (%) operator.
•	It gives the remainder after division.
Example: 10 % 3 = 1

8. Can else be used without a preceding if? Explain.
•	No, else cannot be used alone.
•	else always belongs to an if.
•	else is executed when the if condition is false.

9. What happens if you end an if condition with a semicolon?
Example:
if (a > 10);
    cout << "Hello";
•	The semicolon ends the if statement.
•	The next line runs unconditionally, not as part of the if.
•	This creates a logical error.

10. Explain the difference between == and = operators.
•	= is the assignment operator (stores value).
o	Example: a = 5;
•	== is the comparison operator (checks equality).
o	Example: a == 5

11. Can you combine multiple relational conditions in one expression? Give an example.
Yes, using logical operators like && (AND), || (OR).
Example:
if (age >= 18 && age <= 60)

12. What happens when operators have the same precedence?
•	The operators are evaluated based on associativity.
Example: For + and − (same precedence), evaluation is left to right.

13. Write the general syntax of the ternary operator and explain its components.
Syntax:
(condition) ? expression1 : expression2;
Components:
•	condition → checked first
•	expression1 → executed if condition is true
•	expression2 → executed if condition is false

14. What are the naming rules for identifiers in C++?
•	Must start with letter or underscore.
•	Cannot start with a number.
•	Can contain letters, numbers, and underscores.
•	No spaces or special characters.
•	Cannot be a keyword (like int, if, return)
Q.6Write a C++ program that checks whether a given year lies between 2000 and 2025. If the year is between 2000 and 2015 (inclusive), calculate and display the sum of 2000 and 2015. If the year is between 2016 and 2025 (inclusive), calculate and display the sum of 2016 and 2025. If the year is outside this range, display the message "Year is not in the range."
C++ Program
#include <iostream>
using namespace std;

int main() {
    int year;
    cout << "Enter a year: ";
    cin >> year;

    if (year >= 2000 && year <= 2015) {
        int sum = 2000 + 2015;
        cout << "Sum of 2000 and 2015 = " << sum;
    }
    else if (year >= 2016 && year <= 2025) {
        int sum = 2016 + 2025;
        cout << "Sum of 2016 and 2025 = " << sum;
    }
    else {
        cout << "Year is not in the range.";
    }

    return 0;
}

Explanation
•	If year is between 2000–2015, program prints
2000 + 2015 = 4015
•	If year is between 2016–2025, program prints
2016 + 2025 = 4041
•	Otherwise, program prints
"Year is not in the range."










