# ADVANCED KEYBOARD TRICKS
**Note- Some of the key sequences covered here (particularly those that
use the ALT key) may be intercepted by the GUI for other functions. All of
the key sequences should work properly when using a virtual console**

## Cursor Movement

* <kbd>Ctrl</kbd> + <kbd>A</kbd> Move cursor to the beginning of the line
* <kbd>Ctrl</kbd> + <kbd>E</kbd> Move cursor to the end of the line
* <kbd>Ctrl</kbd> + <kbd>F</kbd> Move cursor forward one character; same as the right arrow key
* <kbd>Ctrl</kbd> + <kbd>B</kbd> Move cursor backward one character; same as the left arrow key
* <kbd>Alt</kbd> + <kbd>F</kbd> Move cursor forward one word
* <kbd>Alt</kbd> + <kbd>B</kbd> Move cursor backward one word
* <kbd>Ctrl</kbd> + <kbd>L</kbd> Clear the screen and move the cursor to the top-left corner
  * (same as `clear` command)

## Modifying Text

* <kbd>Ctrl</kbd> + <kbd>D</kbd> Delete the character at the cursor location
* <kbd>Ctrl</kbd> + <kbd>T</kbd> Transpose (exchange) the character at the cursor location with
the one preceding it
* <kbd>Alt</kbd> + <kbd>T</kbd> Transpose the word at the cursor location with the one preceding
it
* <kbd>Alt</kbd> + <kbd>L</kbd> Convert the characters from the cursor location to the end of the
word to lowercase
* <kbd>Alt</kbd> + <kbd>U</kbd> Convert the characters from the cursor location to the end of the
word to uppercase

## Cutting and Pasting (Killing and Yanking) Text

* <kbd>Ctrl</kbd> + <kbd>K</kbd> Kill text from the cursor location to the end of line
* <kbd>Ctrl</kbd> + <kbd>U</kbd> Kill text from the cursor location to the beginning of
the line
* <kbd>Alt</kbd> + <kbd>D</kbd> Kill text from the cursor location to the end of the
current word
* <kbd>Alt</kbd> + <kbd>BACKSPACE</kbd> Kill text from the cursor location to the beginning of
the current word. If the cursor is at the beginning of a
word, kill the previous word
* <kbd>Ctrl</kbd> + <kbd>Y</kbd> Yank text from the kill-ring and insert it at the cursor
location
