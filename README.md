Design a parking lot using Python with TDD approach

Dependencies
You just need Python. The code is compatible with Python2 as well as Python3. Visit the link https://www.python.org/downloads/ to install Python.

Description
ParkingLot.py script defines the following functions -

create_parking_lot n - Given n number of slots, create a parking lot
park car_regno car_color - Parks a vehicle with given registration number and color in the nearest empty slot possible. If there are no more empty slots available, it shows a message "Sorry, parking lot is full".
status - Prints the slot number, registration number and color of the parked vehicles.
leave x - Removes vehicle from slot number x
There are few query functions to retrieve slot number from registration number of car, get registration numbers of cars with particular color etc.
ParkingLot.py can be run through shell or through file containing test cases. An example file run_test_case.txt has been provided in repo.

I have followed TDD approach while designing this. test_parking_lot.py uses unittest module of python. Here 6 test cases are written in order to test each functionality mentioned in ParkingLot.py

Vehicle.py is a separate class where we can define the type of vehicles that can be parked. As of now, it only contains class Car

Setup
To create your own ParkingLot -

Clone the repository

Run python ParkingLot.py to run without input test case file. This opens a shell where you can write your commands like -

p1

To run with a file execute `python ParkingLot.py -f run_test_case.txt. You can modify the test cases.
p2

You can also run the test cases separately as python test_parking_lot.py. This runs the 6 test cases written in file. This is very useful when you want to create your own function and test it simultaneously.
park3
