---
author: admin
date: 2002-03-06 02:05:03+00:00
draft: false
title: So the Paint-by-Numbers project, named
type: post
categories:
- Tech
---

So the Paint-by-Numbers project, named Go-Gan, is proceeding. Absolutely no interface has been coded yet, just the representation of the underlying puzzle. Tonight I'll write the logic that creates the list of clues from a row or column of painted cells.

After that's done, I'm going to skip over the hardest part of all, and go to the user interface and Cocoa bits. The hard part is a feature where a player working on a puzzle can get a hint.  No matter what hinting system I eventually implement, they all rely on the computer being able to (secretly) solve a puzzle completely. Certain scenarios may not require the whole puzzle to be solved in order to give the hint, but the real underlying purpose of this project, besides learning Cocoa, is to figure out how to get a computer to solve a PBN from just the clues.

All I know are the ad-hoc rules that Alison and I apply to a PBN puzzle, but sometimes there are several speculative steps needed, which will require the computer to perhaps build a branching tree of decisions, in order to arrive at a contradiction in all but one path from root to leaves.  The most important principle, though, is the "more than half", where a clue tells you there are _n_ cells colored black in a space where fewer than _2n_ will fit. This allows you to fill in some of the middle squares, which then give you information about the columns.
