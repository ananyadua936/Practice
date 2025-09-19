#include <iostream> 
using namespace std;
 class areacal
 {
     public:
     void area (int side)
     {
         cout<< side*side;
     }
     void area(int l,int b)
     {
        cout<< l*b;
     }
 };
 int main()
 {
 areacal ob;
 ob.area(5);
 ob.area(3,4);
 return 0;
 }
