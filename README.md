# Menentukan-Bilangan-Prima
    #include<iostream>
    #include<conio.h>
    using namespace std;
    int main()
    {
        int a,b,c;
        cout<<"menampilkan bilangan prima dari 1-100\n ";
        for(a=1;a<=100;a++)
        {
            c=0;
            for(b=1;b<=a;b++)
            {
                if(a%b==0){c+=1;}
            }
            if(c==2)
            {
                cout<<a<< " ";
            }
        }
        getch();
        return 0;
    }
   # Hasil
   ![img](https://raw.githubusercontent.com/AminPriadi/Menentukan-Bilangan-Prima/master/Bilangan%20prima.png)
