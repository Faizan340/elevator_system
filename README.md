Project Description   :-  
The Elevator Management System is a web-based application designed to efficiently manage elevators in a building or complex. The system aims to streamline the elevator operations, provide real-time monitoring, and improve passenger experience while using the elevators.

Architecture   :-
The project follows a Django architecture with the following components:

Elevator System Model: Represents the overall elevator system.
Elevator Model: Represents individual elevators with their status.
Elevator Request Model: Stores user requests for elevators.

Assumptions   :-
The elevator system has one button per floor.
Immediate reflection of API calls to simulate real-time elevator movement.

Testing   :-
Comprehensive unit tests have been written to ensure the functionality of each component. 

Elevator System Initialization   :-
The elevator system can be initialized by specifying the number of elevators, the total number of floors in the building, and other relevant details.

Request Queue Management   :-
The system maintains a queue of elevator requests, ensuring fair distribution of elevator service among different floors.

Next Destination Prediction   :-
The system predicts the next destination floor for each elevator based on its current floor, direction of travel.

Elevator Maintenance and Status Updates   :-
The system updates the status of each elevator based on its working condition.
Technologies used   :-  
Python, Django, Django Rest Framework, PostgreSQL.
API Endpoints   :-

@ lift/elevator/
@ lift/elevatorsystems/
@ lift/elevatorrequest/
@ lift/elevators/pk/all_requests/   -   Fetching All requests for a given elevator.
@ lift/elevators/pk/calculate_next_destination/   -   Fetching next destination floor.
@ lift/elevators/pk/elevator_moving/   -   Fetching if the elevator is moving up or down.
@ lift/elevators/pk/elevator_working/   -   Marking a Elevator as working or not.
@ lift/elevators/pk/elevator_door/   -   Change the door status : open or close.
