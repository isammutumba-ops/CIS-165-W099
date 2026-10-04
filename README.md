# CIS-165-W099
CIS LAB 4 project
#include <iostream>
using namespace std;

int main() {
//All Values
    double value1=28;
    double value2=32;
    double value3=37;
    double value4=24;
    double value5=33;
//My values are 6-10
    double value6=29;
    double value7=33;
    double value8=38;
    double value9=25;
    double value10=34;
    
    
//sum(s)    
    double sum1; 
    sum1=value1 + value2 + value3 + value4 + value5;
    
//my sum is sum2
    double sum2; 
    sum2=value6 + value7 + value8 + value9 + value10;
    
    
//Averages
    double average1;
    average1=sum1/5;
    
//my average is average2
    double average2;
    average2=sum2/5;
    
// results
    cout <<"\nDifferent value calculations expected values results\n";
    
    cout << "Sum: " << sum1 << endl;
    cout << "Average: " << average1 << endl;
    
    cout <<"\nMy calculations with my variables results\n";
    
    cout << "Sum2: " << sum2 << endl;
    cout << "Average2: " << average2 << endl;
    
    
//Expected rate code
    cout <<"\nOcean level example from professor\n";
    
    const double ANNUAL_RATE=1.5;
    int years_5=5;
    int years_7=7;
    int years_10=10;
    
    double increase_5;
    double increase_7;
    double increase_10;
    
    increase_5 = ANNUAL_RATE*years_5 ;
    increase_7 = ANNUAL_RATE*years_7 ;
    increase_10 = ANNUAL_RATE*years_10 ;
    
    cout <<"Ocean level after 5 years: " << increase_5 << "mm" << endl;
    cout <<"Ocean level after 7 years: " << increase_7 << "mm" << endl;
    cout <<"Ocean level after 10 years: " << increase_10 << "mm" << endl;
    
    cout <<"\nOcean level example manipulated rate\n";
//My manipulated rate below:    
    const double ANNUAL_RATEE=1.6;
    
    increase_5 = ANNUAL_RATEE*years_5 ;
    increase_7 = ANNUAL_RATEE*years_7 ;
    increase_10 = ANNUAL_RATEE*years_10 ;
    
    cout <<"Ocean level after 5 years: " << increase_5 << "mm" << endl;
    cout <<"Ocean level after 7 years: " << increase_7 << "mm" << endl;
    cout <<"Ocean level after 10 years: " << increase_10 << "mm" << endl;
    
    return 0;
}
