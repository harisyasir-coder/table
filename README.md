# table
This is a C++ program for print table
#include <iostream>
using namespace std;
int main() {
    int a ,b,c;
    cout<<"enter a number :";
    cin>>b;
    cout<<"table of "<<b<<" is given below\n";
    for(a=1;a<=10;a++)
      cout<<b<<" * "<<a<<" = "<<b*a <<endl;
} 
