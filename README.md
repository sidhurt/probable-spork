# probable-spork
 User would like to add two numbers of different types such as short, int, float, double, long double, long int, char. System accepts the numbers and depending on its type appropriate function would be invoked. Display the result of addition.   
#include<iostream>
using namespace std;

void add(int,int);
void add(int,double);
void add(double,double);
void add(long double,long double);
void add(double,int);

int main()
{


add(2,3);
add(3,4.5);
add(4.5,3.2);
add(2.1,1.5);
add(3.3,2);
}

void add(int a,int b)
{
int A = a+b;
cout<<A<<endl;
}

void add(int a, double b)
{
double A = a+b;
cout<<A<<endl;
}

void add(double a, double b)
{
double A = a+b;
cout<<A<<endl;
}

void add(long double a, long double b)
{
short A = a+b;
cout<<A<<endl;
}

void add(double a, int b)
{
double A = a+b;
cout<<A<<endl;
}
