# prime-number-coding-
#include <iostream>
using namespace std ;

int main() {
  int num ,m, count=0;
  cout <<" enter an integer"<<endl;
  cin>>num;
  if (num<= 1) {
    cout<<" please enter an integer greater than 1"<<endl;
    
    cin>>num;}
  for (m=1 ; m<=num ; m++)
    {  if (num%m==0)
    { count++ ;
      
      }
      }
  if ( count ==2)
  { cout<<" its a prime number "<<endl;}
else {
  cout<<" it is not a prime number "<<endl;}
    
  
  
}
