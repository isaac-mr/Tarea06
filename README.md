# Tarea06
#include<iostream>
#include<string>
using std::cout;
using std::cin;
using std::string;
using std::to_string;
int main()
{
	int number;
	int sum = 0;
	cout << "select numbers" << "\n";
	cin >> number;
	string x = to_string(number);

	for (int i = 0; i < x.length(); i++)

	{
		char y = x[i];
		int num = y - '0';
		sum += num;

	}
	cout << "The number has these digits:" << x.length() << "\n";
	cout << "The sum of the numbers is:" << sum << "\n";
}
