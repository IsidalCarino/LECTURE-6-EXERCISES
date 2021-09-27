#CAN I VOTE
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
    #include <iostream>
using namespace std;
int main()
{
    char again = 'y';
    while (again == 'y' || again == 'Y') {
        int number;
        cout << "Enter a number: ";
        cin >> number;
        if (number >= 1)
            cout << number << " is a postive number." << endl;
        if (number <= -1)
            cout << number << " is a negative number." << endl;
        if (number == 0)
            cout << "The number is zero." << endl;
    }cout << "Go again? (Y or N): ";
    cin >> again;
}
    
   
    //PROFIT OR LOSS
    #include <iostream>
using namespace std;
int main()
{
	int pp, sp, profit, loss;
	cout << "Enter Purchase Price: " << endl;
	cin >> pp;
	cout << "Enter Sale Price: " << endl;
	cin >> sp;
		if (sp > pp);
		{
	profit = sp - pp;
	cout << "Profit: " << profit << endl;
	}
	 if (pp > sp)
		{
			loss = pp - sp;
			cout << "Loss of: " << loss << endl;
		}
		else {
			cout << "no profit and no loss.";
		}
}

    //NAME THAT SHAPE
#include <iostream>
using namespace std;
int main()
{
    int shapes;
    cout << "Enter how many sides of the shape: " << endl;
    cin >> shapes;
    if (shapes = 3) {
        cout << "Triangle"; << endl;
    }if (shapes = 4) {
        cout << "Square"; << endl;
    //very sorry ms i think i need help on this one :(
    }
}
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
