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
	cout << "Hi "<<Nombre<<"\nLet's begin, shall we?\n";
	system("PAUSE");

	using std::chrono::system_clock;
	system_clock::time_point current = system_clock::now();
	time_t Tiempo;
	Tiempo = system_clock::to_time_t(current);
	cout << "Your current time is: " << ctime
    return 0;
 }
