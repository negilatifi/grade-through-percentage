# grade-through-percentage
Finds the grade of your test depending on the percentage of questions completed.
//Program qe percakton noten ne baze te pikeve te marra.  
// Punoi: Negi Latifi



#include <iostream>
using namespace std;

int main(){
    int piket;

    cout<<"Fut piket e marra: "<<endl;
    cin>>piket;

    if(piket<=44){
        cout<<"Ju keni marre 4"; //Nese sasia e pikeve eshte < ose = me 44 nota eshte 4.
        
    }
    else if(piket>=45 and piket<=54){
        cout<<"Ju keni marre 5";
    }
    else if(piket>=55 and piket<=64){
        cout<<"Ju keni marre 6";
    }
    else if(piket>=65 and piket<=74){
        cout<<"Ju keni marre 7";
    }
    else if(piket>=75 and piket<=84){
        cout<<"Ju keni marre 8";
    }
    else if(piket>=85 and piket<=94){
        cout<<"Ju keni marre 9";
    }
    else if(piket>=95 and piket<=100){
        cout<<"Ju keni marre 10";
    }
    return 0;

}

