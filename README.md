# easy-audio
a simple command line tool that works with youtube-dl making downloading audio easier

##  Installation

Installing easy-audio is quite easy on OS X using cURL. Do the following in Terminal

    $ sudo curl -L http://www.easyaudio.nicelion.com -o /usr/local/bin/easy-audio

If curl doesn't work, download this repository. Once downloaded open Finder and type CMD+G. Input /usr/local/bin. Then, drag the easy-audio file from this repository into the bin. Then, see below to make it work.

Then, to make it work: 

    $ sudo chmod +x /usr/local/bin/easy-audio

Then you are all set! 

NOTE: easy-audio was created on a Mac using Mac OS X. easy-audio has not been tested on other operating systems. 

## Requirements

* [youtube-dl](https://github.com/rg3/youtube-dl)
* ffmpeg or avconv and ffprobe or avprobe

## Description

easy-audio "piggy-backs" off of rg3's [youtube-dl.](https://github.com/rg3/youtube-dl) easy-audio makes downloading mp3s from YouTube quicker and simpler.

##### youtube-dl vs easy-audio:

In youtube-dl, the command you enter may look like this:
  
    $ youtube-dl --extract-audio --audio-format mp3 https://www.youtube.com/watch?v=2HQaBWziYvY

In easy-audio, all you type in the Terminal is:
  
    $ easy-audio
  
You are then prompted to provide a link, and your file will download.

## Commands

When you start easy-audio, you will be asked to provide a link or a command. Below are a list of the commands you can use to get more information about the program, or some customization options.

    end                           Ends easy-audio
    
    clear                         Clears all youtube-dl output and previous files you downloaded
   
    pwd, directory,               Outputs the current directory you are in. This is where your files will be exported
    current-directory
    
    version                       Outputs the version number of easy-audio
    
    licence                       Outputs the easy-audio licence. (MIT Licence if you are wondering)
    
    help                          Outputs and lists some help options.
    
  
#### auto-clear

By turning auto-clear on, after each file is downloaded, Terminal will clear. 

To turn on auto-clear, simply type the following when easy-audio is running:

    auto-clear

You will be promted to provide "y" or "n". "y" will turn it on and "n" will either turn it off, or just cancel.

#### quiet-mode

youtube-dl will not show any output when quiet-mode is on. 

To turn quiet-mode on, simply type the following when easy0audio is running:

    quiet-mode
  
  -Or-
  
    quiet
  
  You will be promted to provide "y" or "n". "y" will turn it on and "n" will either turn it off, or just cancel.

## FAQ

Since easy-audio is very new and hardly anyone is using it, this really isn't "frequently asked questions," this is more of a "maybe some questions you have" section.

##### Q: I looked at the code of easy-audio, why does it look like a three year old who knows nothing about programming wrote it?
A: Well the awnser to that is, the person who wrote it knows hardly anything about programming. Well, at least bash. I have been programming for about 3 years, and as of writing this, only about two weeks in the bash programing language. This was my first program. It's simple and it works. For my purposes at least.


  
## Copyright

Anyone is free to use, or modify easy-audio. Do what ever you want with it. All I ask is for credit!
