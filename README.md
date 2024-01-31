# RideNow Car Project

## Overview

RideNow Car Project is a comprehensive console-based ride-sharing application built in C#. The project encompasses various functionalities catering to passengers, drivers, and administrators. It provides a seamless experience for booking rides, managing driver information, and overseeing the system's operations.

## Features

### 1. Book a Ride

- **Description:** Passengers can effortlessly book rides by providing essential details such as name, phone number, start and end locations, and the preferred ride type (Bike, Rickshaw, Car).

- **How to Use:**
  - Run the application.
  - Choose the "Book a Ride" option.
  - Enter passenger details and ride information.
  - Confirm the ride booking.

### 2. Enter as Driver

- **Description:** Drivers have a dedicated portal to register in the system, set their availability, update their current location, and manage their profile information.

- **How to Use:**
  - Run the application.
  - Choose the "Enter as Driver" option.
  - Enter the driver's ID and name.
  - Set availability, update location, and manage the driver profile.

### 3. Enter as Admin

- **Description:** Administrators have access to a feature-rich dashboard with functionalities to add new drivers, remove drivers, update driver information, and search for drivers in the system.

- **How to Use:**
  - Run the application.
  - Choose the "Enter as Admin" option.
  - Access admin features: add, remove, update, or search for drivers.

## Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/your-username/RideNow-Car-Project.git
   ```

2. **Navigate to the project directory:**

   ```bash
   cd RideNow-Car-Project
   ```

3. **Compile and run the application:**

   ```bash
   dotnet run
   ```

## Dependencies

- [DriverLib](DriverLib): A library containing driver-related functionalities.
- [LocationLib](LocationLib): A library providing location-related functionalities.
- [PassengerLib](PassengerLib): A library for passenger-related functionalities.
- [SerializationHelperLib](SerializationHelperLib): A library for serialization and deserialization of driver data.
- [VehicleLib](VehicleLib): A library for handling vehicle information.

## Contributing

If you wish to contribute to this project, follow these steps:

1. Fork the repository.
2. Create a new branch for your feature: `git checkout -b feature-name`
3. Commit your changes: `git commit -m 'Add some feature'`
4. Push to the branch: `git push origin feature-name`
5. Submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).

Feel free to explore the codebase and enhance the project further! If you encounter any issues or have suggestions, don't hesitate to reach out through the GitHub repository. Happy coding!
