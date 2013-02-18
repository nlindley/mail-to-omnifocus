# Send to OmniFocus and Archive

This is a simple service for OS X Mail and OmniFocus that takes the selected
messages and creates Inbox tasks in [OmniFocus][of]. It uses the email subject
is used for the title of the task, and a link to the message is used as a note.
This service also moves the message to the “Archive” folder if it exists.

## Usage

Clone this repository to `~/Library/Services`.

```
git clone https://github.com/nlindley/mail-to-omnifocus.git ~/Library/Services/Send\ to\ OmniFocus\ and\ Archive.workflow
```

If you would like a keyboard shortcut, go to System Preferences, Keyboard,
Keyboard Shortcuts. Select Services in the left pane and select the service in
the right pane. Click the `add shortcut` button and enter the key combination
you wish to use. If Mail is already running, you will need to restart it before
the keyboard shortcut will work.

## License

This software is released under the MIT License, which can be found in
`LICENSE.txt`.
