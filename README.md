[ Languages: [English](README.md), [中文](README-zh.md) ]

# perrots-batch-copy

- [Description](#description)
- [Installation](#installation)
- [Screenshot](#screenshot)
- [Usage](#usage)
- [Hot Key Table](#hot key table)
- [Contributing](#contributing)
- [History](#history)
- [License](#license)

## Description
Collect multiple texts from the clipboard on windows.

## Installation

1. Download the zip file [perrots-batch-copy.zip](https://drive.google.com/file/d/0B9-PjjwL3-xYZGJxV1ZjZ3E3aXc/view?usp=sharing).
2. Extract it and execute the executable file **perrots-batch-copy.exe**.

## Screenshot
![perrots-batch-copy main window](https://drive.google.com/uc?export=download&id=0B9-PjjwL3-xYVVFZYjVBYnp5NkU)

## Usage

1. Clicking the executable file to run it. It will open the main window and show a tray icon to your tray bar.
2. Selecting the menu item **File| Open** from the menu bar to load a text file. Or pressing hot key **Ctrl+O** to do it.
3. Selecting the menu item **File| Save As** from the menu bar to save all clipboard text into a text file. Or pressing hot key **Ctrl+S** to do it.
4. Selecting the menu item **File| Exit** from the menu bar to exit the application. Or pressing hot key **Alt+F4** to do this.
5. Selecting the menu item **Edit| Clear All** from the menu bar to clear all clipboard text in the listview. Or pressing hot key **Ctrl+L** to do it.
5. Selecting the menu item **Edit| Copy All** from the menu bar to copy all clipboard text into the system's clipboard. Or pressing hot key **Ctrl+C** to do this.
6. Selecting the menu item **Edit| Select All** from the menu bar to select all items in the listview. Or pressing hot key **Ctrl+A** to do it.
7. Selecting the menu item **Edit| Delete Selected** from the menu bar to delete selected items of the listview. Or pressing hot key **Delete** to delete selected items.
8. Selecting the menu item **Edit| Copy Selected** from the menu bar to copy selected items of the listview to the system's clipboard. Or pressing **Ctrl+Y** to do this.
9. Selecting the menu item **Tools| Enable Batch Copy** from the menu bar to switch the batch copy function. Or pressing **Win+B** to switch this function.
10. Selecting the menu item **Tools| Enable Half Transparent** from the menu bar to switch half transparent of the main window. Or pressing **Ctrl+T** to switch this function.
11. Selecting the menu item **?| Help Contents** from the menu bar to open the help url link in the web browser. Or pressing **Shift+F1** to do it.
12. Selecting the menu item **?| About Perrot's Batch Copy** from the menu bar to open the about link in the web browser. Or pressing **F1** to do it.
13. Pressing key **Ctrl** or **Shift** to select more than one item in the listview.
14. Pressing combination keys **Ctrl+Shift+[NO]** to paste the text of [NO]th item to the current edit area. NO is from 1 to 9.
15. Every copy action will show a tooltip beside your mouse point. The tooltip text is your copied data.
16. Just click the top right x button to exit the application.

## Hot Key Table
Hot Key | Function
------------ | -------------
Ctrl+S | Save all clipboard text into a text file
Alt+F4 | Exit the application
Ctrl+L | Clear all clipboard text in the listview
Ctrl+C | Copy all clipboard text into the system's clipboard
Ctrl+A | Select all items of the listview
Delete | Delete selected items of the listview
Ctrl+Y | Copy selected items of the listview to the system's clipboard
Win+B | Switch the batch copy function
Ctrl+T | Switch half transparent of the main window
Shift+F1 | Open the help url link in the web browser
F1 | Open the about link in the web browser
Ctrl or Shift | Select more than one item in the listview
Ctrl+Shift+[1~9] | Paste the text of [1~9]th item to the current edit area
Double Click|Double click on the listview's item to copy item to clipboard.

## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D

## History

- **7/14 V1.0.0**
- [+] Copy all items of the listview to the system's clipboard.
- [+] Clear all items of the listview.
- **7/16 V1.8.0**
- [+] Save all items to the user specified text file.
- [+] Exit application.
- [+] Select all items of the listview.
- [+] Copy these selected items of the listview to the system's clipboard.
- [+] Delete the selected items of the listview.
- [+] Press Win+B keys to switch the batch copy function.
- [+] Press Ctrl+T keys to switch the transparency of the window.
- [+] Press Ctrl+Shift+[1~9] keys to paste the [NO]th item of the listview into the current edit area.
- **7/16 V1.15.1**
- [+]Add icon to menu item.
- [+]Show tool tip in tool bar.
- [*]When the program runs, use delete key to delete some files doesn't work in system. Fix this problem.
- [+]Create a tool bar.
- [+]Save file as utf8 encoding.
- [+]Create a load file function to load text file. Use hot key Ctrl+O.
- [+]Double click on the listview's item to copy item to clipboard.
- [+]When the main window shown, load the previous clipboard text.

## License

GNU License
