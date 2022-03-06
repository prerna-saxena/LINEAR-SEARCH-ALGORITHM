# LINEAR-SEARCH-ALGORITHM
LINEAR SEARCH ALGORITHM

//LINEAR SEARCH ALGORITHM

#include <iostream>
using namespace std;
  
void linearsearch(int arr[], int n)
{
  int temp=-1;
  for(int i=0; i<5; i++)
  {
     if (a[i]==n)
      {
        cout<<"ELEMENT FOUND AT LOCATION"<< i<< endl;            
        temp=0;            
      }
  }
 if(temp==-1)
 {
   cout<<"NO ELEMENT FOUND"<< endl;
 }                                 
}  
int main()
  {
  int arr[5]={1, 22, 34, 5, 7}, num;
  cout<<"PLEASE ENTER AN ELEMENT TO SEARCH";
  cin>>num;
  linearsearch(arr, num);
  
  return 0;
  }
  
