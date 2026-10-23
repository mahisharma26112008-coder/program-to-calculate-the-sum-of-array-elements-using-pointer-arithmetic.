# program-to-calculate-the-sum-of-array-elements-using-pointer-arithmetic.

#include<iostream>
  using namespace std;  
    int main(){
     int arr[5]={10,20,30,40,50};
     int *p=arr;
        int sum=0;
      cout<<*p;

        for(int i=0;i<5;i++){
            sum=sum+*(p+i);
        }

        cout<<"sum of elements : "<<sum;
        
         return 0;

    }
        

        

        
