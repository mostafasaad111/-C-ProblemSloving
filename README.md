# Learning logic_of_programming by C++  && Problem Solving.
# Functional Programming && OOP Programming.

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
## 5-increment && decrement example :

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
## 6-Assignment Operators :
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

## 7- Relational Operators :

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
## 8- Relational 0perateor 2 :


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
## 9- Logical Operators :
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
## 10- Math Functions :

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

## 11-  Rectangle Area by Diagonal & Side:
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
## 12-- Calculate Circle Area :
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
##  13- Calculate Circle Area by Diameter :      

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
## 14- Circle Area Along the Circumference :

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
          
## 15- Circle Area inscribed in an Isosceles Triangle :

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

## 16- Circle Area Described Around an Arbitrary Triangle 

  
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
## 17- Pover of 2,3,4:

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
## 18- Power of M:
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
          
## 19-  Seconds to Days Hours Minutes Seconds :

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

## 20- function code example:

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
## 21-  getLine example code:
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
  ## 22- Function VS Procedure :
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
## 23 - Parameter Function :
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
## 24- Procedure Function Example1 :
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
##25-  Calculate Area Rectangle:
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
## 26- Calculate Rectangle Area through Diagonal and side area:

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
## local vs global:
          #include <iostream>
          #include <string>
          #include <cmath>
          using namespace std;
          int x = 600; // global scope
          
          void MyFunction(){ //procedure function
            int x= 400;
            cout<<"the local value is: "<<x<<endl;
          }
          
          int main(){
            int x = 300;
            cout<<"the local value is: "<<x<<endl;
            
            ::x++;
            cout<<"the global value is: "<<::x<<endl;
          }
## by value VS by reference:

          #include <iostream>
          #include <string>
          #include <cmath>
          using namespace std;
          
          void MyFunction(int num1){
            cout<<"num1: "<<num1<<endl;
            num1 = 7000;
            cout<<"num1: "<<num1<<endl;
          
          }
          int main(){
            int num1 = 1000;
            MyFunction(num1);
            cout<<"num1: "<<num1<<endl;
          }
*********************************************************

          #include <iostream>
          #include <string>
          #include <cmath>
          using namespace std;
          
          void MyFunction(int &num1){
            cout<<"num1: "<<num1<<endl;
            num1 = 7000;
            cout<<"num1: "<<num1<<endl;
          
          }
          int main(){
            int num1 = 1000;
            cout<<"num1: "<<num1<<endl;
            MyFunction(num1);
            cout<<"num1: "<<num1<<endl;
            cout<<"num1 address = "<<&num1<<endl;
          }****

## Swap function :
          #include <iostream>
          #include <string>
          #include <cmath>
          using namespace std;
          
          void Swap(int &num1, int &num2)
          {
            cout << "Procedure num1 = " << num1 << "Procedure num2 = " << num2 << endl;
            int temp;
            temp = num1;
            num1 = num2;
            num2 = temp;
            cout << "Procedure num1 = " << num1 << "Procedure num2 = " << num2 << endl;
          }
          int main()
          {
            int num1, num2;
          
            cout << "Please Enter Number1 = " << endl;
            cin >> num1;
          
            cout << "Please Enter Number1 = " << endl;
            cin >> num2;
          
            cout << "Before Swap num1 = " << num1 << " , num2 = " << num2 << endl;
          
            swap(num1, num2);
            cout << "After Swap inside main the function num1 = " << num1 << " , num2 = " << num2 << endl;
          
            return 0;
          }

## Structure and Function example:
          #include <iostream>
          #include <string>
          #include <cmath>
          using namespace std;
          
          // structure and function 
          struct strinfo{
            string FirstName;
            string LastName;
            int Age;
            string phone;
          };
          void ReadInfo(strinfo &info){
            cout<<"Please Enter First Name: "<<endl;
            cin>>info.FirstName;
          
            cout<<"Please Enter Last Name: "<<endl;
            cin>>info.LastName;
          
            cout<<"Please Enter your age: "<<endl;
            cin>>info.Age;
          
            cout<<"Please Enter your phone number: "<<endl;
            cin>>info.phone;
          
          };
          void PrintInfo(strinfo info){
          
            cout<<"\n*****************************\n"<<endl;
            cout<<"first name: "<<info.FirstName<<endl;
            cout<<"last name: "<<info.LastName<<endl;
            cout<<"phone number: "<<info.phone<<endl;
            cout<<"age : "<<info.Age<<endl;
            cout<<"\n*****************************\n"<<endl;
          
          };
          int main()
          {
            strinfo person1Info;
            ReadInfo(person1Info);
            PrintInfo(person1Info);
          
            strinfo person2Info;
            ReadInfo(person2Info);
            PrintInfo(person2Info);
            return 0;
          }

## array example:
          #include <iostream>
          #include <string>
          #include <cmath>
          using namespace std;
          
          int main()
          {
            int x[5] = {23,44,55,23,56};
            cout<<x[0]<<" "<<x[1]<<" "<<x[2]<<endl;
            cout<<x[0]<<endl;
            cout<<x[1]<<endl;
            cout<<x[2]<<endl;
            cout<<x[3]<<endl;
            cout<<x[2] + x[4]<<endl;
            
            int i[4];
            i[0]= 30;
            i[1]=40;
            cout<< i[0] + i[1]<<endl;
            return 0;
          }

## Array Example 2:
          #include <iostream>
          #include <string>
          #include <cmath>
          using namespace std;
          
          struct StrArray_Value{
            float x[3];
          };
          void ReadArrayValue(StrArray_Value &array){
            cout<<"Please Enter Grade1: "<<endl;
            cin>>array.x[0];
            
            cout<<"Please Enter Grade2: "<<endl;
            cin>>array.x[1];
          
            cout<<"Please Enter Grade3: "<<endl;
            cin>>array.x[2];  
          
          };
          void PrintArrayValue(StrArray_Value array){
            float average = (array.x[0] + array.x[1] + array.x[2]) /3;
            cout<<"The average of grades is : "<< average <<endl;
          };
          int main()
          {
            StrArray_Value array1;
            ReadArrayValue(array1);
            PrintArrayValue(array1);
            return 0;
          }

## Write a program to ask the user to enter age if the age is between 18 and 45 print "valid Age" otherwise print "invalid Age":
          #include <iostream>
          #include <string>
          #include <cmath>
          using namespace std;
          
          int main()
          {
            int age ;
            cout<<"Please enter age: "<<endl;
            cin>>age;
            if(age >=18 && age <= 45)
            {
                cout<<"Valid Age: "<<endl;
            }
            else{
              cout<<"Invalid Age: "<<endl;
            }
            return 0;
          }
## Write a program to read the ATM PIN code from the user :
          #include <iostream>
          #include <string>
          #include <cmath>
          using namespace std;
          
          int main()
          {
            int pinCode ;
            cout<<"Please Enter pin Code"<<endl;
            con>>pinCode;
          
            if(pinCode == 1234){
              cout<<'7500';
            }
            else{
              cout<<"Wong Ping"<<endl;
            }
            return 0;
          }
## Write a program to ask the user to enter Grade:
          #include <iostream>
          #include <string>
          #include <cmath>
          using namespace std;
          
          int main()
          {
            int Grade;
            cout<<"Please enter a grade number: "<<endl;
            cin>>Grade;
            if(Grade >= 90 || Grade <= 100)
            {
              cout<<"A";
            }
            else if (Grade >= 80 || Grade <= 89)
            {
              cout<<"B";
            }
            else if (Grade >= 70 || Grade <=79)
            {
              cout<<"C";
            }
            else 
            {
              cout <<"F";
            }
            return 0;
          }
## Write a program to ask the user to enter TotalSales:

          #include <iostream>
          #include <string>
          #include <cmath>
          using namespace std;
          
          int main()
          {
            int Total_Sales_Amount;
            cout << "Please Enter Total_Sales_Amount:" << endl;
            cin >> Total_Sales_Amount;
          
            if (Total_Sales_Amount >= 1000000)
            {
              int value;
              value = Total_Sales_Amount * .01;
              cout << "the value = " << value;
            }
            else if (Total_Sales_Amount <= 1000000 || Total_Sales_Amount > 500000)
            {
              int value;
              value = Total_Sales_Amount * .02;
              cout << "the value = " << value;
            }
            else if (Total_Sales_Amount <= 500000 || Total_Sales_Amount > 100000)
            {
              int value;
              value = Total_Sales_Amount * .03;
              cout << "the value = " << value;
            }
            else if (Total_Sales_Amount <= 100000 || Total_Sales_Amount > 50000)
            {
              int value;
              value = Total_Sales_Amount * .05;
              cout << "the value = " << value;
            }
            else
            {
              cout << "the value = " << 0;
            }
            return 0;
          }
## Write a program to ask the user to enter :
 . number1
 . number2
 . operation type
 
          #include <iostream>
          #include <string>
          #include <cmath>
          using namespace std;
          
          int main()
          {
            int num1, num2;
            char operation_type;
            cout << "Please enter num1 " << endl;
            cin >> num1;
            cout << "Please enter num2 " << endl;
            cin >> num2;
            cout << "Please enter operation_type " << endl;
            cin >> operation_type;
          
            if (operation_type == '+')
            {
              cout << "sum = " << num1 + num2 << endl;
            }
            else if (operation_type == '-' )
            {
              cout << "sum = " << num1 - num2 << endl;
            }
            else if (operation_type == '*')
            {
              cout << "sum = " << num1 * num2 << endl;
            }
            else if (operation_type == '/')
            {
              cout << "sum = " << num1 / num2 << endl;
            }
          
            return 0;
          }

## Write a program to ask the user to enter:
. Day

          #include <iostream>
          #include <string>
          #include <cmath>
          using namespace std;
          
          int main()
          {
            int Day;
            cout<<"Please enter a number between 1 and 7: "<<endl;
            cin>>Day;
          
            if (Day == 1)
            {
              cout << "Sunday" << endl;
            }
            else if (Day == 2)
            {
              cout << "Monday" << endl;
            }
            else if (Day == 3)
            {
              cout << "Tuesday" << endl;
            }
            else if (Day == 5)
            {
              cout << "Thursday" << endl;
            }
            else if (Day == 6)
            {
              cout << "Friday" << endl;
            }
            else if (Day == 7)
            {
              cout << "Saturday" << endl;
            }
            else
            {
              cout << "Wrong Day" << endl;
            }
            return 0;
          }
## enum with if statement:

          #include <iostream>
          #include <string>
          #include <cmath>
          using namespace std;
          enum enScreenColor  {red = 1, blue = 2, green = 3, yellow = 4};
          int main()
          {
            cout << "**********************\n";
            cout << "Please chose the number \n";
            cout << "(1) red \n";
            cout << "(2) blue \n";
            cout << "(3) green \n";
            cout << "(4) yellow \n";
            cout << "**********************\n";
          
            int c;
            enScreenColor color;
          
            cin >> c;
            color = (enScreenColor)c;
            if (color == enScreenColor::red)
            {
              system("color 4F");
            }
            else if (color == enScreenColor::blue)
            {
              system("color 1F");
            }
            else if (color == enScreenColor::yellow)
            {
              system("color 6F");
            }
            else if (color == enScreenColor::green)
            {
              system("color 2F");
            }
          
            return 0;
          }
##example 2:

                         #include <iostream>
                         #include <string>
                         #include <cmath>
                         using namespace std;
                         enum enCountryChoice
                         {
                           Jordan = 1,
                           Tunisia = 2,
                           Algeria = 3,
                           Oman = 4,
                           Egypt = 5,
                           Iraq = 6,
                           other = 7
                         };
                         int main()
                         {
                           cout<< "********************************\n";
                           cout<< "Please chose the number \n";
                           cout<< "(1) jordan\n";
                           cout<< "(2) tunisa\n";
                           cout<< "(3) algeria\n";
                           cout<< "(4) oman\n";
                           cout << "(5) egypt\n";
                           cout << "(6) iraq\n";
                           cout << "(7) other\n";
                           cout << "*********************************\n";
                           int c;
                           cin>>c;
                           enCountryChoice country;
                           country = (enCountryChoice)c;
                           if (country == enCountryChoice::jordan)
                           {
                             cout << "your country is Jordan\n";
                           }
                           else if (country == enCountryChoice::egypt)
                           {
                             cout << "your country is egypt\n";
                           }
                           else if (country == enCountryChoice::tunisa)
                           {
                             cout << "your country is tunisa\n";
                           }
                           else if (country == enCountryChoice::algeria)
                           {
                             cout << "your country is algeria\n";
                           }
                           else if (country == enCountryChoice::iraq)
                           {
                             cout << "your country is iraq\n";
                           }
                           else if (country == enCountryChoice::oman)
                           {
                             cout << "your country is oman\n";
                           }
                           else
                           {
                             cout << "your country not found\n";
                           }
                           return 0;
                         }
                                   
## swicth_case():
               #include <iostream>
               #include <string>
               #include <cmath>
               using namespace std;
               
               int main()
               {
                 int day;
                 cout<<"Please enter a day"<<endl;
                 cin >> day;
                 
                 switch (day)
                 {
                 case 1:
                   cout<<"sun\n";
                   break;
                 case 2:
                   cout<<"Monday\n";
                   break;
                 case 3:
                   cout<<"Tuesday\n";
                   break;
                 case 4:
                   cout<<"Wednesday\n";
                   break;
                 case 5:
                   cout<<"Thursday\n";
                   break;
                 case 6:
                   cout<<"Friday\n";
                   break;
                 case 7:
                   cout<<"Saturday\n";
                   break;
                 default:
                   break;
                 }
                 
                 return 0;
               }
## enum switch case example:
          
          #include <iostream>
          #include <string>
          #include <cmath>
          using namespace std;
          enum enScreenColor
          {
            red = 1,
            green = 2,
            blue = 3,
            yellow = 4
          };
          void printScreen()
          {
            cout << "********************\n";
            cout << "Please choose a color: " << endl;
            cout << "(1)red \n";
            cout << "(2)green \n";
            cout << "(3)blue \n";
            cout << "(4)yellow \n";
            cout << "********************\n";
          }
          int main()
          {
            PrintScreen();
            int c;
            cin >> c;
            enScreenColor color;
            color = (enScreenColor)c;
          
            switch (color)
            {
            case enScreenColor::red:
              system("color 4f");
              break;
            case enScreenColor::blue:
              system("color 1f");
              break;
            case enScreenColor::green:
              system("color 2f");
              break;
            case enScreenColor::yellow:
              system("color 6f");
              break;
          
              system("color 4f");
              break;
            }
            return 0;
          }
## Nested Function enum example:
          #include <iostream>
          #include<string>
          #include <cmath>
          using namespace std;
          enum enWeekDay{sun=1,mon=2,tue=3,wed=4,thu=5,fri=6 ,sat=7};
          
          void PrintScreen(){
            cout<<"================\n";
            cout<<"     weekday    \n";
            cout<<"================\n";
            cout<<"1: sunday"<<endl;
            cout<<"2: Monday"<<endl;
            cout<<"3: Tuesday"<<endl;
            cout<<"4: Wednesday"<<endl;
            cout<<"5: Thursday"<<endl;
            cout<<"6: Friday"<<endl;
            cout<<"7: Saturday"<<endl;
            cout<<"choose your day"<<endl;
          }
          enWeekDay ReadWeekDay(){
            enWeekDay WeekDay;
            int wd;
            cin>>wd;
            return (enWeekDay)wd;
          
          }
          string GetWeekDay(enWeekDay WeekDay){
            switch(WeekDay){
              case enWeekDay::fri:
                return "Fri";
                break;
              case enWeekDay::thu:
                return "thu";
                break;
              case enWeekDay::tue:
                return "Tue";
                break;
              case enWeekDay::wed:
                return "Wed";
                break;
              case enWeekDay::mon:
                return "monday";
                break;
              case enWeekDay::sat:
                return "tuesday";
                break;
              case enWeekDay::sun:
                return "saturday";
                break;
            
          }
          }
          int main(){
            PrintScreen();
            cout<<"today is: "<<GetWeekDay(ReadWeekDay())<<endl;
          }
          
## Write a program to print numbers from 1 to n:

               #include <iostream>
               #include <string>
               #include <cmath>
               using namespace std;
               
               int main()
               {
                 cout << "please enter number \n";
                 int b;
                 cin >> b;
                 for (int i; i <= b; i++)
                 {
                   cout << i<<endl;
                 }
                 return 0;
               }
## Write a program to print numbers from n to 0:
          #include <iostream>
          #include <string>
          #include <cmath>
          using namespace std;
          
          int main()
          {
            cout << "please enter number \n";
            int n;
            cin >> n;
            for (int i=n; i >= 0 ; i--)
            {
              cout << i<<endl;
            }
            return 0;
          }

## Write a program to sum odd numbers from 1 to N:
          #include <iostream>
          #include <string>
          #include <cmath>
          using namespace std;
          
          int main()
          {
            cout << "please enter number \n";
            int n;
            int sum = 0;
            cin >> n;
            for (int i = 1; i <= n; i++)
            {
              if (i % 2 != 0)
              {
                sum = sum + i;
              }
            }
            cout << "sum of odd numbers from 1 to n = " << n << " is: " << sum << endl;
            return 0;
          }
## Write a program to sum even numbers from 1 to N:
               #include <iostream>
               #include <string>
               #include <cmath>
               using namespace std;
               
               int main()
               {
                 cout << "please enter number \n";
                 int n;
                 int sum = 0;
                 cin >> n;
                 for (int i = 2; i <= n; i = i + 2)
                 {
                    sum += i;
                 }
                 cout << "sum of odd numbers from 1 to n = " << n << " is: " << sum << endl;
                 return 0;
               }
               
## Write a program to calculate factorial of N!:
               #include <iostream>
               #include <string>
               #include <cmath>
               using namespace std;
               
               int main()
               {
                 int sum = 1;
                 for (int i=6 ; i > 0  ; i--)
                 {
                    sum *= i;
                 }
                 cout << "sum of odd numbers from 1 to n = " << sum << endl;
                 return 0;
               }
## Write a program print char from a to z :
          #include <iostream>
          #include <string>
          #include <cmath>
          using namespace std;
          
          int main()
          {
            for(int i = 65 ; i <= 90 ; i++){
              cout<<char(i)<<endl;
            }
            return 0;
          }
## Loop & Array Example:
          #include <iostream>
          #include <string>
          #include <cmath>
          using namespace std;
          
          void ReadArrayData(int Arr1[100], int &length)
          {
            cout << "Please enter a number of elements:\n";
            cin >> length;
          
            for (int i = 0; i <= length - 1; i++)
            {
              cout << "please enter number" << i + 1 << endl;
              cin >> Arr1[i];
            }
          }
          void printArrayData(int Arr1[100], int length)
          {
            for (int i = 0; i <= length - 1; i++)
            {
              cout << "number [" << i + 1 << "]: " << Arr1[i] << endl;
            }
          }
          int CalculateArraySum(int Arr1[100], int length)
          {
            int sum;
            for (int i = 0; i <= length - 1; i++)
            {
              sum += Arr1[i];
            }
            return sum;
          }
          float CalculateArrayAverage(int Arr1[100], int length)
          {
            for (int i = 0; i <= length - 1; i++)
            {
              return (float)CalculateArraySum(Arr1, length)/length;
            }
          }
          int main()
          {
            int Arr1[100], length = 0;
            ReadArrayData(Arr1, length);
            printArrayData(Arr1, length);
          
            cout<<"\n************************\n";
            int sum;
            sum =CalculateArraySum(Arr1,length);
          
            cout<<"sum = "<<sum<<endl;
            cout<<"average = "<<sum / length<<endl;
            return 0;
          }
 ## loop Print AA TO ZZ:
           #include <iostream>
          #include <string>
          #include <cmath>
          using namespace std;
          
          int main()
          {
            for (int i = 65; i <= 90; i++)
            {
              cout  << char(i) << endl;
              for (int j = 65; j <= 90; j++)
              {
                cout <<char(i)<<char(j) << endl;
              }
              cout<<"----------------"<<endl;
            }
          }
          
## Print the shape:
*************
***********
*********
*******
*****
***
**
*

               int main()
               {
                 for (int i = 1; i <= 10; i++)
                 {
                   for (int j = 10; j >= i; j--)
                   {
                     cout << "*" ;
                   }
                   cout<<endl;
                 }
               }
## Print The Shape:
12345678910
123456789
12345678
1234567
123456
12345
1234
123
12
1

          #include <iostream>
          #include <string>
          #include <cmath>
          using namespace std;
          
          int main()
          {
            for (int i = 10; i >= 1; i--)
            {
            
              for (int j = 1; j <= i; j++)
              {
                cout << j ;
              }
              cout<<endl;
            }
          }
## Print The Shape:
A
AB
ABC
ABCD
ABCDE
ABCDEF
          
          #include <iostream>
          #include <string>
          #include <cmath>
          using namespace std;
          
          int main()
          {
            for (int i = 65; i <= 70; i++)
            {
            
              for (int j = 65; j <= i; j++)
              {
                cout << char(j) ;
              }
              cout<<endl;
            }
          }
## Print The Shape:
1
12
123
1234
12345
123456
1234567
12345678
123456789
12345678910

          #include <iostream>
          #include <string>
          #include <cmath>
          using namespace std;
          
          int main()
          {
            for (int i = 1; i <= 10; i++)
            {
            
              for (int j = 1; j <= i; j++)
              {
                cout << j ;
              }
              cout<<endl;
            }
          }

## Print The Shape:
12345678910
2345678910
345678910
45678910
5678910
678910
78910
8910
910
10

          #include <iostream>
          #include <string>
          #include <cmath>
          using namespace std;
          
          int main()
          {
            for (int i = 1; i <= 10; i++)
            {
          
              for (int j = i; j <= 10; j++)
              {
                cout << j;
              }
              cout << endl;
            }
          }

## While LOOP Example1:

          #include <iostream>
          #include <string>
          #include <cmath>
          using namespace std;
          
          int main()
          {
            int i = 1;
            while (i <= 5)
            {
              cout << i << "\n";
              i++;
            }
          }
## While LOOP Example:

         #include <iostream>
          #include <string>
          #include <cmath>
          using namespace std;
          
          int main()
          {
            int Number ;
            cout<<"Please enter a positive number."<<endl;
            cin>>Number;
            while(Number <0){
              cout<<"Please enter a positive number."<<endl;
              cin>>Number;
            }
            cout<<"\n the number positive number is "<<Number<<endl;
          }

## While LOOP Example 2 :

          #include <iostream>
          #include <string>
          #include <cmath>
          using namespace std;
          int ReadIntNum(int From, int To)
          {
            int Number;
            cout << "Please enter number From" << From << " to " << To << endl;
            cin >> Number;
          
            while (Number < From || Number > To)
            {
              cout << "Wrong Number" << endl;
              cout << "Please enter number From" << From << " to " << To << endl;
              cin >> Number;
            }
            return Number;
          }
          int main()
          {
            cout<<"\n The Number Is :" << ReadIntNum(18,45)<<endl;
            return 0;
          }
## Write a program to print numbers From 1 to N:

          #include <iostream>
          #include <string>
          #include <cmath>
          using namespace std;
          int UserInput(int num)
          {
            int x = 1;
            cout << "Please enter a number: " << endl;
            cin >> num;
            while (x <= num)
            {
              cout << x << endl;
              x++;
            }
          }
          int main()
          {
            int num;
            cout<<UserInput(num);
            return 0;
          }
## by Using While Loop Write a program to print numbers from 1 to N:

               #include <iostream>
               #include <string>
               #include <cmath>
               using namespace std;
               int UserInput(int num)
               {
                 int x = 1;
                 cout << "Please enter a number: " << endl;
                 cin >> num;
                 while (x <= num)
                 {
                   cout << x << endl;
                   x++;
                 }
               }
               int main()
               {
                 int num;
                 cout<<UserInput(num);
                 return 0;
               }
## by Using While Loop Write a program to print numbers from N to 1:

          #include <iostream>
          #include <string>
          #include <cmath>
          using namespace std;
          int UserInput(int num)
          {
            int x = 1;
            cout << "Please enter a number: " << endl;
            cin >> num;
            while (x <= num)
            {
              cout << num << endl;
              num--;
            }
          }
          int main()
          {
            int num;
            cout<<UserInput(num);
            return 0;
          }
## Write a program to Sum odd numbers from 1 to N (by using a while loop):

          #include <iostream>
          #include <string>
          #include <cmath>
          using namespace std;
          
          int main()
          {
            int number;
            cout << "Please enter number " << endl;
            cin >> number;
            int sum = 0;
            int x = 1;
            while (x <= number)
            {
              if (x % 2 != 0)
              {
                sum += x;
              }
              x++;
            }
            cout << "sum = " << sum << endl;
            return 0;
          }
   ## Write a program to Sum even numbers from 1 to N (by using a while loop):
               #include <iostream>
               #include <string>
               #include <cmath>
               using namespace std;
               int UserInput(){
                   int number;
                 cout << "Please enter number " << endl;
                 cin >> number;
                 int sum = 0;
                 int x = 1;
                 while (x <= number)
                 {
                   if (x % 2 == 0)
                   {
                     sum += x;
                   }
                   x++;
                 }
                 cout << "sum = " << sum << endl;
               }
               int main()
               {
                 UserInput();
                 return 0;
               }
## Write a program to calculate the factorial of N! (by using the While loop):
          
          #include <iostream>
          #include <string>
          #include <cmath>
          using namespace std;
          int CalculateFactorialNumber(){
            int number;
            cout<<"Please enter some factors\n";
            cin>>number;
            int x = 1;
            int sum = 1;
          
            while(x <= number){
              cout<<number<<endl;
              sum *=number;
              number--;
            }
            cout<<"sum = "<<sum<<endl;
          }
          int main()
          {
            CalculateFactorialNumber();
            return 0;
          }

## Write a program to ask the user to enter (by using the While loop): 
. Number 
. M 
          #include <iostream>
          #include <string>
          #include <cmath>
          using namespace std;
          int CalculatePowerOfM()
          {
            int base, power;
            cout << "please enter base :" << endl;
            cin >> base;
            cout << "please enter power :" << endl;
            cin >> power;
          
            int x = 1;
            int sum = 1;
            while (x <= power)
            {
              sum *= base;
              power--;
            }
            cout << "sum = " << sum << endl;
          }
          int main()
          {
            CalculatePowerOfM();
            return 0;
          }
## Write a program to read numbers from the user and sum them, keep reading until the user enters -99 then print the Sum on the Screen. 
          #include <iostream>
          #include <string>
          #include <cmath>
          using namespace std;
          int CalculateNumber()
          {
            int number;
            int sum = 0;
            while (number != -99)
            {
              cout << "Please enter number" << endl;
              cin >> number;
              sum += number;
            }
            cout << "sum = " << sum + 99 << endl;
          }
          int main()
          {
            CalculateNumber();
            return 0;
          }

## Write a program to print all letters A to Z (by using While Loop):
          #include <iostream>
          #include <string>
          #include <cmath>
          using namespace std;
          int PrintLetter()
          {
            int x = 65;
            int y = 90;
            while (x <= y)
            {
              cout << char(x) << endl;
              x++;
            }
          }
          int main()
          {
            PrintLetter();
            return 0;
          }
## Write a program Atm At the request of the user, he enters the password. If the number of attempts is more than three times, he will not be able to enter the password again:
          #include <iostream>
          #include <string>
          #include <cmath>
          using namespace std;
          
          void AtmPinCode()
          {
              int PinCode;
              int maxAttempts = 3;  // Set the maximum number of attempts
              cout << "Please enter a pin code: " << endl;
          
              while (maxAttempts > 0)
              {     
                  cin >> PinCode;
          
                  if (PinCode == 1234)
                  {
                      cout << "Your Balance is: 7500" << endl;
                      break;
                  }
                  else
                  {
                      cout << "Incorrect pin code. " << maxAttempts - 1 << " attempts remaining." << endl;
                      maxAttempts--;
          
                      if (maxAttempts == 0)
                      {
                          cout << "Card is locked." << endl;
                          break;
                      }
          
                      cout << "Please enter a pin code: " << endl;
                  }
              }
          }

int main()
{
    AtmPinCode();
    return 0;
}

## Write a program print number form to the number the user entered:

          #include <iostream>
          #include <string>
          #include <cmath>
          using namespace std;
          int ReadIntNum(int from , int to){
            int number;
            do{
              cout<<"Please enter a number "<<from <<" and "<<to<<":"<<endl;
              cin>>number;
          
            }while(number < from || number > to );
            return number;
          }
          int main()
          {
            cout<<"\n the number your entered is: "<<  ReadIntNum(18 , 45);
            return 0;
          }
## Break Example:

          #include <iostream>
          #include <string>
          #include <cmath>
          using namespace std;
          void print_number()
          {
            int i;
            int arr[10] = {10, 44, 55, 33, 22, 99, 88, 20, 99, 100};
            for (int i = 0; i < 10; i++)
            {
              if (arr[i] == 20)
              {
                break;
              }
              cout << arr[i] << "  \n";
            }
          }
          int main()
          {
            print_Number();
            return 0;
          }

## Continue Example:
          #include <iostream>
          #include <string>
          #include <cmath>
          using namespace std;
          void print_Number()
          {
            int i;
            int sum;
            int arr[5] = {10, 20, 55, 10, 20};
            for (i = 0; i < 5; i++)
            {
              if (arr[i] > 50)
              {
                continue;
              }
              sum += arr[i];
            }
            cout<<"sum = "<<sum<<endl;
          }
          int main()
          {
            print_Number();
            return 0;
          }
   ## Write a program that asks the user to enter your name :
          #include <iostream>
          #include <string>
          #include <cmath>
          using namespace std;
          
          string ReadName()
          {
            string name;
            cout << "Please enter your name: " << endl;
            getline(cin, name);
            return name;
          }
          void PrintName(string name)
          {
            cout << "your name is: " << name << endl;
          }
          int main()
          {
            PrintName(ReadName());
          }
## Write a program to check Odd or Even Number:
          #include <iostream>
          #include <string>
          #include <cmath>
          using namespace std;
          
          int ReadNumber()
          {
            int number;
            cout << "Please enter a number" << endl;
            cin >> number;
            return number;
          }
          void PrintNumber(int number)
          {
            if (number % 2 == 0)
            {
              cout << "your number is even" << endl;
            }else{
              cout << "your number is odd" << endl;
            }
          }
          int main()
          {
            PrintNumber(ReadNumber());
          }
## Write a program to check Odd or Even Number Another solution:

          #include <iostream>
          #include <string>
          #include <cmath>
          using namespace std;
          
          enum enNumberType
          {
            odd = 1,
            even = 2
          };
          
          int ReadNumber()
          {
            int num;
            cout << "Please enter a number." << endl;
            cin >> num;
            return num;
          }
          
          enNumberType CheckNumberType(int num)
          {
            int Result = num % 2;
            if (Result == 0)
              return enNumberType::even;
            else
              return enNumberType::odd;
          }
          
          void PrintNumberType(enNumberType numberType)
          {
            if (numberType == enNumberType::even)
              cout << "\n number is even. \n";
            else
              cout << "\n number is odd. \n";
          }
          int main()
          {
            PrintNumberType(CheckNumberType(ReadNumber()));
            return 0;
          }
## Write a progam ask the user , do you have a Driver_licesnes && Age , do you have a Recommendation::
          #include <iostream>
          #include <string>
          #include <cmath>
          using namespace std;
          struct stInfo
          {
            int age;
            bool HasRecommendation;
            bool HasDriver_license;
          };
          
          stInfo ReadInfo()
          {
            stInfo info;
          
            cout << "Please enter your age: " << endl;
            cin >> info.age;
          
            cout << "Please enter your Driver_license(true or false): " << endl;
            cin >> info.HasDriver_license;
          
            cout << "you have HasRecommendation (true or false): " << endl;
            cin >> info.HasRecommendation;
          
            return info;
          }
          bool IsAccepted(stInfo info)
          {
            if (info.HasRecommendation)
            {
              return true;
            }
            else
            {
              return (info.age > 21 && info.HasDriver_license);
            }
          };
          void PrintUserData(stInfo info)
          {
            if (IsAccepted(info))
            {
              cout << "\n Hired"<<endl;
            }
            else
            {
              cout << "\n Rejected"<<endl;
            }
          }
          
          int main()
          {
          
            PrintUserData(ReadInfo());
            return 0;
          }
## Write a program ask user enter FirstNmae && LastName:

          #include <iostream>
          #include <string>
          #include <cmath>
          using namespace std;
          struct stInfo
          {
            string FirstName;
            string LastName;
          };
          stInfo ReadInfo()
          {
            stInfo info;
            cout << "Please enter first_name: " << endl;
            cin >> info.FirstName;
          
            cout << "Please enter Last_Name: " << endl;
            cin >> info.LastName;
          
            return info;
          }
          string GetFullName(stInfo info)
          {
            string fullname = "";
            fullname = info.FirstName + " " + info.LastName;
            return fullname;
          }
          void PrintInfo(string  fullname)
          {
            cout << "your name is: " << fullname << endl;
          }
          int main()
          {
            PrintInfo(GetFullName(ReadInfo()));
            return 0;
          }
## Write a program and ask the user to enter the number and divide it / 2:
               #include <iostream>
               #include <string>
               #include <cmath>
               using namespace std;
               struct stNumber
               {
                 int number;
               };
               stNumber ReadNumber()
               {
                 stNumber num;
                 cout << "Please enter a number" << endl;
                 cin >> num.number;
                 return num;
               }
               float TotalSum(stNumber num)
               {
                 float sum;
                 sum = (float)num.number / 2;
                 return sum;
               }
               void PrintNumber(float sum)
               {
                 cout << "the number is: " << sum;
               }
               int main()
               {
                 PrintNumber(TotalSum(ReadNumber()));
                 return 0;
               }
## answer 2:
          #include <iostream>
          #include <string>
          #include <cmath>
          using namespace std;
          int ReadNumber()
          {
            int num;
            cout << "please enter your number" << endl;
            cin >> num;
            return num;
          }
          float CalculateNumber(int num)
          {
            return (float)num / 2;
          }
          void printNumber(int num)
          {
            string Result = "Half of " + to_string(num) + "is :" + to_string(CalculateNumber(num));
            cout << Result << endl;
          }
          int main()
          {
          
            printNumber(ReadNumber());
            return 0;
          }
## Write a program to ask a user about the mark if (mark >= 50, print pass) or (mark <= 50, print fail):

               #include <iostream>
               #include <string>
               #include <cmath>
               using namespace std;
               enum enPassFail
               {
                 Pass = 1,
                 Fail = 2
               };
               int ReadMark()
               {
                 int mark;
                 cout << "Please enter your mark: " << endl;
                 cin >> mark;
                 return mark;
               }
               enPassFail CheckMark(int mark)
               {
                 if (mark >= 50)
                   return enPassFail::Pass;
                 else
                   return enPassFail::Fail;
               }
               void PrintResult(int mark){
                 if(CheckMark(mark) == enPassFail::Pass)
                   cout<<"\n You Passed "<<endl;
                 else 
                   cout<<"\n You Failed "<<endl;
               }
               int main()
               {
                 PrintResult(ReadMark());
                 return 0;
               }
## Write a program that asks a user to enter 3 numbers and calculate them:

          #include <iostream>
          #include <string>
          #include <cmath>
          using namespace std;
          // Write a program that asks a user to enter 3 numbers and calculate them
          void ReadNumbers(int &Number1, int &Number2, int &Number3)
          {
            cout << "Please enter a number one \n";
            cin >> Number1;
            cout << "Please enter a number two \n";
            cin >> Number2;
            cout << "Please enter a number three \n";
            cin >> Number3;
          }
          int CalculateNumber(int Number1, int Number2, int Number3)
          {
            return Number1 + Number2 + Number3;
          }
          void PrintNumber(int total)
          {
            cout << "total is :" << total << endl;
          }
          int main()
          {
            int Number1, Number2, Number3;
            ReadNumbers(Number1, Number2, Number3);
            int total = CalculateNumber(Number1, Number2, Number3);
            PrintNumber(total);
            return 0;
          }
## Write a program that asks a user to enter 3 marks and calculate the average and if the total average >= 50 print (pass) else print (fail):

          #include <iostream>
          #include <string>
          #include <cmath>
          using namespace std;
          // Write a program ask a user enter 3 numbers and calculate them
          enum enPassFail
          {
            pass = 1,
            fail = 2
          };
          void ReadMarks(int &mark1, int &mark2, int &mark3)
          {
            cout << "enter mark1: ";
            cin >> mark1;
          
            cout << "enter mark2: ";
            cin >> mark2;
          
            cout << "enter mark3: ";
            cin >> mark3;
          }
          int sumOf3Mark3(int mark1, int mark2, int mark3)
          {
            return (mark1 + mark2 + mark3) / 3;
          }
          float calculateAverage(int mark1, int mark2, int mark3)
          {
            return (float)sumOf3Mark3(mark1, mark2, mark3);
          }
          enPassFail checkAverage(float average)
          {
            if (average >= 50)
              return enPassFail::pass;
            else
              return enPassFail::fail;
          }
          void printAverage(float average)
          {
            if (checkAverage(average) == enPassFail::pass)
              cout << "\nyour average is: " << average << " and  your pass";
            else
              cout << "\nyour average is: " << average << " and  your fail";
          }
          int main()
          {
            int mark1, mark2, mark3;
            ReadMarks(mark1, mark2, mark3);
            printAverage(calculateAverage(mark1, mark2, mark3));
            return 0;
          }
## Write a  program that asks a user to enter two numbers and print the max number:

          #include <iostream>
          #include <string>
          #include <cmath>
          using namespace std;
          
          //The program ask a user to enter two numbers and print the max number
          enum numbers
          {
            num1 = 1,
            num2 = 2
          };
          void ReadNumbers(int &num1, int &num2)
          {
            cout << "please enter number one: \n";
            cin >> num1;
            cout << "please enter number two: \n";
            cin >> num2;
          }
          enNumbers checkNumber(int num1, int num2)
          {
            if (num1 > num2)
              return enNumbers::num1;
            else
              return enNumbers::num2;
          }
          void printNumber(int num1, int num2){
            if(checkNumber(num1, num2) == enNumbers::num1)
              cout<<"the max number is:"<<num1;
            else 
              cout<<"the min number is:"<<num2;
          }
          int main()
          {
            int num1, num2;
            ReadNumbers(num1,num2);
            printNumber(num1, num2);
            return 0;
          }
## Write a  program that asks a user to enter two numbers and print the max number of another answer:
          #include <iostream>
          #include <string>
          #include <cmath>
          using namespace std;
          
          //The program ask a user to enter two numbers and print the number
          void ReadNumbers(int &num1, int &num2)
          {
            cout << "please enter number one: \n";
            cin >> num1;
            cout << "please enter number two: \n";
            cin >> num2;
          }
          int checkNumber(int num1, int num2)
          {
            if (num1 > num2)
              return num1;
            else
              return num2;
          }
          void printNumber(int max){
            cout<<"\n the max number is: "<<max<<endl;
          }
          int main()
          {
            int num1, num2;
            ReadNumbers(num1,num2);
            printNumber(checkNumber(num1 , num2));
            return 0;
          }
## Write a programm ask user enter two numbers and print  Swap between two numbers :
               #include <iostream>
               #include <string>
               #include <cmath>
               using namespace std;
               // swap between two numbers
               void ReadNumbers(int &number1, int &number2)
               {
                 cout << "Please enter number one \n";
                 cin >> number1;
               
                 cout << "Please enter number two \n";
                 cin >> number2;
               }
               int SwapTwoNumbers(int &number1, int &number2)
               {
                 int number3;
               
                 number3 = number1;
                 number1 = number2;
                 number2 = number3;
               
                 return number1, number2;
               }
               void PrintSwapNumber(int number1, int number2)
               {
               
                 cout << "number1: " << number1 << endl;
                 cout << "number2: " << number2 << endl;
               }
               int main()
               {
                 int number1, number2;
                 ReadNumbers(number1, number2);
                 SwapTwoNumbers(number1, number2);
                 PrintSwapNumber(number1 , number2);
                 return 0;
               }
## Write a program to calculate the area of the triangle by a and h :

                #include <iostream>
               #include <string>
               #include <cmath>
               using namespace std;
               // Write a program to calculate the area of a triangle by a and h
               void ReadNumbers(float &a, float &h)
               {
                 cout << "Please enter a number \n";
                 cin >> a;
               
                 cout << "Please enter h number \n";
                 cin >> h;
               }
               float TriangleArea(float a, float h)
               {
                 float area = .5 * a * h;
                 return area;
               }
               void PrintArea(float area)
               {
                 cout << "Area: " << area << endl;
               }
               int main()
               {
                 float a, h;
                 ReadNumbers(a, h);
                 PrintArea(TriangleArea(a, h));
               }
## Write a program to calculate the circle area then print it on the screen:

           #include <iostream>
          #include <string>
          #include <cmath>
          using namespace std;
          // Write a program to calculate the area of a circle by a and h
          void ReadNumber(float &r)
          {
            cout << "Please enter a number \n";
            cin >> r;
          }
          float CircleArea(float r)
          {
            float area = 3.14 * pow(r, 2);
          
            return area;
          }
          void PrintArea(float area)
          {
            cout << "Area: " << area << endl;
          }
          int main()
          {
            float r;
            ReadNumber(r);
            PrintArea(CircleArea(r));
          }
## Write a program to calculate the area of the circle  by (3.14 * d*d ) / 4 :

          #include <iostream>
          #include <string>
          #include <cmath>
          using namespace std;
          // Write a program to calculate the area of a circle  by (3.14 * d*d ) / 4
          void ReadNumber(float &D)
          {
            cout << "Please enter a number \n";
            cin >> D;
          }
          float CircleArea(float D)
          {
            float area = (3.14 * pow(D,2)) / 4;
          
            return area;
          }
          void PrintArea(float area)
          {
            cout << "Area: " << area << endl;
          }
          int main()
          {
            float D;
            ReadNumber(D);
            PrintArea(CircleArea(D));
            return 0;
          }
## Write a program to calculate the circle area along the circumference, then print it on the screen:
          
          #include <iostream>
          #include <string>
          #include <cmath>
          using namespace std;
          // Write a program to calculate the area of a circle  by (d^2) /3.14* 4
          void ReadNumber(float &D)
          {
            cout << "Please enter a number \n";
            cin >> D;
          }
          float CircleArea(float D)
          {
            float area = pow(D,2) /( 3.14 * 4);
          
            return area;
          }
          void PrintArea(float area)
          {
            cout << "Area: " << area << endl;
          }
          int main()
          {
            float D;
            ReadNumber(D);
            PrintArea(CircleArea(D));
            return 0;
          }
## Write a program to calculate the circle area inscribed in an isosceles triangle:

          #include <iostream>
          #include <string>
          #include <cmath>
          using namespace std;
          // Write a program to calculate the area of a circle  by (d^2) /3.14* 4
          void ReadNumber(float &D, float &c)
          {
            cout << "Please enter d number \n";
            cin >> D;
          
            cout << "Please enter c number \n";
            cin >> c;
          }
          float CircleArea(float D, float c)
          {
            float area = 3.14 * (pow(c, 2) / 4) * ((2 * D - c) / (2 * D + c));
          
            return area;
          }
          void PrintArea(float area)
          {
            cout << "Area: " << area << endl;
          }
          int main()
          {
            float D,c;
            ReadNumber(D,c);
            PrintArea(CircleArea(D,c));
            return 0;
          }
## Write a program Read Until Age Between 18 and 45:

               #include <iostream>
               #include <string>
               #include <cmath>
               using namespace std;
               // Write a program asking the user to enter numbers between 18 and 45
               int ReadNumber()
               {
                 int number = 0;
                 cout << "Please enter a number between 18 45:" << endl;
                 cin >> number;
                 return number;
               }
               bool CheckNumber(int number, int from, int to)
               {
                 return (number >= from && number <= to);
               };
               int ReadUntilBetween(int from, int to)
               {
                 int age;
                 do
                 {
                   age = ReadNumber();
                 } while (!CheckNumber(age, from, to));
                 return age;
               }
               void PrintResult(int age){
                 cout<<"your age is: "<<age<<endl;
               
               }
               int main(){
                 PrintResult(ReadUntilBetween(18,45));
                 return 0;
               }
## Write a program print number from 1 to N:

          #include <iostream>
          #include <string>
          #include <cmath>
          using namespace std;
          int ReadNumber( )
          {
            int n;
            cout << "Please enter a number\n";
            cin >> n;
          }
          void Print_For_Loop(int n)
          {
            cout << " FOR LOOP " << endl;
            for (int i = 0; i <= n; i++)
            {
              cout << i << endl;
            }
          }
          void Print_While_Loop(int n)
          {
            cout << " FOR While loop " << endl;
          
            int counter = 0;
            while (counter <= n)
            {
              counter++;
              cout << counter << endl;
            }
          }
          void Print_DO_While_Loop(int n)
          {
            cout << " FOR While Do Loop " << endl;
          
            int counter = 0;
            do
            {
              counter++;
              cout << counter << endl;
            } while (counter <= n);
          }
          int main()
          {
            int n = ReadNumber();
            
            ReadNumber();
            Print_For_Loop(n);
            Print_DO_While_Loop(n);
            Print_While_Loop(n);
          
            return 0;
          }
## Write a program print number from N to 1:

               #include <iostream>
               #include <string>
               #include <cmath>
               using namespace std;
               int ReadNumber(int &n)
               {
                 cout << "Please enter a number\n";
                 cin >> n;
               }
               void Print_For_Loop(int n)
               {
                 cout << " FOR LOOP " << endl;
                 for (int i = 0 ; i < n; n--)
                 {
                   cout << n << endl;
                 }
               }
               void Print_While_Loop(int n)
               {
                 cout << " FOR While loop " << endl;
               
                 int counter = 0;
                 while (counter < n)
                 {
                   n--;
                   cout << n << endl;
                 }
               }
               void Print_DO_While_Loop(int n)
               {
                 cout << " FOR While Do Loop " << endl;
               
                 int counter = 0;
                 do
                 {
                   n--;
                   cout << n << endl;
                 } while (counter < n);
               }
               int main()
               {
                 int n ;
               
                 ReadNumber(n);
                 Print_For_Loop(n);
                 Print_DO_While_Loop(n);
                 Print_While_Loop(n);
               
                 return 0;
               }
## Sum Odd Numbers From 1 to N::


               #include <iostream>
               #include <string>
               #include <cmath>
               using namespace std;
               int ReadNumber(int &n)
               {
                 cout << "Please enter a number\n";
                 cin >> n;
               }
               void Print_For_Loop(int n)
               {
                 int sum = 0;
                 cout << " FOR LOOP " << endl;
                 for (int i = 0; i < n; n--)
                 {
                   if (n % 2 == 0)
                   {
                     sum += n;
                   }
                 }
                 cout << "  sum = " << sum << endl;
               }
               void Print_While_Loop(int n)
               {
                 cout << " FOR While loop " << endl;
                 int sum = 0;
                 int counter = 0;
                 while (counter < n)
                 {
                   if (n % 2 == 0)
                   {
                     sum += n;
                   }
                   n--;
                 }
                 cout << "  sum = " << sum << endl;
               }
               void Print_DO_While_Loop(int n)
               {
                 cout << " FOR While Do Loop " << endl;
                 int sum = 0;
                 int counter = 0;
                 do
                 {
                   if (n % 2 == 0)
                   {
                     sum += n;
                   }
                   n--;
                 } while (counter < n);
                 cout << "  sum = " << sum << endl;
               }
               int main()
               {
                 int n;
               
                 ReadNumber(n);
                 Print_For_Loop(n);
                 Print_DO_While_Loop(n);
                 Print_While_Loop(n);
               
                 return 0;
               }
## Sum Even Numbers From 1 to N::

          #include <iostream>
          #include <string>
          #include <cmath>
          using namespace std;
          enum enOddEven
          {
            odd = 1,
            even = 2
          };
          enOddEven CheckNumber(int n)
          {
            if (n % 2 == 0)
              return enOddEven::even;
            else
              return enOddEven::odd;
          }
          int ReadNumber(int &n)
          {
            cout << "Please enter a number\n";
            cin >> n;
          }
          void Print_For_Loop(int n)
          {
            int sum = 0;
          
            cout << " FOR LOOP " << endl;
            for (int i = 0; i <= n; i++)
            {
              if (CheckNumber(i) == enOddEven::even)
              {
                sum += i;
              }
            }
            cout << "  sum = " << sum << endl;
          }
          void Print_While_Loop(int n)
          {
            cout << " FOR While loop " << endl;
            int sum = 0;
            int counter = 0;
            while (counter < n)
            {
              counter++;
              if (CheckNumber(counter) == enOddEven::even)
              {
                sum += counter;
              }
            }
            cout << "  sum = " << sum << endl;
          }
          void Print_DO_While_Loop(int n)
          {
            cout << " FOR While Do Loop " << endl;
            int sum = 0;
            int counter = 0;
            do
            {
              counter++;
              if (CheckNumber(counter) == enOddEven::even)
              {
                sum += counter;
              }
            } while (counter < n);
            cout << "  sum = " << sum << endl;
          }
          int main()
          {
            int n;
          
            ReadNumber(n);
            Print_For_Loop(n);
            Print_While_Loop(n);
            Print_DO_While_Loop(n);
          
            return 0;
          }
## Write a program print Factorial OF N!:

          #include <iostream>
          #include <string>
          #include <cmath>
          using namespace std;
          int ReadPositiveNumber(string message)
          {
            int number;
          
            do
            {
              
              cout << message << endl;
              cin >> number;
          
            } while (number < 0);
          
            return number;
          }
          int FactorialLoop(int n)
          {
            int sum = 1;
          
            for (int counter = n; counter >= 1; counter--)
            {
              sum *= counter;
            }
            return sum;
          }
          int main()
          {
            FactorialLoop(ReadPositiveNumber("Please enter a positive number: "));
            return 0;
          }
 ## Write a program to read a bill value  add service fee and sales tax to it, and print the total bill on the screen:

          #include <iostream>
          #include <string>
          #include <cmath>
          using namespace std;
          float ReadPositiveNumber(string message)
          {
            float number = 0;
            do
            {
              cout << message << endl;
              cin >> number;
          
            } while (number <= 0);
            return number;
          }
          float TotalBillAfterServiceAndTax(float totalBill)
          {
            totalBill = totalBill * 1.1;
            totalBill = totalBill * 1.16;
          
            return totalBill;
          }
          int main(){
            float totalBill = ReadPositiveNumber("Please Enter a total bill");
          
            cout<<endl;
            cout<<"Total bill = "<<totalBill<<endl;
            cout<<"total bill after service and tax = "<<TotalBillAfterServiceAndTax(totalBill)<<endl;
          
            return 0;
          }

## Write a program to read a NumberOfHours and calculates the number of weeks, and days included int that number:
          #include <iostream>
          #include <string>
          #include <cmath>
          using namespace std;
          float ReadNumberOfHours(string message)
          {
            float number = 0;
            do
            {
              cout << message << endl;
              cin >> number;
            } while (number <= 0);
            return number;
          }
          float CalculateWeeksAndDays(float number, float &weeks, float &days)
          {
            weeks = number / (24 * 7);
            days = number / 24;
          }
          
          int main()
          {
            float weeks, days;
            float number = ReadNumberOfHours("please enter a number of hours");
          
            CalculateWeeksAndDays(number, weeks, days);
          
            cout << "number of days = " << days << endl;
            cout << "number of weeks = " << weeks << endl;
          
            return 0;
          }
## Write a program to calculate the task duration in seconds and print it on screen :
## Given the time duration of a task in the number of days, hours, minutes, and seconds:
          #include <iostream>
          #include <string>
          #include <cmath>
          using namespace std;
          float ReadNumbers(float &days, float &hours, float &minutes, float &seconds)
          {
            cout << "Please enter a number of days" << endl;
            cin >> days;
          
            cout << "Please enter a number of hours" << endl;
            cin >> hours;
          
            cout << "Please enter a number of minutes" << endl;
            cin >> minutes;
          
            cout << "Please enter a number of seconds" << endl;
            cin >> seconds;
          }
          float DaysToSeconds(float days)
          {
            return days * 24 * 60 * 60;
          }
          float HoursToSeconds(float hours)
          {
            return hours *  60 * 60;
          }
          float MinutesToSeconds(float minutes)
          {
            return minutes  * 60;
          }
          int main(){
            float days , hours , minutes , seconds ;
            ReadNumbers(days, hours, minutes, seconds);
          
            float a = DaysToSeconds(days);
            float b = HoursToSeconds(hours); 
            float c = MinutesToSeconds(minutes);
          
            float totalSeconds = a + b + c + seconds;
            cout<<"Total seconds = "<<totalSeconds<<endl;
            
            return 0;
          }
 
## Write a program print prime number from 1 to n:-
          #include <iostream>
          #include <string>
          #include <cmath>
          using namespace std;
          enum enPrimeNumber
          {
            Prime = 1,
            NotPrime = 2
          };
          int ReadPositiveNumber(string Message)
          {
            int number = 0;
            do
            {
              cout << Message << endl;
              cin >> number;
            } while (number <= 0);
            return number;
          }
          enPrimeNumber CheckPrime(int number)
          {
            int m = round(number / 2);
            for (int counter = 2; counter <= m; counter++)
            {
              if (number % counter == 0)
              {
                return enPrimeNumber::NotPrime;
              }
            }
            return enPrimeNumber::Prime;
          }
          void PrintPrimeNumberFrom1ToN(int number)
          {
            cout << "\n";
            cout << "Prime number from " << 1 << "to" << number;
            cout << "are : " << endl;
            for (int i = 1; i <= number; i++)
            {
              if (CheckPrime(i) == enPrimeNumber::Prime)
                cout << i << endl;
            }
          }
          int main()
          {
            PrintPrimeNumberFrom1ToN(ReadPositiveNumber("Please enter a positive number"));
          
            return 0;
          }

## Write a program to check whether the number is perfect or not perfect.

          #include <iostream>
          #include <string>
          #include <cmath>
          using namespace std;
          enum enPrefectNotPerfect
          {
            Perfect = 1,
            NotPerfect = 2
          };
          int ReadPositiveNumber(string message)
          {
            int number = 0;
            do
            {
              cout << message << endl;
              cin >> number;
            } while (number <= 0);
            return number;
          }
          enPrefectNotPerfect CheckNumber()
          {
            int number = ReadPositiveNumber("please enter a number");
            int sum = 0;
            for (int counter = 1; counter < number; counter++)
            {
              if (number % counter == 0)
                sum += counter;
            }
            if (sum == number)
              return enPrefectNotPerfect::Perfect;
          
            else
              return enPrefectNotPerfect::NotPerfect;
          }
          void PrintPerfectNotPerfect()
          {
            if (CheckNumber() == enPrefectNotPerfect::Perfect)
              cout << "Perfect number" << endl;
            else
              cout << "Not perfect number" << endl;
          }
          int main()
          {
            PrintPerfectNotPerfect();
            return 0;
          }

## Another Solution.
          #include <iostream>
          #include <string>
          #include <cmath>
          using namespace std;
          
          int ReadPositiveNumber(string message)
          {
            int number = 0;
            do
            {
              cout << message << endl;
              cin >> number;
            } while (number <= 0);
            return number;
          }
          bool isPerfectNumber(int number)
          {
            int sum = 0;
            for (int i = 0; i < number; i++)
            {
              if (number % i == 0)
                sum += i;
            }
            return number == sum;
          }
          void PrintResult(int number)
          {
            if (isPerfectNumber(number))
              cout << number << "Prefect Number " << endl;
            else
              cout << number << "not perfect number" << endl;
          }
          int main()
          {
            PrintResult(ReadPositiveNumber("Please enter a number"));
            return 0;
          }
## Write a program to print the perfect Number from 1 to N .

          #include <iostream>
          #include <string>
          #include <cmath>
          using namespace std;
          
          int ReadPositiveNumber(string message, int &number)
          {
            number = 0;
            do
            {
              cout << message << endl;
              cin >> number;
            } while (number <= 0);
            return number;
          }
          int isPerfectNumber(int number)
          {
          
            for (int i = 1; i <= number; i++)
            {
              int sum = 0;
              for (int j = 1; j < i; j++)
              {
                if (i % j == 0)
                  sum += j;
              }
              if (i == sum)
                cout << i << "\n Prefect Number " << endl;
            }
          }
          
          int main()
          {
            int number;
            ReadPositiveNumber("Please enter a positive number", number);
            isPerfectNumber(number);
            return 0;
          }
## Another Solution:-
          #include <iostream>
          #include <string>
          #include <cmath>
          using namespace std;
          
          int ReadPositiveNumber(string message)
          {
            int number = 0;
            do
            {
              cout << message << endl;
              cin >> number;
            } while (number <= 0);
            return number;
          }
          bool isPerfectNumber(int number)
          {
            int sum = 0;
            for (int i = 1; i < number; i++)
            {
              if (number % i == 0)
                sum += i;
            }
            return number == sum;
          }
          void PrintPerfectNumberFrom1ToN(int number)
          {
            for (int i = 1; i <= number; i++)
            {
              if (isPerfectNumber(i))
                cout << i << endl;
            }
          }
          
          int main()
          {
            PrintPerfectNumberFrom1ToN(ReadPositiveNumber("Please enter a positive number"));
            return 0;
          }

## Write a program to read number and print reverse order.

          #include <iostream>
          #include <string>
          #include <cmath>
          using namespace std;
          
          int ReadPositiveNumber(string message)
          {
            int number = 0;
            do
            {
              cout << message << endl;
              cin >> number;
            } while (number <= 0);
            return number;
          }
          string ReversePositiveNumber(int number)
          {
            string strNumber = to_string(number);
            string reverse = "";
            for (int i = strNumber.length() - 1; i >= 0; i--)
            {
              reverse +=strNumber[i] ;
            }
            return reverse;
          }
          void PrintNumberReverse(string strNumber)
          {
            cout<<strNumber<<endl;
          }
          int main()
          {
            int number = ReadPositiveNumber("Please enter a positive number");
            string reverse = ReversePositiveNumber(number);
            PrintNumberReverse(reverse);
          }

## Another Solution.

          #include <iostream>
          #include <string>
          #include <cmath>
          using namespace std;
          
          int ReadPositiveNumber(string message)
          {
            int number = 0;
            do
            {
              cout << message << endl;
              cin >> number;
            } while (number <= 0);
            return number;
          }
          string ReverseNumber(int number)
          {
            string strNumber = to_string(number);
            for (int i = strNumber.length() - 1; i >= 0; i--)
            {
              cout<<strNumber[i] <<endl;
            }
          }
          
          int main()
          {
            ReverseNumber(ReadPositiveNumber("Please enter a positive number"));
            return 0;
          }

## Anthor Solution2.

          #include <iostream>
          #include <string>
          #include <cmath>
          using namespace std;
          
          int ReadPositiveNumber(string message)
          {
            int number = 0;
            do
            {
              cout << message << endl;
              cin >> number;
            } while (number <= 0);
            return number;
          }
          void ReverseNumber(int number)
          {
            string strNumber = to_string(number);
            for (int i = strNumber.length() - 1; i >= 0; i--)
            {
              cout<<strNumber[i] <<endl;
            }
          }
          
          int main()
          {
            ReverseNumber(ReadPositiveNumber("Please enter a positive number"));
            return 0;
          }
## Anthor Solution3.

          #include <iostream>
          #include <string>
          #include <cmath>
          using namespace std;
          
          int ReadPositiveNumber(string message)
          {
            int number = 0;
            do
            {
              cout << message << endl;
              cin >> number;
            } while (number <= 0);
            return number;
          }
          void ReverseNumber(int number)
          {
            int Remainder = 0;
            while (number > 0)
            {
              Remainder = number % 10;
              number = number / 10;
              cout << Remainder << endl;
            }
          }
          
          int main()
          {
            ReverseNumber(ReadPositiveNumber("Please enter a positive number"));
            return 0;
          }

## Write a program to read a number and print sum of this digits.

               #include <iostream>
               #include <string>
               #include <cmath>
               using namespace std;
               
               int ReadPositiveNumber(string message)
               {
                 int number = 0;
                 do
                 {
                   cout << message << endl;
                   cin >> number;
                 } while (number <= 0);
                 return number;
               }
               int ReverseNumber(int number)
               {
                 int Remainder = 0;
                 int sum = 0;
                 while (number > 0)
                 {
                   Remainder = number % 10;
                   number = number / 10;
                   sum += Remainder;
                 }
                   return sum;
               }
               
               int main()
               {
                 cout<< " \n sum = "<<ReverseNumber(ReadPositiveNumber("Please enter a positive number")) <<endl;
                 return 0;
               }
               
## Write a program to read a number and print reversed.
## if input = 1234 , output = 4321.

          #include <iostream>
          #include <string>
          #include <cmath>
          using namespace std;
          
          int ReadPositiveNumber(string message)
          {
            int number = 0;
            do
            {
              cout << message << endl;
              cin >> number;
            } while (number <= 0);
            return number;
          }
          int ReverseNumber(int number)
          {
            int Remainder = 0;
            string reverse = "";
            while (number > 0)
            {
              Remainder = number % 10;
              number = number / 10;
              reverse += to_string(Remainder);
            }
            cout << reverse << endl;
          }
          
          int main()
          {
            ReverseNumber(ReadPositiveNumber("Please enter a positive number")) ;
            return 0;
          }

## another Solution.
          #include <iostream>
          #include <string>
          #include <cmath>
          using namespace std;
          
          int ReadPositiveNumber(string message)
          {
            int number = 0;
            do
            {
              cout << message << endl;
              cin >> number;
            } while (number <= 0);
            return number;
          }
          int ReverseNumber(int number)
          {
            int Remainder = 0;
            int number2 = 0;
            while (number > 0)
            {
              Remainder = number % 10;
              number = number / 10;
              number2 = number2 * 10 + Remainder;
            }
            return number2;
          }
          
          int main()
          {
            cout<<ReverseNumber(ReadPositiveNumber("Please enter a positive number"));
            return 0;
          }

## Write a program read a digit and a number , the print digit frequency in the number.

          #include <iostream>
          #include <string>
          #include <cmath>
          using namespace std;
          
          int ReadPositiveNumber(string message)
          {
            int number = 0;
            do
            {
              cout << message << endl;
              cin >> number;
            } while (number <= 0);
            return number;
          }
          int ReverseNumber(int number)
          {
            int Remainder = 0;
            int number2 = 0;
            while (number > 0)
            {
              Remainder = number % 10;
              number = number / 10;
              if(Remainder == 2){
                number2++;
              }
            }
            return number2;
          }
          
          int main()
          {
            cout<<ReverseNumber(ReadPositiveNumber("Please enter a positive number"));
            return 0;
          }
## Write a program read a number and print all digit frequency in that numbrt.


               #include <iostream>
               #include <string>
               #include <cmath>
               using namespace std;
               
               int ReadPositiveNumber(string message)
               {
                 int number = 0;
                 do
                 {
                   cout << message << endl;
                   cin >> number;
                 } while (number <= 0);
                 return number;
               }
               int CountDigitFrequency(short digitToCheck, int number)
               {
                 int Remainder = 0, FreqCount = 0;
               
                 while (number > 0)
                 {
                   Remainder = number % 10;
                   number = number / 10;
                   if (digitToCheck == Remainder)
                   {
                     FreqCount++;
                   }
                 }
                 return FreqCount;
               }
               void PrintAllDigitsFrequencey(int number)
               {
                 for (int i = 0; i < 10; i++)
                 {
                   short DigitFrequency = 0;
                   DigitFrequency = CountDigitFrequency(i, number);
               
                   if (DigitFrequency > 0)
                   {
                     cout << "Digit: " << i << " Frequency is " << DigitFrequency << endl;
                   }
                 }
               }
               
               int main()
               {
                 int number = ReadPositiveNumber("Please enter a positive number");
                 PrintAllDigitsFrequencey(number);
               
                 return 0;
               }

##  Write a program read number and print from right to left .
## input = 1234 
## output =>
## 1
## 2
## 3
## 4

          #include <iostream>
          #include <string>
          #include <cmath>
          using namespace std;
          
          int ReadPositiveNumber(string message)
          {
            int number = 0;
            do
            {
              cout << message << endl;
              cin >> number;
            } while (number <= 0);
            return number;
          }
          int PrintNumber( int number)
          {
            int Remainder = 0, number2 = 0;
          
            while (number > 0)
            {
              Remainder = number % 10;
              number = number / 10;
              number2 = number2 * 10 + Remainder;
            }
            int Remainder2 = 0;
            while (number2 > 0)
            {
              Remainder2 = number2 % 10;
              number2 = number2 / 10;
              cout << Remainder2 << endl;
            }
          }
          
          int main()
          {
            PrintNumber(ReadPositiveNumber("Please enter a positive number")) ;
          
            return 0;
          }

## Write a program to read numbers and  check if it is a palindrome.
## palindrome is a number that reads the same from right to left.

               #include <iostream>
               #include <string>
               #include <cmath>
               using namespace std;
               
               int ReadPositiveNumber(string message)
               {
                 int number = 0;
                 do
                 {
                   cout << message << endl;
                   cin >> number;
                 } while (number <= 0);
                 return number;
               }
               int PrintNumber(int number)
               {
                 int Remainder = 0, number2 = 0;
               
                 while (number > 0)
                 {
                   Remainder = number % 10;
                   number = number / 10;
                   number2 = number2 * 10 + Remainder;
                 }
                 return number2;
               }
               int ReverseNumber(int number)
               {
                 int Remainder2 = 0;
                 int number3 = 0;
                 int number2 = PrintNumber(number);
               
                 while (number2 > 0)
                 {
                   Remainder2 = number2 % 10;
                   number2 = number2 / 10;
                   number3 = number3 * 10 + Remainder2;
                 }
                 return number3;
               }
               int check(int number)
               {
                 int number2 = PrintNumber(number);
                 cout << "number2 = " << number2 << endl;
                 int number3 = ReverseNumber(number);
                 cout << "number3 = " << number3 << endl;
               
                 if (number2 == number3)
                 {
                   cout << "Yes, it is a Palindrome number";
                 }
                 else
                 {
                   cout << "no, it is  not Palindrome number";
                 }
               }
               int main()
               {
                 check(ReadPositiveNumber("Please enter a positive number"));
               
                 return 0;
               }


## Another Solution.
          #include <iostream>
          #include <string>
          #include <cmath>
          using namespace std;
          
          int ReadPositiveNumber(string message)
          {
            int number = 0;
            do
            {
              cout << message << endl;
              cin >> number;
            } while (number <= 0);
            return number;
          }
          int ReverseNumber(int number)
          {
            int Remainder = 0;
            int number2 = 0;
          
            while (number > 0)
            {
              Remainder = number % 10;
              number = number / 10;
              number2 = number2 * 10 + Remainder;
            }
            return number2;
          }
          int check(int number)
          {
          
            int number2 = ReverseNumber(number);
            cout << "number2 = " << number2 << endl;
          
            if (number == number2)
            {
              cout << "Yes, it is a Palindrome number";
            }
            else
            {
              cout << "no, it is  not Palindrome number";
            }
          }
          int main()
          {
            check(ReadPositiveNumber("Please enter a positive number"));
          
            return 0;
          }
## Another Solution.

          #include <iostream>
          #include <string>
          #include <cmath>
          using namespace std;
          
          int ReadPositiveNumber(string message)
          {
            int number = 0;
            do
            {
              cout << message << endl;
              cin >> number;
            } while (number <= 0);
            return number;
          }
          int ReverseNumber(int number)
          {
            int Remainder = 0;
            int number2 = 0;
          
            while (number > 0)
            {
              Remainder = number % 10;
              number = number / 10;
              number2 = number2 * 10 + Remainder;
            }
            return number2;
          }
          bool check(int number)
          {
            return number == ReverseNumber(number);
          }
          int main()
          {
          
            if (check(ReadPositiveNumber("Please enter a positive number")))
            {
              cout << "Yes, it is a Palindrome number";
            }
            else
            {
              cout << "no, it is  not Palindrome number";
            }
          
            return 0;
          }

## Write a program to read a number and print the number as follows.
## if input = 5;
## 55555
## 4444
## 333
## 22
## 1

               #include <iostream>
               #include <string>
               #include <cmath>
               using namespace std;
               
               int ReadPositiveNumber(string message)
               {
                 int number = 0;
                 do
                 {
                   cout << message << endl;
                   cin >> number;
                 } while (number <= 0);
                 return number;
               }
               int invertedNumber(int number)
               {
                 while (number > 0)
                 {
                   for (int i = number; i > 0; i--)
                   {
                     cout << number;
                   }
                   number--;
                   cout<<endl;
                 }
               }
               int main()
               {
                 invertedNumber(ReadPositiveNumber("Please enter a number"));
                 return 0;
               }

## Another Solution.
          #include <iostream>
          #include <string>
          #include <cmath>
          using namespace std;
          
          int ReadPositiveNumber(string message)
          {
            int number = 0;
            do
            {
              cout << message << endl;
              cin >> number;
            } while (number <= 0);
            return number;
          }
          int invertedNumber(int number)
          {
            cout << endl;
            for (int i = 0; i < number; i--)
            {
              for (int j = 0; j < number; j++)
              {
                cout << i;
              }
            }
          }
          int main()
          {
            invertedNumber(ReadPositiveNumber("Please enter a number"));
            return 0;
          }
          
## Write a program to read a number and print the number as follows.
## if input = 5;
## 1
## 22
## 333
## 4444
## 55555

          #include <iostream>
          #include <string>
          #include <cmath>
          using namespace std;
          
          int ReadPositiveNumber(string message)
          {
            int number = 0;
            do
            {
              cout << message << endl;
              cin >> number;
            } while (number <= 0);
            return number;
          }
          int invertedNumber(int number)
          {
            for (int i = 1; i <= number; i++)
            {
              cout << endl;
              for (int j = 0; j < i; j++)
              {
                cout << i;
              }
            }
          }
          int main()
          {
            invertedNumber(ReadPositiveNumber("Please enter a number"));
            return 0;
          }
          
## Write a program to read a Letter and print the number as follows.
## if input = 5;
## A
## BB
## CCC
## DDDD
## FFFFF
     
          #include <iostream>
          #include <string>
          #include <cmath>
          using namespace std;
          
          int ReadPositiveNumber(string message)
          {
            int number = 0;
            do
            {
              cout << message << endl;
              cin >> number;
            } while (number <= 0);
            return number;
          }
          int PrintLetterNumber(int number)
          {
          
            for (int i =65; i <=  65 + number - 1 ; i++)
            {
              for (int j = 1; j <= number - (65 + number - 1 - i); j++)
              {
                cout << char(i);
              }
              cout << endl;
            }
          }
          int main()
          {
            PrintLetterNumber(ReadPositiveNumber("Please enter a number"));
            return 0;
          }

## Write a program to read a Letter and print the number as follows.
## if input = 5;
## FFFFF
## DDDD
## CCC
## BB
## A

          #include <iostream>
          #include <string>
          #include <cmath>
          using namespace std;
          
          int ReadPositiveNumber(string message)
          {
            int number = 0;
            do
            {
              cout << message << endl;
              cin >> number;
            } while (number <= 0);
            return number;
          }
          int PrintLetterNumber(int number)
          {
          
            for (int i = 65 + number - 1; i >= 65; i--)
            {
              for (int j = 1; j <= number - (65 + number - 1 - i); j++)
              {
                cout << char(i);
              }
              cout << endl;
            }
          }
          int main()
          {
            PrintLetterNumber(ReadPositiveNumber("Please enter a number"));
            return 0;
          }

## Write a program to print all Words from AAA TO ZZZ.

          #include <iostream>
          #include <string>
          #include <cmath>
          using namespace std;
          
          void PrintAllNumber()
          {
            string word = "";
            for (int i = 65; i <= 90; i++)
            {
              for (int j = 65; j <= 90; j++)
              {
                for (int k = 65; k <= 90; k++)
                {
                  word = word + char(i);
                  word = word + char(j);
                  word = word + char(k);
                  cout << word << endl;
                  word = "";
                }
              }
              cout << endl;
            }
          }
          int main()
          {
            PrintAllNumber();
          }

## Write a program to guess a 3-letter Password (all capital).
## input => (AAF).
          #include <iostream>
          #include <string>
          #include <cmath>
          using namespace std;
          string ReadPassWord(string message)
          {
            string word2;
            cout << message << endl;
            cin >>  word2;
            return word2;
          }
          bool PrintAllNumber(string word2)
          {
            string word = "";
            int counter = 0;
            for (int i = 65; i <= 90; i++)
            {
              for (int j = 65; j <= 90; j++)
              {
                for (int k = 65; k <= 90; k++)
                {
                  word = word + char(i);
                  word = word + char(j);
                  word = word + char(k);
                  counter++;
                  cout << word << endl;
                  if (word == word2)
                  {
                    cout << "train" << counter << ":AAF" << endl;
                    return true;
                  }
                  
                  word = "";
                }
              }
              cout << endl;
            }
            return false;
          }
          int main()
          {
            PrintAllNumber(ReadPassWord("Please enter a pass word"));
          }

## Write a program to read a text and encrypt it, decrypt it. 


               #include <iostream>
               #include <string>
               #include <cmath>
               using namespace std;
               string ReadText()
               {
                 string text;
                 cout << "Please enter your text" << endl;
                 getline(cin, text);
               
                 return text;
               }
               string EncryptText(string text, short EncryptKey)
               {
                 for (int i = 0; i < text.length(); i++)
                 {
                   text[i] = char((int)text[i] + EncryptKey);
                 }
                 return text;
               }
               string DeEncryptText(string text, short EncryptKey)
               {
                 for (int i = 0; i < text.length(); i++)
                 {
                   text[i] = char((int)text[i] - EncryptKey);
                 }
                 return text;
               }
               int main()
               {
                 const short EncryptKey = 9;
                 string text = ReadText();
               
                 string TextEncrypt = EncryptText(text, EncryptKey);
                 string TextDeEncrypt = DeEncryptText(TextEncrypt, EncryptKey);
               
                 cout << "text" << endl;
                 cout << text << endl;
                 cout << "text after encrypt" << endl;
                 cout << TextEncrypt << endl;
                 cout << "text deEncrypt" << endl;
                 cout << TextDeEncrypt << endl;
               }

## Write a program to print 3 random numbers from 1 to 10.

          #include <iostream>
          #include <string>
          #include <cmath>
          #include <cstdlib>
          using namespace std;
          
          int RandomNumber(int from, int to)
          {
          
            int randNum = rand() % (to - from + 1) + from;
            return randNum;
          }
          int main()
          {
            srand((unsigned)time(NULL));
          
            cout << RandomNumber(10, 500) << endl;
            cout << RandomNumber(10, 500) << endl;
            cout << RandomNumber(10, 500) << endl;
          
            return 0;
          }
## Write a program to print random Small letters, Capital Letters, Special Characters, and digits in order.

          #include <iostream>
          #include <string>
          #include <cmath>
          #include <cstdlib>
          using namespace std;
          
          int RandomNumber(int from, int to)
          {
            int randNum = rand() % (to - from + 1) + from;
            return randNum;
          }
          enum enCharType
          {
            SmallLetter = 1,
            CapitalLetter = 2,
            SpecialCharacter = 3,
            Digit = 4
          };
          
          char GetRandCharacter(enCharType CharType)
          {
            switch (CharType)
            {
            case enCharType::SmallLetter:
            {
              return char(RandomNumber(97, 122));
              break;
            }
            case enCharType::CapitalLetter:
            {
              return char(RandomNumber(65, 90));
              break;
            }
            case enCharType::SpecialCharacter:
            {
              return char(RandomNumber(33, 47));
              break;
            }
            case enCharType::Digit:
            {
              return char(RandomNumber(48, 57));
              break;
            }
            }
          }
          
          int main(){
            srand((unsigned )time(NULL));
          
            cout<<GetRandCharacter(enCharType::CapitalLetter)<<endl;
            cout<<GetRandCharacter(enCharType::Digit)<<endl;
            cout<<GetRandCharacter(enCharType::SmallLetter)<<endl;
            cout<<GetRandCharacter(enCharType::SpecialCharacter)<<endl;
          
            return 0;
          }

## 











