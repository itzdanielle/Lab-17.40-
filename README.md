# Lab-17.40-
#include <iostream>
#include <iomanip>
using namespace std;

double miles (double distance, int time ) { 
double result;
result = (distance / 65) * time;
return result;
}

int main() {
cout << setprecision(2) << fixed;
double distance;
cout << "Please input the miles traveled: " << endl;
cin >> distance;
int time;
cout << "Please input the hours traveled: " << endl;
cin >> time;
double result;
result = miles(distance, time);
cout << "Your speed is " << result << " miles per hour" << endl; 
}
