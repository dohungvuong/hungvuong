#include <iostream>
#include <math.h>
using namespace std;

int main()
{
    double m, n, r, ketqua, x, y;

    cout << "Nhap so tien gui: ";
    cin >> n;

    cout << "Nhap so tien ky vong: ";
    cin >> m;

    cout << "Nhap lai suat theo nam: ";
    cin >> r;
   
    x = m/n;
    y = 1+r;
    ketqua = log(x)/log(y);
    
    cout<<"can so nam la: " << ketqua << endl;
	
    return 0;
}
