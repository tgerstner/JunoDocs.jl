# Installation Instructions

Getting Juno takes a couple of simple steps:

## 1. Install Julia

First, download Julia (command line version) for your platform from the [downloads page](http://julialang.org/downloads/).

Then:

#### On Windows

1. Run the downloaded installer, using the default settings.

#### On OS X

1. Double-click the downloaded disk image to load it.
2. Drag the Julia-0.X.Y app onto the Applications folder shortcut.

#### On Linux

1. Unzip the downloaded folder and place it in your home directory.
2. Make sure to have dependencies curl and cmake installed.

## 2. Install Atom

Download, install and open [Atom](https://atom.io). If you have it already, make sure it's up to date (version 1.23+).

## 3. Install Juno

In Atom, go to Settings (`Ctrl+,`, or `Cmd+,` on macOS) or (File / Settings). 

Click on "Install" listed on the left.

In the search box at the top of the screen, enter "uber". Uber-Juno will show up. 

Click the install button in the package.

Atom will then set up Juno for you, installing the required Atom and Julia packages.

### Note

You may need to add the path to Julia if it is not accessible via the command `julia`. 

To do so, go to Settings (File / Settings) then click on Packages. [If you cannot find Julia, sometimes it is under Install] 

You are looking for julia-client. 

Once you have located it, click Settings. Look for "Julia Path and enter the location where Julia.exe can be found.
(example: C:\Users\UserName\AppData\Local\Julia-1.0.0\bin\julia.exe)

## 4. Use Juno

You should be good to go now -- try opening the REPL with Packages > Julia > Open Console or `Ctrl-J Ctrl-O` (`Cmd-J Cmd-O` on macOS) and press `Enter` to start a Julia session.


## Common Problems

If you experience problems after installing Juno, have a look at the [FAQ](@ref).
In case you can't solve your problem with the instructions here or in the FAQ,
then please post [at the discussion board](https://discourse.julialang.org/) and we're happy to help.

#### Juno could not be started.
Go to Packages > Julia > Settings and change "Julia Path" to point to the Julia
binary.
