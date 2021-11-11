# Demo--1
#include<iostream>

using namespace std;

int main() {
    int x1, x2, x3, x4, x5;
    int max, min;
    cout << "Nhap vao 5 so: ";
    cin >> x1 >> x2 >> x3 >> x4 >> x5;
    max = x1;
    if (x2 > max)
        max = x2;
    if (x3 > max)
        max = x3;
    if( x4 > max)
        max = x4;
    if (x5 > max)
        max = x5;
    
    min = x1;
    if (x2 < min )
        min = x2;
    if (x3 < min)
        min = x3;
    if( x4 < min)
        min = x4;
    if (x5 < min)
        min = x5;
    cout << "Gia tri lon nhat la " << max << endl;
    cout << "Gia tri nho nhat la " << min << endl;
    return 0;
}
