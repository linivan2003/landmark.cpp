# landmark.cpp
This C++ project creates a simple landmark display system that showcases the use of classes, inheritance, virtual functions, constructors, and destructors to manage various types of landmarks.
## Features
The code consists of several classes representing different types of landmarks:

Landmark: Base class representing a generic landmark, defining a name, color, and an icon.
Hotel: Derived class from Landmark, representing a hotel.
Restaurant: Derived class from Landmark, representing a restaurant with varying capacity icons.
Hospital: Derived class from Landmark, representing a hospital with a unique color and icon.

## Structure
Landmark Class:

Manages the basic properties and functions common to all landmarks.
Implements a virtual destructor and functions for name, color, and icon.

Derived Classes (Hotel, Restaurant, Hospital):

Inherit from Landmark and extend its functionalities.
Implement specialized behavior for icons, colors, and specific features of each type of landmark.

## Cleanup
The program ensures proper memory management by deleting dynamically allocated landmark objects using destructors before exiting.
