
# project-cusmf

Welcome to Project CustomMusicFile! Where you can create your own music file format!
## Picking your Music File

Let's pick your music file! It can be any music file (.mp3, .ogg, .flac, etc.) and convert it using https://cloudconvert.com/mp3-converter or https://www.freeconvert.com/audio-converter
## WARNING!!

Make sure that you convert to .wav, If your music file is already .wav then you can now proceed to Step 2.
## Trimming and converting to Base64

Make sure you trim your Music file or else the AUDIO=BASE64 will be extreemly long and cause crashes, 5-9 seconds is recommended.

### Converting to Base64

Go to https://www.base64encode.org/ and find the Encode files to Base64 format section, Then import your .wav file and wait for conversion, After the conversion, Download the .txt file.

## Creating the File Info and your Music File

Once you have your .txt file, Open it on Notepad (Windows), TextEdit (MacOS), or Text (ChromeOS), Then copy all of the code, Now create a new text file (Set .txt for now.) and paste this into the new text file:
```
MP1-FILE
TITLE=Whatever You Want
ARTIST=Whatever You Want
BITRATE=The song's BITRATE speed
AUDIO=BASE64:PASTE-YOUR-BASE64-HERE
```
Then save, Now go to your File Manager and rename the .txt to .(anything you want) Now open the project-cusmf-player.html by downloading and opening it.

# Credits

Huge thanks to ChatGPT for helping making this work

and Thanks to God/Allah that this project was possible, Bye!!

