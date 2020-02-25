# FunctionF2
Calling function
#include "stdafx.h"
#include <iostream>
using namespace std;

int f2(int &x)
{
	x = 9;
	return 11;
}



void main()
{
	int i = 7;
	f2(i);
	cout << i;
    
}
