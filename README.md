# Membuat program-pembalik kata kalimat

Coding program lengkap

    #include <iostream>
    #include <string.h>
    using namespace std;
    int main(void)
    {
    char str[100];
    int i,l;

    cout<<"MASUKKAN KATA = ";
    cin>>str;

    l=strlen (str);
    cout<<"KATA TERBALIK = ";

    for (i=l-1;i>=0;i--){
        cout<<str[i];
    }
    return 0;
    }



Hasil program

![img](https://raw.githubusercontent.com/MUTIARAIZMI/Membuat-program-pembalik-kata-kalimat/master/pembalik%20kata.jpg)
