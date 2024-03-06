# MTP

Keys in One-time pad encryption (OTP) should only be used once, when they get reused we can do a Many-time pad attack.

MTP Interactive uses automated cryptanalysis to present a partial decryption which can be solved interactively.

## Install and fix

Python 3.7+ required

Clone this repository and run the following command in the root directory with a terminal (i have also tested it in pycharm but it seems not to work properly in the terminal of pycharm, so i recommend using the terminal of your operating system.)


```
./cli.py <path_to_the_file>
```


Don't click on the window, use the arrow keys to move the cursor and the escape key (ESC) to open the menu.


[![asciicast](https://asciinema.org/a/204705.png)](https://asciinema.org/a/204705)

### Intstructions

Cursor movement is similar to Sublime Text:
 - Left, Right, Up and Down for simple movement
 - Home, End, Page Up and Page Down for larger movement
 - Left Click for jumping to mouse cursor

Letters can be entered using the keyboard any time.

The menu can be opened with the escape key. The "Export" button in the menu
will write the JSON state of the decryption to a file named 'result.json' by default. Use the -o flag to specify the desired filename for export.

You can exit the program cleanly using the "Quit" menu button.

Window resizing and text size changes are supported.

## Development

Use a Python 3.11 virtual environment to develop on this project

```
virtualenv venv -p python3.11
source ./venv/bin/activate
pip install -r requirements.txt
```

Pull Requests and Issues welcome!
