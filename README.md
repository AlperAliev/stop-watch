# stop-watch

Stop Watch

A simple stopwatch application that allows the user to start, stop, and reset a running timer. The display updates dynamically as the stopwatch counts seconds and minutes.

Features

Clean and minimal layout showing elapsed time

Three functional buttons: Start, Stop, and Reset

Automatic formatting with a leading zero for single–digit values (e.g., 07 seconds)

Minutes increase automatically when seconds reach 60

How It Works

The JavaScript logic handles all stopwatch operations:

Starts real-time counting when the Start button is pressed

Pauses the counter when Stop is pressed

Resets the timer back to 00:00 when Reset is pressed

Updates seconds every 1000 milliseconds

Adds leading zeros to numbers under 10

Converts 60 seconds into 1 minute automatically

The entire timer mechanism is managed through JavaScript variables and timed intervals.

Technology Stack

HTML

JavaScript

Responsiveness

The project is built for desktop use only and does not include responsive design.
