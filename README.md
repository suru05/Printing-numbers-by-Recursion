# Printing-numbers-by-Recursion
#include <iostream>
using namespace std;
int i = 0;
void Name(int i, int N)
{
    
    if (i > N) {
        return;
    }
    cout << i << endl;
        Name(i + 1, N);
    
    
}
int main()
{ 
    
    Name(1,35);
    return 0;
}
