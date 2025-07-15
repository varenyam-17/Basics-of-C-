# experiment-1
AIM-Hello World and Calculator program
Theory:
•	The C++ language defines several headers, which contain information that is either necessary or useful to your program. For this program, the header <iostream> is needed.
•	The line using namespace std; tells the compiler to use the std namespace. Namespaces are a relatively recent addition to C++.
•	The next line '// main() is where program execution begins.' is a single-line comment available in C++. Single-line comments begin with // and stop at the end of the line.
•	The line int main() is the main function where program execution begins.
•	The next line cout << "Hello World"; causes the message "Hello World" to be displayed on the screen.
•	The next line return 0; terminates main( )function and causes it to return the value 0 to the calling process.
Code:
#include<iostream>
using namespace std;
int main()
{
    cout<<"Hello World"<<endl;
    cout<<"First Program";
    return 0;
}
Part 2:

#include<iostream>
using namespace std;
int main()
{
    float num1,num2;
    cout<<"Enter the First Number"<<endl;
    cin>>num1;
    cout<<"Enter The Second number"<<endl;
    cin>>num2;
    int num3=num1+num2;
    cout<<"Add: "<<num3<<endl;
    int nums=num1-num2;
    cout<<"Sub: "<<nums<<endl;
    int numm=num1*num2;
    cout<<"mult: "<<numm<<endl;
    float div=num1/num2;
    cout<<"div: "<<div<<endl;
    return 0;
}

