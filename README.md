# Overview

It is a minimal reproducible issue in which i asked in https://stackoverflow.com/questions/75542482/how-to-keep-google-chrome-extension-popup-opened-when-user-opens-dialog-file

Basically, i want to add a form with input text field and a button dialog file which allows user to upload a file.
When installed, it outputs something like :

![extension opened](/img/popup-opened.png)

Then, when i click on button for selecting file, it opens something like :

![dialog file](/img/dialog-file.png)

Finally, when i select the file, the popup is closed :

![select file](/img/select-file.png)
![extension closed](/img/extension-closed.png)

_NB_ : Image in directory `img/hello_extensions` is from https://github.com/GoogleChrome/chrome-extensions-samples/blob/main/functional-samples/tutorial.hello-world/hello_extensions.png

# Installation

Clone this project (or download zip file and extract it). Then go to chrome://extensions/, active `developer mode` and load unpacked extension.
