#include<iostream>
using namespace std;
	void getvalues ( int [ ] , int );
		int main(){
			int num [ 10 ] , i;

			//Function call, passing Array num
			getvalues ( num , 10 );

			// Display the values of Arrays 
			cout << "\n The Array  is populated with values \n ";
			for ( i = 0; i < 10; i++)
			cout << "num [ " << i << " ] = " << num [ i ] << '\n';
		}

		void getvalues ( int num [ ] , int arraysize){
			int i;

			for ( i = 0; i < arraysize; i++ ){
				num [ i ] = i;
			}
		}
