# Converting_a_number_from_meters_to_kilometers
#include <iostream>
using namespace std;
int main()
{
	setlocale(LC_ALL, "Russian");
	double meters;
	cout << "Введите растояние в метрах: ";
	cin >> meters;
	double kilometers = meters / 1000;
	cout << meters << " м." << " равно " << kilometers << " км.";
}

