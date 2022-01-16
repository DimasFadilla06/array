# array

#include <iostream>

using namespace std;

int main()
{
        //array
    int Z[2][2];

        for(int b=0; b<=2; b++ ){
        for(int k=0; k<=2; k++){
            cout<< "masukkan angka :";
            cout <<"Z["<<b<<"]["<<k<<"] :";
            cin>>Z[b][k];
        }
        }
        cout<<endl;

        for(int b=0;b<=2;b++){
                for(int k=0;k<=2;k++){
                    cout<<Z[b][k];
                }
                cout<<endl;
        }
    return 0;
}
