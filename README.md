# cplus2if_statement
more if statement


#include <iostream>
using namespace std;

int main()
{
    bool isMale=true;
    bool isTall=false;
     
    if (isMale && isTall){
          cout<<" You are a male and you are tall\n ";
    }else if (isMale && !isTall){
          cout<<" You are a short male\n ";
    }else if (!isMale && isTall){
           cout<<" You are a tall male\n ";
    }else{
          cout<<"You are not a male and you are not tall";
    }
    return 0;
}
output:
  
  You are a short male
