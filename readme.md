# Val_Timer - A Spike Timer Overlay for Valorant

This is a Spike countdown overlay tool designed for the game Valorant. When the Spike icon appears on the screen, it automatically displays a 45-second countdown, helping players to master the timing precisely.

<img width="297" height="239" alt="image" src="https://github.com/user-attachments/assets/3f9d5c4e-641e-41ff-86c2-989384cdcf77" />


### ⚠️ Important Notes

1.  You **must** set your game's display mode to **Windowed Fullscreen** for the overlay to work correctly.
2.  This tool currently only supports the following resolutions: **1920x1080**, **2560x1440**, and **2560x1600 WIDESCREEN**. Using other resolutions will likely cause detection to fail.

### ✨ Features

* **Auto Detection**: No manual operation needed. The program automatically detects the Spike icon via screen recognition.
* **Overlay Countdown**: Displays a clear, large countdown timer in the top-left corner of the screen.
* **Color-coded Alerts**: As time runs out, the countdown number changes from white to orange, and finally to red.
* **Multi-resolution Support**: Built-in image recognition configurations for mainstream resolutions like 1K (1920x1080), 2K (2560x1440) and 2.5K (2560x1600)
* **Debug Mode**: An optional debug mode to view the real-time image match score.


### 📝 Credits

* This program uses [OpenCV](https://opencv.org/) for image processing.
* Uses the [mss](https://python-mss.readthedocs.io/) library for efficient screen capturing.
