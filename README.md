#include<iostream>
using namespace std;
int main(){
    int a=12;
    int b=1283;
    int *ptr =NULL;
    //  cout<<"Address of variable a is: "<<&a<<endl;
    //  cout<<"Address of varaible b is: "<<&b<<endl;
    ptr=&a;
    // ptr=&b;
    cout<<"Now address store inside the pointer is: "<<ptr<<endl;
    cout<<"Value inside the pinter is :"<<*ptr<<endl;

    //   cout<<"Address of variable a is: "<<&a<<endl;
    //  cout<<"Address of varaible b is: "<<&b<<endl;

    return 0;
}
