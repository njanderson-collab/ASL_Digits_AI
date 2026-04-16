
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
### Models used

Downloading, extraction, and placing the models into the *assets* folder is
managed automatically by the **download.gradle** file.
