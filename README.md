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
##
