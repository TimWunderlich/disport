# disport
Wrapper for xrandr to easily handle multi monitor setup

## Description

Provides easy access to the most important xrandr functions (at least to the ones I use most often), namely:
* Send the same output to all connected displays
* Restrict the output to the main display
* Extend the viewport across several displays

If you need any more elaborate xrandr functions, you better just use xrandr.

## Install

    pip install disport

## Usage

List connected displays and their resolutions:

    disport --list

Clone output among all connected displays:

    disport --clone

Restrict output to main display:

    disport --solo

Extend output to the display left of the main display:

    disport --extend left

Extend it to the right:

    disport --extend right

## To-do

* Let the user specify the display for the restrict mode
* Let the user freely specify the arrangement of the displays for the extend mode
* Provide fallback if two displays have no common resolution
