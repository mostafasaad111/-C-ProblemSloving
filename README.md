# fundamental-of-C++

## 1-first program
     .#include <iostream>
    int main()
    {
      std::cout << "**********************\n";
      std::cout << "Name: Mustafa saad Mohammed.\n";
      std::cout << "Age: 23 Years.\n";
      std::cout << "City: Cairo.\n ";
      std::cout << "Country: Egypt\n";
      std::cout << "**********************\n";
      return 0 ;
    }
## 2-Write a program to do the following shape:
      #include <iostream>
     int main()
     {
       std::cout << "*********\n";
       std::cout << "*********\n";
       std::cout << "*********\n";
       std::cout << "*********\n";
       
       return 0 ;
     }  
## 3-Write a program to do the following output and Leave space between every line:
      #include <iostream>
          int main()
          {
            std::cout << "I love Programming!\n\n";
            std::cout << "I promise to be the best developer ever!\n\n";
            std::cout << "I know it will take some time to practice, but I will achieve my goal.!\n\n";
            std::cout << "\n";
            std::cout << "Best Regards, \n Mustafa Sad";
            
            return 0 ;
          }    
## 4-Write a program to do the following shape:

            #include <iostream>
               int main()
               {
                 std::cout <<"*    *\n";
                 std::cout <<"*    *\n";
                 std::cout <<"******\n";
                 std::cout <<"*    *\n";
                 std::cout <<"*    *\n";
                 
                 return 0 ;
               }
## increment && decrement example :

          #include <iostream>
          using namespace std;
          int main()
          {
            int A = 10;
            int B = A++;
          
            cout<< "B = " << B << endl;
            cout<< "A = " << A << endl;
          
            B = ++A;
            cout<< "B = " << B << endl;
            cout<< "A = " << A << endl;
            return 0;
          }
## Assignment Operators :
          #include <iostream>
          using namespace std;
          int main()
          {
           
            int a = 10 , b = 20;
            a += b ; // a = a + b
            cout << " a += b " << a << endl;
            a -= b ; // a = a - b 
            cout << " a += b " <<a << endl;
            a *= b;  // a = a * b
            cout << " a += b " << a << endl;
            a /= b; // a = a / b
            cout << " a += b " <<a << endl;
            a %= b; // a = a / b
            cout << " a += b " <<a << endl;
          
            return 0;
          
          }

## Relational Operators :

          #include <iostream>
          using namespace std;
          int main()
          {
           
            int a = 10 , b = 20;
            
            cout << (a == b ) <<endl;
            cout << (a != b ) <<endl;
            cout << (a > b ) <<endl;
            cout << (a < b ) <<endl;
            cout << (a >= b ) <<endl;
            cout << (a <= b ) <<endl;
            return 0;
          
          }
## Relational 0perateor 2 :


          #include <iostream>
          using namespace std;
          int main()
          {
           
                 int a , b;
                 
                 cout << "please enter a number" << endl;
                 cin >> a;
                 
                 cout << "please enter b number" << endl;
                 cin >> b;
                 
                 cout << (a == b ) <<endl;
                 cout << (a != b ) <<endl;
                 cout << (a > b ) <<endl;
                 cout << (a < b ) <<endl;
                 cout << (a >= b ) <<endl;
                 cout << (a <= b ) <<endl;
            return 0;
          
          }
## Logical Operators :
          #include <iostream>
          using namespace std;
          int main()
          {
            
            // Task 
            cout << (12 >= 12)<< endl;
            cout << !(12 >= 12) << endl;
            cout << (1 && 1) << endl;
            cout << (7 == 7  && 7 > 5) << endl;
            cout << (12 > 7 ) << endl;
            cout << !(12 < 7 ) << endl;
            cout << (true && 0 ) << endl;
            cout << (7 == 7 && 7 < 5) << endl;
            cout << ( 8 < 6) << endl;
            cout << !( 8 < 6 ) << endl;
            cout << ( 0 || 1) << endl;
            cout << (7 == 7 || 7< 5) << endl;
            cout << (7 < 7 || 7 > 5) << endl;
            cout << (8 == 8 ) << endl;
            cout << !(8 == 8 ) << endl;
            cout << ( 0 || 0) << endl;
            cout << ( 12 <= 12 ) << endl;
            cout << !(12 <= 12) << endl;
            cout << !(0) << endl;
            cout << (7 == 7 && 7 > 5) << endl;
            cout << ( 7 == 5) << endl;
            cout << ! ( 7 == 5 )<< endl;
            cout << !(1 || 0) << endl;
            cout << (7 == 7 && !(7 < 5)) << endl;
          
            return 0;
          
          }
## Math Functions :

          #include <iostream>
          #include <cmath>
          using namespace std;
          int main()
          {
            
            double x = 64;
            cout << sqrt(x) <<endl;
            cout << sqrt(50)<< endl;
            cout << round(sqrt(50))<< endl;
          
            cout << round(2.4) << endl;
            cout << round(2.5) << endl;
            cout << round(2.7) << endl;
            cout << round(2.8) + round(2.3) << endl;
          
            cout << pow(2,4) << endl;

            cout << ceil(2.9)<< endl;
            cout << ceil(-2.9) << endl;
          
            cout << floor(2.9) << endl;
            cout << floor(-2.9 ) << endl;
            
            cout << abs(-10) << endl;
            cout << abs(10) << endl;
            return 0;
          
          }

## Task 16 Rectangle Area by Diagonal & Side:
          #include <iostream>
          #include <cmath>
          using namespace std;
          int main()
          {
            
            int a, d;
            cout <<"Please enter a number" << endl;
            cin>> a ;
          
            cout <<"please enter d number" << endl;
            cin>> d ;
          
            cout<< "Area = " << a * sqrt(pow(d,2)-pow(a,2)) << endl;
          
            return 0;
          
}
## Calculate Circle Area :
               #include <iostream>
               #include <cmath>
               using namespace std;
               int main()
               {
                 
                 int r ;
                 cout << "please enter r value" << endl;
                 cin>>r;
               
                 cout << 3.14 * pow(r , 2);
               
                 return 0;
               
               }
##   Calculate Circle Area by Diameter :      

          #include <iostream>
          #include <cmath>
          using namespace std;
          int main()
          {
            
            int D;
            cout << "please enter d value" << endl;
            cin >> D;
          
            cout << "Area" <<( 3.14 * pow(D,2) ) / 4 << endl;
            return 0;
          
          }
## Calculate Circle Area Inscribed in a Square :    

          #include <iostream>
          #include <cmath>
          using namespace std;
          int main()
          {
            int a ;
            cout << "Please enter a value" << endl;
            cin >> a;
          
            cout << "area = "<<3.14 * pow(a/2,2)<<endl;
            cout << "area = "<<(3.14 * pow(a,2)) / 4 <<endl;
            return 0;
          
          }
## Circle Area Along the Circumference :

           #include <iostream>
          #include <cmath>
          using namespace std;
          int main()
          {
            int l ;
            cout << "please enter l value" << endl;
            cin >> l;
          
            cout << "Area ="<<pow(l,2) / (4 * 3.14) << endl;
          
            return 0;
          
          }
          
## Circle Area inscribed in an Isosceles Triangle :

          #include <iostream>
          #include <cmath>
          using namespace std;
          int main()
          {
            int a, b ;
            cout << "Please enter a value" << endl;
            cin >> a;
          
            cout << "please enter b value" << endl;
            cin >> b;
          
            cout << "Area ="<<3.14 * (pow(b,2)/4) * ((2 * a -b ) / (2 * a + b)) << endl;
          
            return 0;
          
          }

## Circle Area Described Around an Arbitrary Triangle 

  
          #include <iostream>
          #include <cmath>
          using namespace std;
          int main()
          {
            int a , b , g ;
            int p = (a + b + g)/2;
            int t = (a * b * g )/( 4 * sqrt(p * (p -a) * (p -b) *(p -g) ));
            cout << "please enter a value" << endl;
            cin >>a ;
          
            cout << "please enter b value " << endl;
            cin >> b ;
          
            cout << "please enter g value " << endl;
            cin >> g ;
          
            cout << "Area = " << 3.14 * pow(t,2 ) ;
          
            return 0;
          
          }
