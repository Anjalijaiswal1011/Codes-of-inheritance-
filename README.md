# Codes-of-inheritance-#include<iostream>
using namespace std;

class student {
public:
    void print () {
        cout << "She is very intelligent" << endl;
    }
};

class Girl {
public:
    void print1() {
        cout << "Enter two numbers: ";
        cin >> a >> b;
        
        
    }
public:
    int a = 24, b = 30;
    
};
class neha : public Girl {
public:
void product ()
{
cout << "The multiplication of " << a << "×" << b << " is " << a*b << endl;
}
};

class Ansha : public Girl
 {
 public:
 void sum()
 {
    cout <<a+b<<endl;
    }
};

int main() {
    neha n;
    Ansha a;
    
    
    a.sum();
    n.product();
    
    return 0;
    }
