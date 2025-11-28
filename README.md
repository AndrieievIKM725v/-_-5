#include <iostream> 
using namespace std; 
 
int main() { 
    unsigned long long n; 
    cout << "Enter n: "; 
    cin >> n; 
 
    if (n == 0) { 
        cout << "Digits: 1"; 
        return 0; 
    } 
 
    int count = 0; 
    while (n > 0) { 
        n /= 10; 
        count++; 
    } 
 
    cout << "Digits: " << count; 
    return 0; 
}
