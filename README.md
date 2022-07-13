# C-Programme
C-All-Programme

#include <bits/stdc++.h>

using namespace std;

    int main(){

        int number, range;
        cout<<"Enter number:";
        cin>>number;
        cout<<"Enter Range:";
        cin>>range;
        for(int i=1; i<=range; ++i){
            cout<<number<<"*"<<i<<"="<<number*i<<endl;
        }
    }
