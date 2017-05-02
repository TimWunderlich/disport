# disport
Wrapper for xrandr

Provides easy access to the most important xrandr functions (at least to the ones I use most often), namely:
* Send the same output to all connected displays
* Restrict the output to only one display
* Extend the viewport across several displays

If you need any more elaborate xrandr functions, just use xrandr.

## Usage

Clone output:
    python main.py c

Restrict output to main display:
    python main.py s

Extend output to the display left of the main display:
    python main.py e l

Extend it to the right:
    python main.py e r
