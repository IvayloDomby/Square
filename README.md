#include <iostream> 
using namespace std;

 int main(){ 
  int size;  
  bool solid =false;  //Ïëúòíî èëè êóõî
  cout <<"Size:"; 
  cin >>size; 
  cout << endl; 
  for (int r=0;r<size;r++)
  { 
      for (int c=0;c<size;c++)
	  { 
          if(solid) 
              cout << " *"; 
          else
		  { 
              if(r==0||r==size-1||c==0 or c==size-1)
                  cout<< " *"; 
              else
                  cout<< "  "; 
          }  
      } 
    cout<<endl; 
}  
}
