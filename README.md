# Cruise Service

This Cruise Service project allows users to book journeys according to room types such as Economy, Business, and Deluxe. The code is implemented in C++ and consists of various files to handle different aspects of the service.

## Project Structure

- `Main.cpp`: The main file to run the Cruise Service program.
- `Passenger.cpp`: Implementation file for handling passenger details.
- `Cruise.cpp`: Implementation file for handling cruise details.
- `storeDetails.cpp`: Implementation file for storing and managing details in text files.
- `Admin.cpp`: Implementation file for administrative functionalities.
- `handlingWaitingList.cpp`: Implementation file for managing waiting lists.

## Usage

Compile the program using the following command:

```bash
g++ Main.cpp Passenger.cpp Cruise.cpp storeDetails.cpp Admin.cpp handleWaitingList.cpp -o Run

Run the compiled program:
./Run

Files
Cruise.txt: Text file to store cruise details.
passengerDetails.txt: Text file to store passenger details.

How to Run
Compile the program using the provided command.
Run the compiled program.
Follow the on-screen instructions to book journeys and manage cruise details.

Features
Booking: Users can book journeys based on different room types.
Details Management: Administrative features to view and manage cruise and passenger details.
Waiting List Handling: Efficiently handles waiting lists for fully booked rooms.

Contributing
Feel free to contribute to this Cruise Service project. If you have suggestions or find any issues, please open an issue or create a pull request.
