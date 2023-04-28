#include <bits/stdc++.h>
using namespace std;
float CalcularFahrenheit(float fahrenheit);
int main (){
	float fahrenheit;
	
	cout<<"Ingrese la cantidad de Fahrenheit que quiere pasar a grados centígrados: "<<endl;
	cin>>fahrenheit;
	
	cout<<"la cantidad de grados centígrados es de: "<<CalcularFahrenheit(fahrenheit)<<endl;
	
	return 0;
}

float CalcularFahrenheit(float fahrenheit){
	float Celciuls;
	
	Celciuls=(fahrenheit-32) * 1.8;

	
	return Celciuls;
}
