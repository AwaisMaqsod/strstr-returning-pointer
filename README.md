//strstr-returning-pointer
//Strstr returning piointer of first occurrence , c++ Oop
#include<iostream>
#include <string.h>
#include<cstring>
using namespace std;
class stringg{
	public:
		char st1[20],st2[20];
		char* p;
        void get_Data(){
			cout<<"Enter 1st string : "<<endl;
			cin>>st1;
			cout<<"Enter 2nd String : "<<endl;
			cin>>st2;
			}
		void set_Data(){
			 p = strstr(st1, st2);
       cout<<"Strings found : Strings return a pointer : "<<endl;
       cout<<"First occurrence of string " << st2<<" . "<< st1<<" . "<< p;
	   
		}
};

int main(){
	stringg tt;
	tt.get_Data();
	tt.set_Data();
	
	return 0;
}
  ![image](https://user-images.githubusercontent.com/96110915/152947205-cef0628b-e8ed-436c-8ebe-41ba6a61d02a.png)
