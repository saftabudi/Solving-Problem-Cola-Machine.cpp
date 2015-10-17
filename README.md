#include <iostream>

using namespace std;

int main(){

    int Minuman;
    cout<<"======PILIH MINUMAN KESUKAAN ANDA=======\n\n";
    cout<<"Masukan Kode Minuman : ";
    cin>>Minuman;
    switch(Minuman)
    {
        case 1:cout<<"Minuman yang anda pilih adalah Cocacola\n";break;
        case 2:cout<<"Minuman yang anda pilih adalah Nestea\n";break;
        case 3:cout<<"Minuman yang anda pilih adalah Cimory\n";break;
        case 4:cout<<"Minuman yang anda pilih adalah Milo\n";break;
        case 5:cout<<"Minuman yang anda pilih adalah Rootbeer\n";break;
        default :cout<<"Error!!!choice was not valid, here is your money back \n\n";break;

    }

    return 0;
}
