# Table of Contents
1. [About UGChordstoFlats](#about-ugchordstoflats)
2. [How to use](#how-to-use)

# About UGChordstoFlats
Changes basic chord chart sharp chords to flats. Most useful in the context of transposition.
For (guitar or ukulele) chord charts on the site [Ultimate Guitar](www.ultimate-guitar.com/).

This implementation is a fork from https://github.com/hongjes1/UGChordstoFlats.
Actualy, it has been competely rewritten; the visible differences are:
* no change to the non sharped chords (the original implementation was rewriting B into Cb for instance)
* deactivate chord diagrams to prevent chord reset (on mouse over)
* less constraints on chord names: the '#' shall be the second character (second character after '/' for bass notes)

# How to use
1. Open a tab's page.
2. Open the javascript console: CTRL+SHIFT+J in Chrome, CTRL+SHIFT+K in Firefox, others: search the web for "open console <browser>" 
3. Copy/paste the code from __UGChordsToFlats.js__ into the console, then press ENTER.

Note: the chord diagrams are deactivated, because the code that displays them also resets the chord names.

[Back to top](#table-of-contents)
