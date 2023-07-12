# Calculadora
#include<iostream>
using namespace std;

int main(){

  int op;
  double num1,num2,sum,res,mult,div;
  
  
  cout<<"Elije el primer termino: "<<endl;
  cin>>num1;
  
  cout<<"Elije el segundo termino: "<<endl;
  cin>>num2;
  
  cout<<"-- (1) Suma -- "<<endl;
  cout<<"-- (2) Resta -- "<<endl;
  cout<<"-- (3) Multiplicacion -- "<<endl;
  cout<<"-- (4) Division --"<<endl<<endl;
  
  cout<<"Elije la operacion a realizar: "<<endl;
  cin>>op;
	
	
  
  switch(op){
  	
  	case 1: 
  	
  	  cout << "Has elegido suma " <<endl;
  	  
  	  sum= num1+num2;
  	  
  	  cout << "tu resultado es: " <<sum<<endl;
  	  break; 
		 
  	case 2: 
  	
  	  cout << "Has elegido resta " <<endl;
  	  
  	  res= num1-num2;
  	  
  	  cout << "tu resultado es: " <<res<<endl;
  	  break;
  	  
	case 3: 
  	
  	  cout << "Has elegido multiplicacion " <<endl;
  	  
  	  mult= num1*num2;
  	  
  	  cout << "tu resultado es: " <<mult<<endl;
  	  break;
		
	case 4: 
  	
  	  cout << "Has elegido division " <<endl;
  	  
  	  div= num1/num2;
  	  
  	  cout << "tu resultado es: " <<div<<endl;
  	  break;
		
	default: 
	
	  cout<<"Elije un numero valido";
	  break;			 

  }


   return 0;

}
