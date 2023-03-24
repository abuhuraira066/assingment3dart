# assingment3dart
create a vehicle class with brand , model ,and year properties and a method called drive ( ) that prints a message indicating that the vehicle is being driven . then create a Car class that inherits from vehicle and has a numDoors property . Override the drive( ) method in the car class to print a message that includes the number of doors .


class Vehicle {
  String brand;
  String model;
  int year;

  Vehicle(this.brand, this.model, this.year);

  void drive() {
    print('The $year $brand $model is being driven.');
  }
}

class Car extends Vehicle {
  int numDoors;

  Car(String brand, String model, int year, this.numDoors) : super(brand, model, year);

  @override
  void drive() {
    print('The $year $brand $model with $numDoors doors is being driven.');
  }
}
void main() {
  Car myCar = Car('Suzuki', 'mehran', 1999, 4);
  myCar.drive(); // output: The 2022 Toyota Camry with 4 doors is being driven.
}
