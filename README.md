# screen2gdrive

1. Install `maim`.
2. Install `rclone`.
3. Configure `rclone` with a google drive remote and call the remote `GoogleDrive`.
4. Set your window manager to run the included script `screen2gdrive` (for the
   straight download link) or `screen2gdrive --raw` (for the google drive
   preview link) whenever a certain key combo is pressed.

Now, whenever that key combo is pressed, a region of the screen will be
screenshotted, uploaded to google drive, and a link to it will be generated and
put on the clipboard.