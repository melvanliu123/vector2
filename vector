#include <iostream>
#include<vector>
using namespace std;
int min(vector <vector<int>> &v) {
   
    int m=v[0][0];
    
    for(int i=0;i<4;i++){
        for(int j=0;j<3;j++){
            
            if(m>v[i][j])
            m=v[i][j];
        }
       
    }
     return m;
}
int main(){
    int x;
    vector<vector<int>> v(4);
    for(unsigned i=0;i<4;i++){
        v[i]=vector<int>(3);
    }
    
    for(int i=0;i<4;i++){
         
        for(int j=0;j<3;j++){
            cin >>x;
            v[i][j]=x;
        }
    }

    cout <<"min: "<<min(v);
    return 0;
} 
