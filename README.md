# checkm8gui

checkm8gui is an application for macOS and Linux which adapts the [ipwndfu](https://github.com/axi0mx/ipwndfu/) command-line tool by [axi0mX](https://twitter.com/axi0mx/) to a graphical application.

## Credit

This program was written by [me](https://github.com/emeryferrari/), however this program would not be possible without the work [axi0mX](https://twitter.com/axi0mx/) has put into [ipwndfu](https://github.com/axi0mx/ipwndfu/) and the work [Srikanth Lingala](https://github.com/srikanth-lingala/) has put into [zip4j](https://github.com/srikanth-lingala/zip4j/).<br/>
[zip4j](https://github.com/srikanth-lingala/zip4j/) is licensed under the [Apache License 2.0](https://www.apache.org/licenses/LICENSE-2.0.txt).<br/>
zip4j Copyright 2010 Srikanth Reddy Lingala

## Testing

This program's GUI has been tested on an Ubuntu virtual machine and on a Windows machine, however, it has not been tested on a physical iOS device because I only own an S8003 iPhone 6s which is not currently supported by ipwndfu.<br/><br/>
UPDATE: On October 22nd, checkm8gui v0.2 was tested on a 2013 Apple TV 3rd generation and was successfully put into pwned DFU mode. No other functions of checkm8gui were tested and no other devices have been tested.

## Features

This program can enter your device into pwned DFU mode on a checkm8-compatible device. Once the device is in pwned DFU mode, this program can dump the SecureROM of the device, demote the device, or verbose boot the device. Features which are planned to be implemented in the near future are: decrypting keybags, changing your boot logo, restoring to signed and unsigned firmwares, and running custom ipwndfu commands.

## Disclaimer

This is not a tool for the inexperienced. This tool could seriously damage your device if misused. If you don't know what you're doing, stay away from this application. It is not feasibly possible to accidentally demote your device with this program. When the demote device option is chosen, multiple confirmation warnings are given before the task is carried out.

## Compilation/Execution

This tool can either be run from the .jar executable of the latest release in the Releases tab, or can be compiled using javac.

## Prerequisites

Java Runtime Environment or Java Development Kit<br/>
A Unix-based operating system

## Command-line arguments

-v/-verbose - Prints the command issued to the terminal along with the output of the command when an option is picked. This is not to be confused with verbose booting your iOS device.<br/>
--ignore-os - Launches the application regardless of what operating system it's being run on.<br/>
--ipwndfu-folder folder - A command to manually specify your ipwndfu folder location. This does not overwrite the location recorded in checkm8gui.bin. This folder specification will only persist in the current session.<br/>

## Known issues

There are many performance and consistency issues in the source code. None of these will affect your experience with the program in practice, however these are planned to be fixed in a future pre-release update nonetheless.

## Contacting me

I will respond to any PM I receive on Reddit.<br/>
[u/verystrangebeing](https://reddit.com/user/verystrangebeing/)