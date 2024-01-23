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























               









