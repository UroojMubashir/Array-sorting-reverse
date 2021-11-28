#include <iostream>
#include <array>
#include <algorithm>
using namespace std;

int main()
{
   array <int,5> numbers ={33,5,7,99,83};
   reverse(numbers.begin(), numbers.end());
   for(int num:numbers){
       cout<<num <<" ";
   }

    return 0;
}

   
