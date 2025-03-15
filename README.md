Location Services
Author: Ojaswa Kesharwani

Description: This is a dummy Android project demonstrating how to fetch the user's current location and send it via WhatsApp.

Features
Fetches the device's current location using Google's Fused Location Provider.
Sends the location as a Google Maps link through WhatsApp.
Prerequisites
Android Studio installed.
An Android device or emulator running Android 6.0 (Marshmallow) or higher.
WhatsApp installed on the device (for testing the send functionality).
Getting Started
Clone the Repository:

bash
Copy
Edit
git clone https://github.com/Ojaswakesharwani/Location-Services.git
Open in Android Studio:

Launch Android Studio.
Select "Open an existing project" and navigate to the cloned repository.
Build the Project:

Allow Android Studio to sync and build the project. Resolve any dependencies if prompted.
How It Works
MainActivity.kt:
Initializes the FusedLocationProviderClient to access location services.
Requests location permissions at runtime.
Fetches the last known location upon user interaction.
Constructs a Google Maps URL with the obtained latitude and longitude.
Opens WhatsApp with a pre-filled message containing the location link.
Permissions
The app requires the following permissions:

ACCESS_FINE_LOCATION: To access precise device location.
Ensure these permissions are declared in the AndroidManifest.xml and handled at runtime.

Notes
The app uses the Fused Location Provider for efficient and accurate location tracking.
Location accuracy depends on device sensors and settings.
Ensure that location services and permissions are enabled on the device for proper functionality.
Contributions
This project is a demonstration and is not actively maintained. However, feel free to fork and modify it for your own purposes.

License
This project is open-source and available under the MIT License.
