## Description

Simple X11 app example on mac os x in single file [xl01.cpp](xl01.cpp)

## Compile

	g++ xl01.cpp -o xl01 -I/opt/X11/include -I/opt/X11/include/X11 -L/opt/X11/lib -L/opt/X11/lib/X11 -lX11

## Run

* launch ```XQuartz.app```
* launch xterm from XQuartz
* run ```./xl01``` from xterm

screenshot

![](https://www.evernote.com/l/AAF3t3W7ss5Fjblvz4a9O-89aJesLSqi7dwB/image.png)

## Resources

* [http://www.geeks3d.com/20120102/programming-tutorial-simple-x11-x-window-code-sample-for-linux-and-mac-os-x/]()
