---
author: admin
date: 2007-02-04 18:14:07+00:00
draft: false
title: One view on the state of media-in-the-home
type: post
categories:
- Tech
---

Within the last year, I've purchased both an Xbox 360 and an HDTV (a 37" Sharp Aquos LCD). I have a TiVo, a home network, a Powerbook, and a fast PC with lots of storage. Surely somewhere in all of that is a viable, clean, easy to use method of expanding what I can enjoy on my home entertainment center to include my iTunes music, any downloaded video files, saved TiVo videos, and personal photos.

The executive summary is that I'm going to be purchasing a Mac Mini when they are next updated by Apple (should be soon), because that is going to be the most flexible entertainment hub. I also learned that our household is more of an Apple shop than I had guessed, mainly due to iTunes.

I have tried several scenarios, mostly focused on viewing downloaded TV shows on my TV:



  1. Streaming videos from Windows XP to the Xbox with on-the-fly re-encoding (explained below)
  2. Streaming videos from Windows XP to the Xbox with manually re-encoded files
  3. Streaming videos from Windows Vista Media Center to the Xbox
  4. Playing videos on TiVo
  5. Using my PowerBook plugged directly into the TV to play movies using Front Row


The Xbox 360 is designed to talk to any Windows XP machine using Media Player 11, or to Windows Media Center. You use different areas of the Xbox menus to access either of these two, and they have some differences and similarities. If you are connecting to plain Media Player, say for Videos, then you access a "Videos" item on the Xbox and it connects to the PC and shows a flat list of videos. Here are a few reasons that this seemingly futuristic capability completely sucks:

  1. The Xbox can only play movies in WMV format, which is very rarely used anywhere. This means that almost any video you already have, and any TV show you download from the internet, is in the wrong format to play on the Xbox. But let's pretend for a minute that you've converted everything to this format, as there are other things that suck.
  2. The video listing you get is a flat list with no playlists or other organizing schemes, and only the filename is shown, with no way to give it a piece of metadata like a title. This just does not scale to even 3 seasons of TV shows.
  3. When you play a video, you cannot resume playback to a previously-viewed point. You have to fastforward to where you were. This is a typical Microsoft UI oversight, and we ran into this issue approximately EVERY DAY.
  4. To populate this list in the first place, you must share your Windows Media Player 11 library using "media sharing". This seemed cool at first, since I thought that like iTunes, your library would be shared, since that's what the name says. Nope. None of your playlists are shared _for videos_, only your audio playlists. Instead, only the videos that live inside so-called "Watched Folders" are shared. This means you have to get Media Player to monitor a folder and have it always add any new files to your library. To me, the purpose of a media library is so that I can carefully catalog my personal media files, not use it as a dumping-ground of all files. On top of this, of course it does not work properly, so that when I had a new folder with 10 video files in a monitored location, only 8 of them would appear automatically, and I had to add the last two manually. Wow.


Let's go back and discuss WMV. When you convert one type of media encoding to another, it's called "re-encoding." So one must re-encode any movie in Xvid of Divx format (e.g. all downloaded TV shows) into WMV. There is a program called TVersity that comes really close to making this problem disappear. What it does is let you add any movie files to its list, and this list appears on the Xbox under the Videos area. So one cool thing is that it's simulating the media sharing feature of Media Player. But what's even cooler is that it will serve the Xbox an on-the-fly re-encoded WMV stream instead of the original file. This lets you have lots of Xvid files around, but the Xbox can still play them. Here are the disappointments of this setup:

  1. You cannot fastforward or rewind in a stream. So basically you can pause your videos, or stop them and restart from the beginning. That's it. Not too flexible.
  2. My PC (an Athlon XP 2500+) is evidently too slow to do all this in real time, despite playing with the setttings. So there were always 5-10 pauses per half-hour show, of 30 seconds each, each of which ended up skipping over a few seconds of video.


At this stage (I'm progressing chronologically through my experiments in this narrative), I decided I'd try to just re-encode a given season of a TV show we were watching all at once into WMV using some tool, and then stream these using media sharing. So I found a tool called Encode360 that has the Xbox in mind, and I started to re-encode. Here were the disappointments of this approach:

  1. There are three flavors of WMV. The best quality is offered by so-called WVC1, but to encode a 30 minute show in this format took about 90 minutes. Moreover, after doing two or three shows, Encode360 would crash, and so what should have finished in a day or so took me a week of restarting jobs before work and before going to bed.
  2. If you use the lower levels of WMV quality, you have to up the bitrate to get watchable video. But bitrate is directly proportional to file size, and so a 300MB Xvid file would become a 1GB WMV file. And since I want to keep the Xvid original, that's 1.3G per half-hour show!


Now let's talk about Media Center. You can think of it as a special version of Media Player that looks great on a TV and is easy to navigate with a remote control. It connects to a Media Center PC which itself runs a very similar-looking full-screen interface. Basically the Media Center PC streams all its data to the Xbox, so it becomes another way to view videos, music and photos. It doesn't really solve any of the above problems with encoding, since the Xbox still needs WMV format movies even inside Media Center. But if I were to re-encode all the movies myself (maybe by finding a better tool than Encode360) then maybe I could at least have a better organized interface for browsing playlists and having real Title metadata. Also, there's a plugin for Media Center that does what TVersity does (re-encode to WMV on the fly), but it crashed Media Center the first time I tried it. I like the Media Center interface, and if it let me organize movies I guess that would make me happy. But I still need to do all that re-encoding work, which I'm not willing to do.

One more item on Media Center. It also shares photos and music to the Xbox, but its whole metaphor for photos is just stupid old hard drive folders and filenames. We have tools like iPhoto on the Mac and Picasa on Windows now, that have transcended this old model by light-years. What about storing photos in albums? Or giving them Titles instead of filenames? Or giving them other metadata like tags and comments? None of this is in Media Center from what I could see. We have to keep everything organized by folder and filename, which is not where metadata should live. Lastly, if you use an iPod and buy music from iTunes, then the music sharing is not useful to you, since it can't play protected iTunes music, nor can it see your iTunes playlists.

Transitioning now, I have two friends at work who swear by Media Center. When I complained about my woes with the Xbox, they couldn't relate 100% because their setups are different in one key way: They have their PCs in their living rooms, directly connected to the home theater. They have so-called HTPCs (Home Theater PCs), and so they can play whatever video formats they want, since the Xbox is not involved. If you want one of these, then you need a new computer. But if you're going to go to that trouble, why not get a Mac Mini, which has Front Row, a similar piece of software to Media Center. I decided to try this by installing Front Row on my Powerbook, hooking it up to the TV, and seeing what was possible. Here are the wins.


  1. I can play any video file (MPEG, Xvid, Divx), since now you're using a Real Computer
  2. I can play iTunes music, including using actual, real library sharing from the iTunes library on my PC (the main repository of music in our house)
  3. I can see my iPhoto library, which I don't use since the photos are on our PC, so it's not so useful to me, but iPhoto is better than flat folders and files, so it wins in principle
  4. I can add videos to iTunes and give them Title metadata rather than use filenames. I'm still trying to find out if I can make playlists of videos. To do any of this, you need to use QuickTime to make a so-called "reference movie", which is a small file that a) can be added to iTunes, which doesn't accept .avi files directly and b) refers to the original and plays it, saving the space of a full re-encoding.
  5. The interface is nice of course, but comparably nice versus Media Center
  6. You can view video podcasts, something Media Player cannot do without third-party add-ins.


This was a breakthrough when I tried it using my PowerBook. I still kept all the movie files on my PC, and used file sharing to play them over the network. If I buy an inexpensive Mac Mini, I can make it its own component in my home theater and use Front Row all the time. If you're wondering where Apple TV fits into this, it would provide a _similar_ setup to a Mac Mini for less money, but it can only play MPEG4 and QuickTIme movies, which puts you in a re-encoding situation similar to the Xbox. But at least MPEG4 is a real open format with lots of tools available, unlike WMV.

TiVo was a nonstarter by the way, since although it can connect to a PC to play files, it can only play TiVo MPEG2 files.

Lastly, when it comes to recording TV shows over cable TV or satellite, you have another set of choices. Media Center and TiVo both do this, but not Front Row or Apple TV. If you want to record HD, you need to either buy a $2,000 HTPC or an $800 TiVo Series 3. When the Series 3 drops in price, I'll consider getting one.
