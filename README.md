//check the number is prime or not
#include<bits/stdc++.h>
using namespace std;
string prime(int num){
    if(num<=1){
        return "not prime";
    }
        for(int i=2;i<num;i++){
            if(num%i==0){
                return "not prime";
            } 
            } return "prime";
        } 
    

int main(){
    int num;
    cout<<"plese enter the number so i check this is prime or not"<<endl;
    cin>>num;
    
    cout<<prime(num);
    return 0;
}
