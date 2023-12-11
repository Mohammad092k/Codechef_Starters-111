Problem
Chef embarks on a journey starting from a town named 
�
S, containing a string of 
8
8 uppercase English alphabets. His objective is to reach the destination known as CODETOWN.

If Chef is currently in town 
�
1
T 
1
​
 , then, with each move, Chef can transition to another town named 
�
2
T 
2
​
 , provided that either:

�
2
T 
2
​
  is derived from 
�
1
T 
1
​
  by replacing a consonant with another consonant, or;
�
2
T 
2
​
  is derived from 
�
1
T 
1
​
  by replacing a vowel with another vowel.
Find whether Chef can reach CODETOWN in any number of moves.
Note that in the english alphabet, letters A, E, I, O, and U are considered as vowels and rest are considered as consonants.

My-Code--

#include <bits/stdc++.h>
using namespace std;

int main() {
  int t;
  cin >> t;
  while (t--) {
    string s;
    cin >> s;

    bool valid = true;
    for (int i = 0; i < 8; i++) {
      if (i == 1 || i == 3 || i == 5) {
        if (!(s[i] == 'A' || s[i] == 'E' || s[i] == 'I' || s[i] == 'O' || s[i] == 'U')) {
          valid = false;
          break;
        }
      } else {
        if (s[i] == 'A' || s[i] == 'E' || s[i] == 'I' || s[i] == 'O' || s[i] == 'U') {
          valid = false;
          break;
        }
      }
    }

    if (valid) {
      cout << "YES" << endl;
    } else {
      cout << "NO" << endl;
    }
  }
  return 0;
}
