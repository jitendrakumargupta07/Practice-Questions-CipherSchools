// ANSWER 1
#include <iostream>
using namespace std;

int main() {
    string str1, str2;

    cout << "Enter the first string: ";
    cin >> str1;

    cout << "Enter the second string: ";
    cin >> str2;

    cout << "Concatenated string: " << str1 + str2 << endl;

    return 0;
}


//ANSWER 2
#include <iostream>
using namespace std;

int main() {
    int grade1, grade2, grade3, grade4, grade5;
    int sum;

    cout << "Enter grade 1: ";
    cin >> grade1;

    cout << "Enter grade 2: ";
    cin >> grade2;

    cout << "Enter grade 3: ";
    cin >> grade3;

    cout << "Enter grade 4: ";
    cin >> grade4;

    cout << "Enter grade 5: ";
    cin >> grade5;

    sum = grade1 + grade2 + grade3 + grade4 + grade5;
    cout << "The average grade is: " << sum / 5.0 << endl;

    return 0;
}


//ANSWER 3
#include <iostream>
using namespace std;

int main() {
    int number;

    cout << "Enter a number: ";
    cin >> number;

    cout << "The square of " << number << " is: " << number * number << endl;

    return 0;
}
