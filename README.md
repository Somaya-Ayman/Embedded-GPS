# GPS Distance Tracking System

This project involves developing a system using the TM4C123G LaunchPad from Texas Instruments that tracks the distance a user travels between two points using GPS coordinates. The system will also provide visual feedback to the user using built-in LEDs, indicating when they are close to their destination or have reached it.

## Features

The GPS subsystem will perform the following tasks:

1. Store the coordinates of the starting point.
2. Store the coordinates of the end point and calculate the total distance traveled by the user.
3. Provide visual feedback to the user using built-in LEDs:
   1. Stage 1: Turn on the green LED when the target destination is reached.
   2. Stage 2: Turn on the yellow LED when the target destination is about to be reached (less than 5 meters away).
   3. Stage 3: Turn on the red LED when the target destination is far away by more than 5 meters.

The trajectory of the distance traveled should satisfy the following criteria:

1. The total distance between the start and end point should be greater than 100 meters.
2. The path from the start point to the end point should form a non-straight line similar to the provided baseline path.
3. The calculated distance should be compared with the distance obtained from Google Maps, and the error margin should be less than or equal to 5%.

## Usage

To use this system, you will need to connect the TM4C123G LaunchPad to a GPS module and configure it to receive GPS coordinates. Once the system is set up, you can use it to track your distance traveled and receive visual feedback using the built-in LEDs.

### Programming Language Used

This project was developed using C programming language.

![C Language Icon](https://img.icons8.com/color/48/000000/c-programming.png)

### Vendor of the TM4C123G LaunchPad

The TM4C123G LaunchPad used in this project was developed by Texas Instruments.

![TI Logo](https://www.ti.com/content/dam/ticom/images/logo/TI-Logo-Red-RGB.svg)

## Credits

This project was developed by [Mahmoud Abdelraouf] as part of [Introduction to Embedded Systems/GPS Tracking System].

### Contribution

Here is a photo demonstrating the contribution made by this project:

![Contribution Photo](https://www.parsintl.com/wp-content/uploads/2018/05/PARS-Intl-Logo-1.png)
