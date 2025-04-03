# 977A-WRONG-SUBSTRACTION-CODEFORCES

#include <bits/stdc++.h>
using namespace std;

int main() {
    int n, k;
    cin >> n >> k;

    for (int i = 1; i <= k; i++) {  // Fix loop condition
        if (n % 10 == 0) 
            n /= 10;
        else 
            n -= 1;
    }

    cout << n << endl;  // Print only final result
    return 0;
}


//HERE WE SOLVE THE QUESTION IN WHICH THE GIRL IS DOING WRONG SUBSTRACTION 

