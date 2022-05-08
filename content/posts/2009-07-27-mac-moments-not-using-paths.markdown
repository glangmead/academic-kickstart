---
author: admin
date: 2009-07-27 03:14:45+00:00
draft: false
title: 'Mac Moments: Not using paths'
type: post
categories:
- Misc
---

On my Mac, I had a movie in my Movies folder called "Sesame Street Season 1 part 1.m4v". I dragged it to iTunes so I could play it there (for my daughter), and all was well. One day I wanted to move those old Sesame Streets into a folder called "old", so I made the "old" folder and dragged that movie in, no big deal.

iTunes still had a record of that movie file of course, but what happens when I ask iTunes to play it? What do you think _ought_ to happen? What do you _wish_ would happen? What do you think computers are _capable_ of enabling to happen?

I'll tell you what happens on a Mac: it plays the movie, and on Windows and all other operating systems, it does not. This is not about iTunes. The distinction holds for any piece of software at all that maintains pointers to files, whether it's a media organizer, or a Recent Documents feature in a word processor. This is because on Windows, there is no other system-provided mechanism for storing file locations besides paths. Paths include the name of all enclosing folders, plus the filename, plus of course the drive letter on Windows, e.g. "C:\Documents and Settings\Greg\My Movies\Sesame Street Season 1 part 1.m4v". If I change the path to include "old" partway along the chain, which is what moving the file into "old" amounts to, then the path has changed and the original path is invalid, it points to nothing.

I will not describe the technical details of the mechanism the Mac uses instead, because frankly it doesn't matter, that's the whole point. It's a smart piece of technology that hides from the user, but enables the user to work in a more intuitive way. It permits all software not to be sensitive to changes the user makes to the locations of files or folders.

This mechanism has existed since the early days of the Mac. It's not some fancy modern cpu-intensive disk-intensive feature that indexes your hard drive or anything. It's just a better way of storing file locations in software, since users like to move stuff around.

This is one of those differences that I usually have trouble articulating, but subconsciously affects all my decisions, just like the fragility of paths affects many of my decisions when I'm using Windows.
