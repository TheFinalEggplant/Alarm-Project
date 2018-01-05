# Alarm-Project
Work done for Computer Science SL AI
#include "stdafx.h"
#include <iostream>
#include<string>

using namespace std;

int main()
{
	string Nombre;
	cout << "Hello. I am your personalized Alarm Clock. To begin, please enter your name.\nMy name is: "; //Intro and Name
	cin >> Nombre;
	cout << "Hi "<<Nombre<<"\n Let's begin, shall we?\n";
	system("PAUSE");
    return 1;
}
int clock()
{
	cout << "First, we need to check your computer's clock. One moment please...\n";
	return 0;
}
