# Project adapted from PopcornTV
This project was adapted from the PopcornTV project which is now discontinued. Further work on this project will resume to make it compatible with MediaChannel API.

# What was PopcornTV?

PopcornTV was a simple application that allowed an AppleTV to stream Movies and TV shows directly from torrents. It pulls from [yts.to]() as well as the Popcorn Time TV API to allow users to watch most Movies and TV Shows Instantly.

This project is useful only to those running AppleTV 3 or older. <br>
For AppleTV 4 see the tvOS [MediaChannel App](https://github.com/bugs181/tvOS) (Coming soon!)

## How it worked

PopcornTV worked by hijacking the Trailers application on the Apple TV. In order to do this effectively we changed the DNS server on the Apple TV to point to the computer/server running this app. This application was initially created in 24 hours as a proof of concept that allows streaming torrents directly to an Apple TV by generating valid XML for it to read from. It has since grown into a much more full fledged application.

We pulled all of our Movies from [YTS]() by using the API that they provide. All TV shows used the [Popcorn Time TV API]()

## Modified version

The modified version of PopcornTV replaces the torrent engine with the MediaChannel API. <br>

*IMPORTANT*: Torrenting NO LONGER works with this application, please see the original project for that.<br>
However, it is entirely possible that a torrent engine may be added in at a later date which uses the MediaChannel Torrent channel.
 
## Warning
PopcornTV streams movies and TV shows from websites that are likely not from the true copyright holders.
 
Downloading copyrighted material may be illegal in your country. Use at your own risk.

## Demo
### Demo Images
![](http://i.imgur.com/7dB9zGp.jpg)
![](http://i.imgur.com/vigyOsZ.jpg)
![](http://i.imgur.com/296kywf.jpg)
![](http://i.imgur.com/S0yrFHo.jpg)
[More Screenshots](http://imgur.com/a/bKobV)

## Version History
- [0.1.5 - Quality Selection, Subtitles, Favorites](https://github.com/OstlerDev/PopcornTV/releases/tag/v0.1.5)
- [0.1.4 - Clean up Code, Implement Certificate Generation. Initial Release](https://github.com/OstlerDev/PopcornTV/releases/tag/v0.1.4)
- 0.1.3 - Add TV Show Support (broken)
- 0.1.2 - Redesign UI
- 0.1.1 - Implement VideoAPI
- 0.1.0 - Initial Testing

## IRC

Have a burning question that you need answered, or just want to chat with the developers? The developers and some bug testers are hanging on IRC at #PopcornTV on Freenode ([Click here if you do not have an IRC Client](http://webchat.freenode.net/?channels=PopcornTV)).

We do always reply, though sometimes it takes a little longer to respond if we are watching movies or coding.

License
----

If you distribute a copy or make a fork of the project, you have to credit this project as source.

This program is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with this program.  If not, see http://www.gnu.org/licenses/ .


PopcornTV - Streaming video to an Apple TV through torrents
Copyright © 2015  PopcornTV and the contributors
PopcornTV is released under the GPL
