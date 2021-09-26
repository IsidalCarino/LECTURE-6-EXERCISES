# Lecture-6-Exercise
#include <iostream>
using namespace std;
int main()
{
    bool canivote = true;
    cout << "What is your age?";
    int agenum;
    cin >> agenum;
    if (agenum < 18) {
        cout << "You cannot vote" << endl;
    }
    else if (agenum > 18) {
        cout << "You can vote" << endl;
    }
}
  
  //odd and even
