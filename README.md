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
            int a, b, g ;
            int p = (a + b + g)/2;
            int t = (a * b * g )/( 4 * sqrt(p * (p -a) * (p -b) *(p -g) ));
            cout << "Please enter a value" << endl;
            cin >>a ;
          
            cout << "please enter b value " << endl;
            cin >> b ;
          
            cout << "please enter g value " << endl;
            cin >> g ;
          
            cout << "Area = " << 3.14 * pow(t,2 ) ;
          
            return 0;
          
          }
## Pover of 2,3,4:

          #include <iostream>
          #include <cmath>
          using namespace std;
          int main()
          {
            int a, b, g ;
            int p = (a + b + g)/2;
            int t = (a * b * g )/( 4 * sqrt(p * (p -a) * (p -b) *(p -g) ));
            cout << "Please enter a value" << endl;
            cin >>a ;
          
            cout << "please enter b value " << endl;
            cin >> b ;
          
            cout << "please enter g value " << endl;
            cin >> g ;
          
            cout << "Area = " << 3.14 * pow(t,2 ) ;
          
            return 0;
          
          }
## Power of M:
          #include <iostream>
          #include <cmath>
          using namespace std;
          int main()
          {
            int number, M ;
            cout<< "Please enter number: ";
            cin >> number;
          
            cout << "Please enter M: ";
            cin >> M;
          
            cout << "Power Number of M = "<< pow(number,M)<<endl;
          
            return 0;
          
          }
Task Duration In Seconds:

          #include <iostream>
          #include <cmath>
          using namespace std;
          int main()
          {
            int days, hours, minutes, seconds;
            cout << "Please enter days: "<<endl;
            cin>>days;
          
            cout << "Please enter hours: "<<endl;
            cin>>hours;
          
            cout << "Please enter minutes: "<<endl;
            cin>>minutes;
          
            cout << "Please enter seconds: "<<endl;
            cin>>seconds;
            
            int d = days * 24 * 60 * 60;
            int h = hours * 60 * 60;
            int m = minutes * 60 ;
            cout << "Total of seconds: "<< d + h + m + seconds;
            return 0;
          
          }
          
## Seconds to Days Hours Minutes Seconds :

          #include <iostream>
          #include <cmath>
          using namespace std;
          int main()
          {
            int TotalSeconds ;
            cout << "Please enter total seconds: " ;
            cin>> TotalSeconds;
            
            const int secondsPerDay =  24 * 60 * 60 ;
            const int secondsPerHour =  60 * 60 ;
            const int secondsPerMinute =  60 ;
          
            int Remainder = 0 ;
            cout<< "days = "<< floor(TotalSeconds /secondsPerDay)<< endl; 
            Remainder = TotalSeconds % secondsPerDay ;
            cout<< "hours = "<< floor(Remainder /secondsPerHour) << endl; 
            Remainder = Remainder % secondsPerHour;
            cout<< "minute = "<< floor(Remainder / secondsPerMinute)<< endl; 
            Remainder = Remainder % secondsPerMinute;
            cout<< "second = " << Remainder ;
            return 0;
          
          }

## function code example:

          #include <iostream>
          #include <string>
          #include <cmath>
          using namespace std;
          
          void DisplayMyCardInfoFunction(){
            cout<<"*****************************"<<endl;
            cout<< "Name : Mustafa Sad"<< endl;
            cout<< "Age : 23 Years"<< endl;
            cout<< "City : MitGamer"<< endl;
            cout<< "Country : Egypt"<< endl;
            cout<<"*****************************"<<endl;
          }
          void PrintSquareStarFunction(){
            cout<<"*******************"<<endl;
            cout<<"*******************"<<endl;
            cout<<"*******************"<<endl;
            cout<<"*******************"<<endl;
          }
          void PrintILoveProgrammingFunction(){
            cout<<"I Love Programming"<<endl;
            cout<<"I Promise to be the best developer ever1"<<endl;
            cout<<"I know it will take some time to practice, but I will achieve my goal "<<endl;
            cout<<"Best Regards, Mohammed Abu-Hahdoud"<<endl;
          }
          void PrintH(){
            cout<<"*      *"<<endl;
            cout<<"*      *"<<endl;
            cout<<"********"<<endl;
            cout<<"*      *"<<endl;
            cout<<"*      *"<<endl;
          }
          int main(){
            DisplayMyCardInfoFunction();
            PrintSquareStarFunction();
            PrintH();
            PrintILoveProgrammingFunction();
            return 0;
          }
## getLine example code:
          #include <iostream>
          #include <string>
          #include <cmath>
          using namespace std;
          
          
          int main(){
            // Example for getline() function
          
            int number;
            string name, country;
          
            cout<<"Please Enter Your number"<<endl;
            cin>>number;
            cout<<"Please Enter Your Name"<<endl;
            cin.ignore(1,'\n');
            getline(cin, name);
            cout<<"Please Enter Your Country"<<endl;
            cin>>country;
          
            cout<<"your Number is: "<<number<<endl;
            cout<<"your name is: "<<name<<endl;
            cout<<"your country is: "<<country<<endl;
            return 0;
          }
  ## Function VS Procedure :
          #include <iostream>
          #include <string>
          #include <cmath>
          using namespace std;
          
          void MySumProcedure()
          {
            int num1, num2;
            cout << "Please Enter Number1" << endl;
            cin >> num1;
            cout << "Please Enter Number2" << endl;
            cin >> num2;
            cout << num1 + num2<<endl;
          }
          int MySumFunction()
          {
            int num1, num2;
            cout << "Please Enter Number1" << endl;
            cin >> num1;
            cout << "Please Enter Number2" << endl;
            cin >> num2;
            return num1 + num2;
          }
          int main()
          {
            MySumProcedure();
            cout<<MySumFunction() << endl;
          
            return 0;
          }
## Parameter Function :
          #include <iostream>
          #include <string>
          #include <cmath>
          using namespace std;
          
          // parameters functions
          int MyFunction(int num1, int num2){
            return num1 * num2;
          }
          int main()
          {
            // cout<<MyFunction(20 , 30)<<endl;
            // cout<<MyFunction(40 , 30)<<endl;
            // cout<<MyFunction(3 , 30)<<endl;
            // cout<<MyFunction(1 , 30)<<endl;
          
            int num1, num2;
            cin>>num1;
            cin>>num2;
            cout<<MyFunction(num1,num2)<<endl;
            return 0;
          }
## Procedure Function Example1 :
          #include <iostream>
          #include <string>
          #include <cmath>
          using namespace std;
          
          // parameters functions
          void MyFunction(){
            int num1, num2, num3;
            cout<<"Please Enter Number1"<<endl;
            cin>>num1;
            cout<<"Please Enter Number2"<<endl;
            cin>>num2;
            
            cout<<"number1 is: "<<num1<<endl;
            cout<<"number2 is: "<<num2<<endl;
          
            // Swap the two numbers together 
            num3 = num1;
            num1 = num2;
            num2 = num3;
            cout<<"number1 is: "<<num1<<endl;
            cout<<"number2 is: "<<num2<<endl;
            
          }
          int main()
          {
            MyFunction();
            
            return 0;
          }
## Function Example2:
## Calculate Area Rectangle:
          #include <iostream>
          #include <string>
          #include <cmath>
          using namespace std;
          
          // parameters functions
          int MyFunction(int a , int b){
            return a*b;
          }
          int main()
          {
            int a,b;
            cout<<"Please Enter a Value"<<endl;
            cin>>a; 
            cout<<"Please Enter b Value"<<endl;
            cin>>b;
            
            cout<<"Area = "<<MyFunction(a,b)<<endl ; 
            return 0;
          }
## Function Example3:
## Calculate Rectangle Area through Diagonal and side area:

          #include <iostream>
          #include <string>
          #include <cmath>
          using namespace std;
          
          // parameters functions
          int AreaFunction(int a, int d)
          {
            return a * sqrt(pow(d, 2) - pow(a, 2));
          }
          int main()
          {
            int a, d;
            cout << "Please Enter a Value" << endl;
            cin >> a;
            cout << "Please Enter d Value" << endl;
            cin >> d;
          
            cout<<"Result of Area = "<< AreaFunction(a,d)<<endl;
            return 0;
          }
## Function Example 3:
## Calculate circle area:
          #include <iostream>
          #include <string>
          #include <cmath>
          using namespace std;
          
          // parameters functions
          void CircleFunction(){
            int r, Area;
            cout<<"Please Enter r Value"<<endl;
            cin>>r;
          
            Area = 3.14 * pow(r,2);
            cout<<"Area = "<<Area<<endl;
          }
          int main()
          {
            CircleFunction();
            return 0;
          }
## Function Example4:
## Calculate circle area:
          #include <iostream>
          #include <string>
          #include <cmath>
          using namespace std;
          
          // parameters functions
          int CircleFunction(int d){
            return (3.14 * pow(d,2)) / 4;
          }
          
          int main()
          {  
            int d;
            cout<<"Please Enter d value: "<<endl;
            cin>>d;
            cout<<"Area = "<<CircleFunction(d)<<endl;
            return 0;
          }
## Procedure function example4:
          #include <iostream>
          #include <string>
          #include <cmath>
          using namespace std;
          
          // parameters procedure function
          void CircleFunction(){
            int a;
            cout<<"Please Enter A value:"<<endl;
            cin>>a ;
            cout<<"Area = "<<(3.14* pow(a,2))/4<<endl;
          
          }
          int main()
          {  
            CircleFunction();
            return 0;
          }
## circle area function example:
          #include <iostream>
          #include <string>
          #include <cmath>
          using namespace std;
          
          // parameters procedure function
          int CircleFunction(int l ){
            return pow(l,2) /(4*3.14 );
          }
          int main()
          {  
            int l;
            cout<<"Please Enter L value"<<endl;
            cin>>l;
            cout<<"area = "<<CircleFunction(l)<<endl;
            return 0;
          }

## Calculate Circle Area :
          #include <iostream>
          #include <string>
          #include <cmath>
          using namespace std;
          
          // parameters procedure function
          int AreaFunction(int a , int b ){
            return 3.14 *( pow(b,2)/4)*((2*a-b)/(2*a+b));
          }
          int main()
          {  
            int b, a; 
            cout<<"Please Enter a value: "<<endl;
            cin>>a;
            cout<<"Please Enter b value: "<<endl;
            cin>>b;
            cout<<"value= "<<AreaFunction(a,b)<<endl;
          
            return 0;
          }
## function code Example 5:
          #include <iostream>
          #include <string>
          #include <cmath>
          using namespace std;
          
          // parameters procedure function
          double AreaFunction(int a, int b, int c)
          {
            double p = (a + b + c) / 2;
            double h = sqrt(p * (p - a) * (p - b) * (p - c));
            return 3.14 * (pow((a * b * c) /( 4 * h), 2));
          }
          int main()
          {
            int a, b, c;
            cout << "Please Enter a and b and c values" << endl;
            cin >> a >> b >> c;
          
            cout << "Values: " << AreaFunction(a, b, c) << endl;
            return 0;
          }
## task pow(x,x) example:

          #include <iostream>
          #include <string>
          #include <cmath>
          using namespace std;
          
          // parameters procedure function
          void task-function(){
            int num;
            cout<<"Please Enter number: "<<endl;
            cin>>num;
            cout<<"Number^2 = "<<pow(num,2 )<<endl;
            cout<<"Number^3 = "<<pow(num,3 )<<endl;
            cout<<"Number^4 = "<<pow(num,4 )<<endl;
          }
          int main()
          {
            task-Function();
            return 0;
          }
          ****

## Example function for calculating the day and hours & minutes and seconds :
          void TimeFunction()
          {
            int total_seconds;
            int remainder = 0;
            const int  second_per_day = 24 * 60 * 60;
            const int  second_per_hour = 60 * 60;
            const int  second_per_minutes = 60;
          
            cout << "Please Enter TotalOF Seconds: " << endl;
            cin >> total_seconds;
          
            cout<<"days = "<<floor(total_seconds / second_per_day)<<endl;
            remainder = total_seconds % second_per_day;
          
            cout<<"hours = "<<floor( remainder / second_per_hour)<<endl;
            remainder = total_seconds % second_per_hour;
          
            cout<<"minute = "<< floor(remainder / second_per_minutes)<<endl;
            remainder = remainder % second_per_minutes;
            
            cout<<"second = "<< remainder ;
          }
          int main()
          {
            TimeFunction();
            return 0;
          }























