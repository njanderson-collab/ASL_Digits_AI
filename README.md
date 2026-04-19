
### Key Features
*   **Translation Invariance**: Landmarks are calculated relative to the wrist.
*   **Mirrored Support**: Input coordinates are automatically flipped to account for the front-facing camera.
*   **HUD Overlay**: Predictions are displayed in a high-visibility green box at the top of the screen.

---

## Build Prerequisites
*   **Android Studio**: Hedgehog or newer recommended.
*   **Physical Device**: Android SDK 24 (Nougat) or higher.
*   **TensorFlow Lite**: The project is configured to use TFLite **2.17.0** to support modern `FULLY_CONNECTED` operations.

## Setup & Installation
1.  **Clone the Repo**:
2.  Install Android Studio at https://developer.android.com/studio
3.  Launch the repo within Android Studio
4.  Connect compatible Android device, make sure developer mode and USB debugging are turned on.
5.  Build project and gradle
6.  Run on Android Device
### Models used

Downloading, extraction, and placing the models into the *assets* folder is
managed automatically by the **download.gradle** file.

















## Disclaimer
Portions of this code were tested and edited with suggestions from Android Studio's onboard AI to ensure compatibility
