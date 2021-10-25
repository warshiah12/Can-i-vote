# Can-i-vote
#include<iostream>
using namespace std;
int main()
{
	int age = 16; //declaring variable age and initialising value 16 to it
	if (age == 18)  //if else statement will be used to check if the user is allowed to vote or not
	{
		cout << "You are eligible to vote." << endl;  //if userinput is equal to 18 then if block of statements will be executed
	}
	else { //if ag is not equal to 18 then else block of statements will be executed
		cout << "Sorry!You are not eligible to vote." << endl;
	}
	return 0;
}
