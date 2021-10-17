# Python-YouTube-Downloader
The Youtube downloader project is a python project. The object of this project is to download any type of video in a fast and easy way from youtube in your device.

In this python project, user has to copy the youtube video URL that they want to download and simply paste that URL in the ‘paste link here’ section and click on the download button, it will start downloading the video. When video downloading finishes, it shows a message ‘downloaded’ popup on the window below the download button.
To implement this project we use basic concept of python, tkinter, pytube library.

Tkinter is a standard GUI library and it is one of the easiest ways to build a GUI application.
pytube used for downloading videos from youtube
These are the following steps to build youtube video downloader project in python :

Import libraries
Create display window
Create field to enter link
Create function to start downloading
1. Import Libraries
Start the project by importing the required modules.
In this python project, we import Tkinter and pytube modules.
Tk() used to initialize tkinter to create display window
geometry() used to set the window’s width and height
resizable(0,0) set the fix size of window
title() used to give the title of window
Label() widget use to display text that users can’t able to modify.
root is the name of the window
text which we display the title of the label
font in which our text is written
pack organized widget in block
link is a string type variable that stores the youtube video link that the user enters.
Entry() widget is used when we want to create an input text field.
width sets the width of entry widget
textvariable used to retrieve the value of current text variable to the entry widget
place() use to place the widget at a specific position
Url variable gets the youtube link from the link variable by get() function and then str() will convert the link in string datatype.

The video is download in the first present stream of that video by stream.first() method.

Button() widget used to display button on the window.

text which we display on the label
font in which the text is written
bg sets the background color
command is used to call the function
root.mainloop() is a method that executes when we want to run the program.
With this project in python, we have successfully developed the youtube video downloader project using python. We used the popular Tkinter library that used for rendering graphics. We use the pytube library to download videos from youtube.
