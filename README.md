# Cruise Service Booking System

## Introduction

Welcome to the Cruise Service Booking System! This program allows users to book journeys on a cruise ship, with various room types available such as Economy, Business, and Deluxe. The system manages passenger details, cruise information, and waiting lists efficiently.

## Files

The project is organized into several C++ files:

- **Main.cpp**: The main program file that orchestrates the flow of the application.
- **Passenger.cpp**: Handles passenger-related operations and data.
- **Cruise.cpp**: Manages cruise-related operations and data.
- **storeDetails.cpp**: Implements the storage and retrieval of details for passengers and cruises.
- **Admin.cpp**: Provides functionality to view all details.
- **handlingWaitingList.cpp**: Manages waiting lists for fully booked cruises.

## Compilation and Execution

To compile the program, use the following command:

```bash
g++ Main.cpp Passenger.cpp Cruise.cpp storeDetails.cpp Admin.cpp handlingWaitingList.cpp -o Run
```

To run the program:

```bash
./Run
```

## Data Storage

- **Cruise.txt**: Stores information about available cruises, their schedules, and room types.
- **passengerDetails.txt**: Records passenger details, booking status, and waiting list information.

## Usage

1. Run the program using the specified compilation and execution commands.
2. Follow the on-screen prompts to book a journey, view details, or perform other operations.
3. Enjoy the cruise service!

## Contributions

Contributions to the Cruise Service Booking System are welcome! Feel free to submit issues, feature requests, or pull requests to help improve the system.

## License

This Cruise Service Booking System is open-source and available under the [MIT License](LICENSE).

---

Feel free to customize the README according to your specific project details and requirements.
