## basic
```cpp
#include <iostream>
#include <cmath>
#include <string>
using namespace std;

int main() {
    //
    // page1(); 
    return 0;
}
```

```cpp
#include <iostream>
using namespace std;

/* between this many lines too*/
void page1(){
    string name;
    cout << "Hello\nEnter your name: ";
    cin >> name;
    cout << "Welcome,\n\n\n" + name << endl;
    // this is a comment, hedaya wake up and didnt had breakfast
}
```

```cpp

void page4(){
    cout << sqrt(25) << endl;
    cout << pow(2, 3) << endl;
    cout << 10 % 3 << endl;
    /*
    // modulo
    20 / 3
    quetiont:  
    el hahar : 2
    */
}
```

```cpp
void page6() {
    char ch = 'A';
    // string daya = "dAaya"
    cout << ch << endl;
    cout << int(ch) << endl;
}
```

```cpp

void page7(){
   // float can be int
   // char can be int
   // int can be char
     
   // int 65 'A'
   // char 
   char starry = 66; // 'B'
   int frost = 'A'; // 65
   
    char hed = 65 + 1;
    int daya = int(hed);
    cout << hed << endl;
    cout << daya << endl;
}
```

```cpp
// x++, ++x
void page8(){
    int x = 10; // x = 10
    int daya = x; // x = 10
    x = x + 1; // x = 11
    
    int starry = x; // x = 11
    x = x - 1; // x = 10
    // starry = 11
    starry = starry + 10; // starry += 10, starry = 21
    starry += 10; // starry = 31
    starry = starry * 10; // starry *= 10, starry = 310
    starry = starry - 10; // starry -= 10, starry = 300
  
    bool aredaya = (x > 5);
    
    cout <<"daya " << daya << endl;
    cout << "starry " << starry << endl;
    cout << "x " << x << endl;
    cout << "bool " << aredaya << endl;
}
```

```cpp
void page10(){
    int n = 15;
    bool daya = (n < 10);
    bool starry = (n>10);
    bool frost = (n==15);
    // and or not
    bool and1 = daya && starry && frost; // and1=false
    bool or1 = daya || starry || frost; // or1=true
    bool not1 = !and1 || !or1; // not1=true
    // and: 
    // or:
    // not:
    cout <<"and " << and1 << endl;
    cout << "or " << or1 << endl;
    cout << "not " << not1 << endl;
}

```
