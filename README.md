# Practical-4-4-1-

#include<iostream>
using namespace std;

int max(int i, int j) {
    return (i > j) ? i : j;
}
int max(int i, int j, int k) {
    return max(max(i, j), k);
}
int main() {
    int num1, num2, num3;
    cout << "Enter Three numbers: ";
    cin >> num1 >> num2 >> num3;
    cout << " Maximum number is: " << max(num1, num2, num3) << endl;
    return 0;
}
