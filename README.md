# Dino Game Automation

This script automates the popular Dino game found in the Google Chrome browser using Python's pyautogui library. The script captures the screen, detects obstacles (cacti and birds), and performs the necessary actions (e.g., jumping) to help the player achieve a high score.

## Table of Contents
- [How to Run](#how-to-run)
- [Additional Notes](#additional-notes)
- [Acknowledgments](#acknowledgments)

## How to Run

1. Install the required libraries by running the following command:pip install pyautogui
                                                                   pip install pillow
2. Open the Python script in an IDE or text editor.

3. Adjust the parameters or customize the code as needed.

4. Run the script and switch to the Google Chrome browser with the Dino game opened.

5. The script will automatically play the game by detecting obstacles and taking the appropriate actions.

## Additional Notes

- This script uses the pyautogui library to simulate keyboard inputs for controlling the Dino game.
- It utilizes the ImageGrab module from the Pillow library to capture the screen and process the image data.
- The `isCollide` function detects obstacles based on pixel values in the captured image.
- Feel free to modify the code to adjust the obstacle detection or enhance the gameplay.


