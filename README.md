# ACTIVITY1 finals
#include <iostream>
using namespace std;

#include <iostream>
using namespace std;

int main() {
    int list[5] = {10, 20, 30, 40, 50};
    int index;

    cout << "Enter an index (0–4): ";
    cin >> index;

    if (index >= 0 && index < 5) {
        cout << "list[" << index << "] = " << list[index] << endl;
    } else {
        cout << "Error: Index out of bounds!" << endl;
    }

    return 0;
}

How can array index errors cause unpredictable results?





What are good programming practices to prevent them?

Always validate indices before accessing arrays.
Use constants for array size (e.g., const int SIZE = 5;).
Use loops that respect array boundaries (for (int i = 0; i < SIZE; ++i)).
