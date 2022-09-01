# Dart-abstract
Dart-abstract
void main() {
  
  
  
Abstract has no object

abstract contains two function.
 1)concrete function==>(complete function) 
 2)abstract function==>(incomplete function)

In abstract class,we use abstract function/incomplete function and abstract function has no body.

In inheritance class,we use concrete function/complete function and concrete function has body.

@overide keyword is written before starting concrete function.


abstract funtion example   ==>   void showdetails();

concrete function example  ==>    @overide void showdetails(){}
  
 
  
  
Train obj1=Train("blue",200000,5);

obj1.showdetails();

}

abstract class Vechicle //abstract class
{
Vechicle(){print("i am parent class constructor ");} //no argument abstract constructor 

void showdetails(); //abstract or incomplete function,,,it has no body
}

class Train extends Vechicle//i am child class(Train) 
{late String color;
late int price;
late int speed;
Train(this.color,this.price,this.speed)
{print("i am child class constructor ");}
@override
void showdetails()//concrete or complete function,,,it has body
{
print(color);
print(price);
print(speed);
} 
}
