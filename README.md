# Car Speedometer App

A simple and efficient Android application that measures your car's speed using GPS and displays it in a large, readable format.

## Features
- **Real-time Speed Tracking**: Uses high-accuracy GPS data to calculate speed.
- **Large Display**: Large font size for the speed display, perfect for use while driving.
- **Unit Conversion**: Automatically displays speed in km/h.
- **Modern UI**: Built with Jetpack Compose.

## How it Works
The app requests location updates from the `FusedLocationProviderClient`. The speed is retrieved from the `Location` object in meters per second and converted to kilometers per hour by multiplying by 3.6.

## Permissions
The app requires `ACCESS_FINE_LOCATION` permission to function correctly.

## Technologies Used
- Kotlin
- Jetpack Compose
- Google Play Services Location API
- Material 3
