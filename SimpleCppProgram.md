## Simple Code .
#include <iostream>
using namespace std;

int main()
{
  cout << "Programming is great fun!";
  return 0;
}
 
  # Below code is added by me
  ## C++ code for pythagoras theorem -->>

#include<iostream>
using namespace std;
int main()
{
    int a,b,c;
    cout<<"Enter The 'base' of the Traingle: ";
    cin>>a;
    cout<<"Enter The 'Perpendicular/height' of the Traingle: ";
    cin>>b;
    cout<<"Enter The 'Diagonal' of the Traingle: ";
    cin>>c;
    if(a*a+b*b==c*c){
        cout<<"Triangle follows Pythagoras's Theorem";
    }
    else{
        cout<<"Not Follow Pythagoras's Theorem";
    }
    return 0;
}
