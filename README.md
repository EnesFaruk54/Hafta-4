#include <iostream>
#include <conio.h>
using namespace std;

int main(){

 int sayi1, dordebolme = 4 ,ucebolme = 3 ;
 float sonuc;
 cout<<"Hafta 4 odevim.\n\n";

 cout<<"Lütfen bir sayi giriniz: ";
 cin>>sayi1;

 if(sayi1%2==0){
    cout<<"sonuc : "<<(float)sayi1/dordebolme;}

 else if (sayi1%2==1){
    cout<<"sonuc : "<<(float)sayi1/ucebolme;}

 return(0);
 }
