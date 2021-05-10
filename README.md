# codechef-problem-TABLE

/*Problem Code:TABLE*/
#include<bits/stdc++.h>
using namespace std;
int main(){
    int n;
    cin>>n;
    for(int i=1;i<11;i++){
        i==10?cout<<n*i:cout<<n*i<<" -> ";
    }
    return 0;
}
