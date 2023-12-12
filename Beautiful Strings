Problem--
https://www.codechef.com/START111C/problems/BEAUTYSTR?tab=statement

My_Code--

#include <bits/stdc++.h>
#include <vector>
#include <string>
using namespace std;

const int MOD = 1e9+7;

int main() {
    int t;
    cin >> t; // Number of test cases
    while (t--) {
        int n;
        
        cin >> n; 
        string s;
        cin >>s;

        vector<int> f(26, 0); // Arraḥy to store the f of each character

        for (int i = 0; i < n; i++) {
            f[s[i] - 'a']++;
        }

        long long ans = 1; 

        for (int i = 0; i < 26; i++) {
            
            ans =(ans*(f[i] + 1))%MOD;
        }

        cout<<(ans - 1 + MOD)%MOD<<endl;
    }

    return 0;
}
