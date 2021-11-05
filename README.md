# lb1
Прокопов Дмитрий Владиславович
2 курс направления "Программная инженерия"
Программа для подсчёта количества чётных и нечётных чисел
#include <iostream>
using namespace std;
int main()
{
    int n, m, x=0, y=0;
    cin>>n>>m;
    int a[n][m];
    for(int i=0; i<n; i++){
        for(int j=0; j<m; j++){
            cin>>a[i][j];
        }
    }
    for(int i=0; i<n; i++){
        for(int j=0; j<m; j++){
            if( a[i][j]%2==0)x++;
                else y++;
        }
    }
    cout<<x<<endl;
    cout<<y<<endl;
    return 0;
}
