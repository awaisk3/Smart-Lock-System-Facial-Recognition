Features:
Facial Recognition: Detects and verifies faces using a connected camera.
Speaker and Microphone: Provides audio feedback or allows communication.
Control Logic: Unlocks the door when the face is recognized.

Hardware Requirements:
ESP32 (with camera support, e.g., ESP32-CAM).
Camera module (compatible with ESP32-CAM).
Speaker and microphone (for audio feedback).
Relay module (to control the lock).

Libraries Needed:
ESP32 Camera library.
Face recognition model (TinyML or cloud-based API).
Audio playback library.
Optional: Speech-to-text library or API for microphone input.

Steps for Completion:
Camera Initialization: Configure your ESP32-CAM pins.
Facial Recognition: Replace the recognizeFace function with an actual facial recognition model or API call.
Audio Feedback: Implement audio playback using your speaker and integrate a TTS library if required.
Relay or Servo Control: Adjust the unlockDoor logic based on your locking mechanism.
