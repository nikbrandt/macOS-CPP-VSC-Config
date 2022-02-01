Oi! Welcome to the janky VSC setup.

## Compiling

 - To compile the current file: `Cmd + Shift + B`
 - To compile all .cpp files in the directory of the currently selected file: `Cmd + T` and select "build dir files"

## Debugging

 - Compile using either method above
 - Keep open the file whose name matches the compiled executable
 - Go to the debugging VSC tab on the left
 - Run either the Intel or ARM configuration based on your computer architecture
 - (If you want to compile before debugging each time, uncomment the `preLaunchTask` in `launch.json` and set it to your preferred pre-launch script from `tasks.json`.)

## Terminal Navigation
 - Focus/unfocus terminal: `Ctrl + \``
 - Next terminal window: `Ctrl + Tab` (when terminal focused)
 - Focus terminal 1: `Alt + 1`
 - Focus terminal 2: `Alt + 2`
 - Focus terminal 3: `Alt + 3`

## Tab navigation

(This is built into VSC)

 - Focus tab 1 of current window: `Ctrl + 1`
 - Focus tab 2 of current window: `Ctrl + 2`
 - ...etc
 - Move right a tab: `Cmd + Alt + ->`
 - Move left a tab: `Cmd + Alt + <-`

 ## Other VSC things
 - Command palette: `Cmd + Shift + P`