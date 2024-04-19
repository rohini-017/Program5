#include <iostream>
using namespace std;

int main() {
  double numbers[] = {7, 5, 6, 12, 35, 27};

  double sum = 0;
  double count = 0;
  double average;

  cout << "The numbers are: ";
  for (const double &n : numbers) {
    cout << n << "  ";
    sum += n;

    // count the no. of array elements
    ++count;
  }
  cout << "\nTheir Sum = " << sum << endl;
  average = sum / count;
  cout << "Their Average = " << average << endl;

  return 0;
}
