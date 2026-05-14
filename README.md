#include <iostream>
using namespace std;

int main() {
    int n;

    cout << "Enter number of elements: ";
    cin >> n;

    int arr[n];

    cout << "Enter " << n << " elements: " << endl;
    for (int i = 0; i < n; i++) {
        cin >> arr[i];
    }

    cout << "Output: " << endl;
    for (int i = 0; i < n; i++) {
        cout << arr[i] << " ";
    }
    cout << endl;

    int sum = 0;
    for (int i = 0; i < n; i++) {
        sum += arr[i];
    }

    cout << "Sum of elements: " << sum << endl;


// Task 2: Sum of Elements
int n2;
std::cin >> n2;
int arr2[n2];
int sum2 = 0;

for (int i = 0; i < n2; i++) {
    std::cin >> arr2[i];
    sum2 += arr2[i];
}
std::cout << sum2 << std::endl;


int n3;
std::cin >> n3;
int arr3[n3];

for (int i = 0; i < n3; i++) {
    std::cin >> arr3[i];
}

int max3 = arr3[0];
for (int i = 1; i < n3; i++) {
    if (arr3[i] > max3) {
        max3 = arr3[i];
    }
}

std::cout << max3 << std::endl;



int n4;
std::cin >> n4;
int arr4[n4];

for (int i = 0; i < n4; i++) {
    std::cin >> arr4[i];
}

int min4 = arr4[0];
for (int i = 1; i < n4; i++) {
    if (arr4[i] < min4) {
        min4 = arr4[i];
    }
}

std::cout << min4 << std::endl;



int n6;
std::cin >> n6;
int arr6[n6];
for (int i = 0; i < n6; i++) {
    std::cin >> arr6[i];
}

int target;
std::cin >> target;

bool exists = false;
for (int i = 0; i < n6; i++) {
    if (arr6[i] == target) {
        exists = true;
        break;
    }
}

if (exists) {
    std::cout << "Found" << std::endl;
} else {
    std::cout << "Not Found" << std::endl;
}


    return 0;
}
