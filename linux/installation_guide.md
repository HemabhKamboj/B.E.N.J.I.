# B.E.N.J.I.

<h1 align="center">
<img width="400" src="https://raw.githubusercontent.com/the-ethan-hunt/B.E.N.J.I./master/benji_final.ico">
<br>
<br>
</h1>

**A digital assistant for your device with the capability of listening and following your orders.**
> Please note that you need to be connected to the internet and a working microphone for the Voice Recognition Engine to work properly.
You can always type in your commands in the Command Box and hit 'Enter' and B.E.N.J.I. will obey your orders.

# Contents

- [B.E.N.J.I.](#benji)
- [Contents](#contents)
  - [Installation in Linux](#installation-in-linux)
    - [Python 3.x installation linux](#python-3x-installation-linux)
    - [Virtualenv installation Linux](#virtualenv-installation-linux)
    - [B.E.N.J.I. Installation Linux](#benji-installation-linux)
  - [Intallation Guide (Windows)](#intallation-guide-windows)
    - [Python 3.x installation-windows](#python-3x-installation-windows)
    - [Virtualenv installation Windows](#virtualenv-installation-windows)
    - [B.E.N.J.I. Installation Windows](#benji-installation-windows)
  - [Features and commands of B.E.N.J.I](#features-and-commands-of-benji)
  - [FAQs](#faqs)

## Installation in Linux

Setting up B.E.N.J.I requires following things to be ready.

1. [Python3 Installed](#python-3.x-installation-linux)
2. [Virtualenv installed and activated](#virtualenv-installation)

### Python 3.x installation linux

Make sure you are connected to the internet and have python 3.x installed. <br>
To check python version, open Terminal with Ctrl+T and run the following command
Follow the following steps to install B.E.N.J.I.<br>
`python3 --version`

If you are using Ubuntu 16.10 or newer, then you can easily install Python 3.6 with the following commands:<br>

1. Update your system by
`sudo apt-get update` <br>

2. Install python 
`sudo apt-get install python3.6` <br>

If you’re using another version of Ubuntu (e.g. the latest LTS release), we recommend using the deadsnakes PPA to install Python 3.6:

`sudo apt-get install software-properties-common` <br>
`sudo add-apt-repository ppa:deadsnakes/ppa` <br>
`sudo apt-get update` <br>
`sudo apt-get install python3.6` <br>

If you are using other Linux distribution, chances are you already have Python 3 pre-installed as well. If not, use your distribution’s package manager. For example on Fedora, you would use dnf:

`sudo dnf install python3` <br>

### Virtualenv installation Linux

Virtualenv helps to get rid of any dependency errors.

1. Open Terminal with Ctrl+T or by searching in applications menu and run the following commands.<br>
`pip3 install virtualenv`

2. Create virtual environment using: <br>
`virtualenv venv`

3. Now activate virtual environment <br>
`cd venv` <br>
`source bin/activate`

### B.E.N.J.I. Installation Linux

After your virtualenvironment is activated, follow the below steps

1. Clone B.E.J.I.'s Github repository.<br>
`git clone http://github.com/the-ethan-hunt/B.E.N.J.I`

2. Change your current directory. <br>
`cd  B.E.N.J.I-master/linux`

3. Install the required python packages from `requiements.txt` by following command <br>
`pip3 install -p requirements-linux.txt`

4. Now finally, its time to run B.E.N.J.I. <br>
`python3 benji.py`

You can give voice commands to B.E.N.J.I after clicking the mic button or even write out command in the command box.

## Intallation Guide (Windows)

Setting up B.E.N.J.I requires following things to be ready.

1. [Python3 Installed](#python-3.x-installation-windows)
2. [Virtualenv installed and activated](#virtualenv-installation-windows)

### Python 3.x installation-windows

1. Open a browser window and navigate to the Download page for Windows at www.python.org.

2. Underneath the heading at the top that says Python Releases for Windows, click on the link for the Latest Python 3 Release - Python 3.x.x.

3. Scroll to the bottom and select either Windows x86-64 executable installer for 64-bit or Windows x86 executable installer for 32-bit.

4. Run the Installer: <br>
   Once you have chosen and downloaded an installer, simply run it by double-clicking on the downloaded file. A dialog should appear.
    > Important: You want to be sure to check the box that says Add Python 3.x to PATH as shown to ensure that the interpreter will be placed in your execution path.

5. Then just click Install Now. That should be all there is to it. A few minutes later you should have a working Python 3 installation on your system.

### Virtualenv installation Windows

Virtualenv helps to get rid of any dependency errors.

1. In your Command Prompt enter:
`pip install virtualenv`<br>
This will install virtuealenv in your system.

2. Now make a folder named BENJI and charge your directory to BENJI using <br>
`cd BENJI` <br>

3. Now make your virtualenvironment using<br>
`virtualenv env` <br>

4. Now to activate your virtualenv: <br>
`\path\to\env\Scripts\activate`

### B.E.N.J.I. Installation Windows

1. To downlaod BENJI go to
https://github.com/the-ethan-hunt/B.E.N.J.I.

2. Click on `Clone or download` button on in left side and then click `Download ZIP`

3. Extract this zip folder named BENJI that we created earlier.

4. We need to install some packages in order to run BENJI, for that change the directory in command prompt to B.E.N.J.I./windows with your virtualenv activated and run the following command: <br>
`pip install -r requirements-windows.txt`

5. After successfull installation of all the packages we are now ready to run BENJI. Run it using: <br> `python benji.py`
    
## Features and commands of B.E.N.J.I 

List of the things that B.E.N.J.I. can do:

>* In cases where the commands are separated by '/', use any one of the mentioned commands
>For example, use either ***What is your name*** or ***Identify Yourself*** or ***Who are you***. Don't type all of them at once.

-Know B.E.N.J.I. <br>
  "***Who are you/Identify Youself/What is your name***" for B.E.N.J.I. to introduce itself.
  
-Set a reminder <br>
  "***set a reminder***" to set a reminder.

-Search for a file on your Device <br>
"***lookfor/find*** _Filename_" to look for a file and open it.

-Print files <br>
"***print*** _NameOfTheFile_" to print that file.

-Play Youtube videos <br>
 "***play/stream/queue*** _Song/VideoName_" to play any song or video on Youtube.

-Download music <br>
"***download music*** _SongName_" to download a song.

-Search for any place on the Google Maps <br>
"***locate/spot*** _PlaceName_" to look for a place on Google Maps.

-Open any website that you ask it to, in your default browser 

-B.E.N.J.I. can also open G Suite apps in your broweser<br>

-Google Search <br>
"***search/google*** _ItemToBeSearched_" to google anything.

-Search for Images on Google Images <br>
"***images of*** _ImageToBeSearched_" to look up images on Google Images.

-Open Gmail to check your mails <br>
"***gmail*** to open gmail

-Google News <br>
"***news/google*** _open_"

-Google Translate <br>
"***translate*** _open_"

-Google Photos <br>
"***google photos*** _open_"

-Google Drive <br>
"***google driver*** _open_"

-Google Plus <br>
"***google plus*** _open_"

-Google Forms <br>
"***google forms*** _open_"

-Google Documents <br>
***google document*** _open_"

-Google Sheets <br>
"***google sheets*** _open_"

-Google Slides <br>
"***google slides*** _open_"

-Google Groups <br>
"***google groups*** _open_"

-Google Earth <br>
"***google earth*** _open_"

-Google Cloud Print <br>
"***google cloud print*** _open_"

-Google Fonts <br>
"***google fonts*** _open_"

-Open up Blogger <br>
"***blogger*** _open_"

-Search for anything on Google from the application itself <br>

-Search from Wikipedia <br>
"***wikipedia/wiki*** _ItemToBeSearched_" to search anything on Wikipedia

-Lock your device securely <br>
"***secure/lock device***" to lock your device.

-Look up latest news from Al Jazeera, BBC, Hindu <br>
"***al jazeera/bbc/cricket/hindus news*** to lookup news from respective networks

-Look up the latest cricket scores and news from ESPN Cricket <br>
"***cricket*** to check cricket scores.

-Shut Down your device instantly or set a timer <br>
"***shutdown after*** _hours_ _minutes_" to initiate a Shut Down Timer. <br>
 To cancel Timer  "***cancel shutdown***"  <br>
To instantly shut down your device "***shutdown now***"

-Restart your device <br>
"***restart now***" to restart your device.

-Create a file(txt, docx, pptx,xlsx, vsdx and rtf supported) <br>
"***create*** _filename_ _filetype_" to create a file where filetype maybe "text", "word", "powerpoint", "presentation", "excel", "visio" or "rich"

-Turn on and Turn off the wifi <br>
"***wifi*** _enable/disable_" to turn on and off the wifi.

-Launch any application <br>
"***launch*** _ApplicationName_" to launch any application where _ApplicationName_ may be
    * " _text_" for Gedit
    * "_chrome_" for Google Chrome
    * "_firefox_" for Mozilla Firefox
    * "_calculator_" for Calculator
    * "_office_" for Libre Office

_**Hope you enjoy using B.E.N.J.I.**_

_More features coming soon._

## FAQs

__**What is Benji?**__

*B.E.N.J.I.- The Impossible Missions Force's digital assistant*  <br>
It's desktop application which automates a lot of stuff for you on voice commands.

__**Can voice of Benji be changed?**__

Not yet, would you like to contribute in adding new voices. Checkout the [Contibution] section.

__**Can we add other custom tasks on Benji?**__

Yes of course, you are welcome increase the power of Benji. To make your feature to be added in the project,Checkout the [Contibution] section

