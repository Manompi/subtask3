#include <iostream>
using namespace std;

int main() {
    int temp1, temp2, temp3;

    
    
    // Get temperature readings from user
    cout << "Enter the first temperature reading: ";
    cin >> temp1;
    
    cout << "Enter the second temperature reading: ";
    cin >> temp2;

   
    // Check temperature difference between first and second reading
    int difference = temp2 - temp1;
    
    if (difference > 50) {
        cout << "Reduce fryer heat before taking the third reading." << endl;
    } else if (difference < 10) {
        cout << "Increase the Fryer heat before taking the third reading." << endl;
   
    
  
