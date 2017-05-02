# disport
Wrapper for xrandr to easily handle multi monitor setup

## Description

Provides easy access to the most important xrandr functions (at least to the ones I use most often), namely:
* Send the same output to all connected displays
* Restrict the output to the main display
* Extend the viewport across several displays

If you need any more elaborate xrandr functions, you better jus use xrandr.

## Usage

Clone output among all connected displays:

    python main.py c

Restrict output to main display:

    python main.py s

Extend output to the display left of the main display:

    python main.py e l

Extend it to the right:

    python main.py e r

## To-do

* Let the user specify the display for the restrict mode
* Let the user freely specify the arrangement of the displays for the extend mode
