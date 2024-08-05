// ConsoleApplication1.cpp : This file contains the 'main' function. Program execution begins and ends there.
//

#include <iostream>
using namespace std;

int main(){

    string str = "Racecar 1.";
    int n = str.length();
    //loop through the first half of the string 
    for (int i =0; i < n/2;++i) { 

        swap(str[i], str[n - i - 1]);
    }
    cout <<"Reversed  String" << str << endl;
    return 0;
}
