# Leap-Year-Code-C-
As i builded my login by solving these question for finding leaf year as the code tells given year is leap or not
<br>
author - Umesh jadhav

#include<iostream>
using namespace std; 
int main(){
    int year,year1;
    cout<<"Enter Year : ";
    cin>>year;
    //leap year if perfectly div by 400
    if(year%400==0){
        cout<<year<<" is leap year";
    }else if(year%100==0){
        cout<<year<<" is not leap year";
    }else if(year%4==0){
        cout<<year<<" is leap year";
    }else{
        cout<<year<<" not a leap year";
    }
}
