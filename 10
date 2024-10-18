#include <iostream>
#include <vector>
#include <cmath>
#include <string>
using namespace std;




int main() {
    
    double a, b, c;
    cin >> a >> b >> c;

   
    double sides[3] = {a, b, c};
    sort(sides, sides + 3);


    a = sides[0];
    b = sides[1];
    c = sides[2];

    if (a + b <= c) {
        cout << "impossible" << endl;
    } else {
        
        double a2 = a * a;
        double b2 = b * b;
        double c2 = c * c;

        if (a2 + b2 == c2) {
            cout << "right" << endl;
        } else if (a2 + b2 > c2) {
            cout << "acute" << endl;
        } else {
            cout << "obtuse" << endl;
        }
    }

    return 0;
}
