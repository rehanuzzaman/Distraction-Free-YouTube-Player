Description:
The Distraction Free YouTube Player is a simple command-line program written in C. It allows users to play YouTube videos in a distraction-free manner by opening them directly in a web browser window with specified parameters to minimize distractions. The program is designed to enhance focus and minimize interruptions while watching YouTube videos.

Functionality:

Upon execution, the program prompts the user to enter the URL of the YouTube video they want to watch.
After entering the URL, the program constructs a command to open the video in a new browser window with specific parameters:
autoplay=1: Automatically starts playing the video.
fs=1: Enables fullscreen mode.
disablekb=1: Disables keyboard controls to prevent accidental interruptions.
controls=0: Hides video player controls to reduce distractions.
loop=1: Loops the video continuously.
playlist: Specifies the video URL extracted from the input URL.
The constructed command is executed using the system() function, which opens the specified YouTube video in the default web browser.
The program displays a countdown message indicating the video will start playing in 3 seconds, then 2 seconds, and finally 1 second.
After the countdown, the program prints a message indicating that the video has started playing.
Finally, a thank-you message is displayed along with the author's website for more information.
Usage:

Compile the program using a C compiler (e.g., GCC).
Run the compiled executable.
Enter the URL of the YouTube video when prompted.
Wait for the video to start playing in the browser window.
Note:

The program assumes that the user has Google Chrome installed and configured as the default web browser.
Ensure that the system has an active internet connection to play the YouTube video.
The program does not handle errors such as invalid URLs or network connectivity issues.
