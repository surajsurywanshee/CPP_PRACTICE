//  1. number swapping program 

#include <iostream>
using namespace std;

int main()
{
    int a, b;
    cin >> a >> b;

 //1st  
    int temp;
    temp = a;
    a = b;
    b = temp;
    
//2nd 
    a = a + b;
    b = a - b;
    a = a - b;
    cout << a << "\t" << b;
    return 0;
}

//  2. checking number is prime or not

#include <iostream>
using namespace std;

int main () {
    int n;
    cin >> n;
    int counter = 0;
    
 // 1st mathode
    for (int i = 1; i <= n; i++) {
        if (n%i == 0) {
            counter++;
        } 
    }
    if (counter==2) {
        cout << "it is a prime  number";
    }
    else {
        cout << " it is not a prime number";
    }

// 2nd mathode 
      for (int i = 1; i <= n/2; i++) {
        if (n%i == 0) {
            counter++;
        }  
    }
    if (counter==1) {
        cout << "it is a prime  number";
    }
    else {
        cout << " it is not a prime number";
    }
}

// 3. maximum number cheking program

#include <iostream>
using namespace std;

 int main() {
     int a, b, c;
     cin >>a>>b>>c;
     int max =0;
     if (a>b) {
         if (a>c) {
             max = a;
         }
         else {
             max = c;
         }
     }
     else {
         if(b>c) {
             max = b;
         }
         else {
             max =c;
         }
     }
     cout << "max out of " <<a<< " " <<b<< " " <<c<< " is " << max; 
 }

//4.EXAMPLE

#include <iostream>
using namespace std;

int main()
{
    int n;
    cout << "enter the number :";
    cin >>n;
    int count = 0;
    for (int i =1; i<= n; i++) {
        if (n%i == 0) {
            cout << i << " ";
            count ++;
        }
    }
    cout << " \n count of devisor : " << count;
    return 0;
}

// 5. EXAMPLE

#include <iostream>
using namespace std;
int main() 
{
    int n;
     cout << "enter the number :";
     cin >>n;
     int count = 0;
     while (n>0) {
         n = n/10;
         count ++;  
     }
     cout << " count of digits :" << count;
     return 0;
 }
