//CAN I VOTE
#include <iostream>
using namespace std;
int main()
{
    char again = 'y';
        while (again=='y'||again == 'Y'){
    bool canivote = true;
    cout << "Enter your age: ";
    int agenum;
    cin >> agenum;
    if (agenum < 18) {
        cout << "You cannot vote" << endl;
    }
    else if (agenum > 18) {
        cout << "You can vote" << endl;
    }cout << "Go again? (Y or N): ";
    cin >> again;
    }

//ODD OR EVEN
    
#include <iostream>
using namespace std;
int main()
{
    char again = 'y';
    while (again == 'y' || again == 'Y') {
        int x;
        cout << "Enter a Number: ";
        cin >> x;
        if (x % 2 == 0)
            cout << x << "Even Number." << endl;
        else
            cout << "Odd Number." << endl;
    cout << "Go again? (Y or N): ";
    cin >> again;
    }
        return 0;
    
 //NUMBER CHECKER
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
