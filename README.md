# PPK
#include <iostream>

using namespace std;

int main()
{
    // std::cout << "Hello World!\n"; 
    int i, j, x, y;
    cout << "Podaj dlugosc szachownicy:";
    cin >> j;
    cout << "Podaj szerokosc szachownicy:";
    cin >> i;


    
        for (x = 0; x < i; x++)
        {
            if (x % 2 == 0)
                cout << "X";
            else cout << " ";
        }
  
        cout << endl; 

        for (y = 1; y < i; y++)
        {
            if (y % 2 == 0)
                cout << "X";
            else cout << " ";
        }
}
