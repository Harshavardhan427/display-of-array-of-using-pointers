# display-of-array-of-using-pointers
#include <iostream>
using namespace std;

int main()
{
   int arr[5];
   cout << "Enter elements: ";

   for(int i = 0; i < 5; ++i)
      cin >> arr[i];

   cout << "You entered: ";
   for(int i = 0; i < 5; ++i)
      cout << " " << *(arr + i);

   return 0;
    
    output:
                         
Enter elements: 1 2 3 5 4
You entered:  1 2 3 5 4
                         
