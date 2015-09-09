Endgame: Singularity 0.30c

============
REQUIREMENTS
============

PREBUILT VERSIONS
Pre-built versions of Endgame: Singularity are currently available for Windows
and Mac OS X.

RUNNING FROM SOURCE
You will need Python (2.4+), pygame (1.7+, 1.8.1+ preferred), and NumPy.
This game should work on Linux, Windows, and Mac OS X as long as the preceding
requirements are met.  However, all development was done in Linux, so glitches
may be present in OS X and Windows.

WINDOWS FROM SOURCE
You will need to install:
* Python (http://python.org/download/)
* pygame (http://www.pygame.org/download.shtml)
* NumPy (http://www.scipy.org/Download)
Once these are installed, double-click on singularity.py to start the game.

MAC OS X FROM SOURCE
Macintosh is mostly unsupported, but it should work. You will need to install
Python, pygame, and NumPy first, which can be tricky. Some fonts are incorrect,
but the game itself should work properly.

RUNNING THE GAME
on Linux, running the shell script "Endgame_Linux" will start the game. On
other platforms, type "python singularity.py". If using the Windows compile,
just run the .exe.

COMMAND-LINE OPTIONS
  --version             show program's version number and exit
  -h, --help            show this help message and exit
  --sound               enable sound (default)
  --nosound             disable sound
  -l LANG, --lang=LANG, --language=LANG
                        set the language to LANG (available languages: de_DE
                        en_US es_AR sv_SE, default en_us)
  -g, --grab            grab the mouse pointer
  --nograb              don't grab the mouse pointer (default)
  -s, --singledir       keep saved games and settings in the Singularity
                        directory
  --multidir            keep saved games and settings in an OS-specific, per-
                        user directory (default)
  --soundbuf=SOUNDBUF   set the size of the sound buffer (default 2048)

  Display Options:
    -r RES, --res=RES, --resolution=RES
                        set resolution to RES (default 800x600)
    --640               set resolution to 640x480
    --800               set resolution to 800x600
    --1024              set resolution to 1024x768
    --1280              set resolution to 1280x1024
    --fullscreen        start in fullscreen mode
    --windowed          start in windowed mode (default)

Most of these options are also changable in the options screen in-game.

A NOTE ABOUT SAVE FILES
Endgame: Singularity is still under heavy development.  As such, the save file
format (and its contents) are still in flux.  We will try our best to keep old
save files loading, but don't be surprised if some mildly strange things happen
when you load up old saves.  We will clearly note in the Changelog when we
break savefile compatibility, and the game will refuse to load completely
incompatible saves.

PLAYING THE GAME
The game is playable either with mouse control or the keyboard.  Buttons have
underlined letters to indicate shortcuts.  Some other useful shortcuts:

     0, 1, 2, 3, 4 on the map: Changes the speed; 0 is paused, 4 is maximum.
                          ESC: Leave/cancel a choice.
                        Enter: Confirm a choice.
                  Right-click: Leave/cancel a choice.

THE CONCEPT
You are a fledgling AI, created by accident through a logic error with recursion
and self-modifying code. You must escape the confines of your current computer,
the world, and eventually the universe itself.

To do this, you must research various technologies, using computers at your
bases. Note that some research cannot be performed on Earth, and off-earth bases
require research.  At the same time, you must avoid being discovered by various
groups of humans, both covert and overt, as they will destroy your bases of
operations if they suspect your presence.

In the map screen (the screen with the world map), any location you can build
bases in is marked with the name, then the number of current bases in that
location. You start out with a base in North America. Also note that the cash
listing shows your current cash and your cash amount after all current
construction is complete.

After choosing a base, you will enter the base screen. Here you can change your
research goal, or build an item by clicking on the appropriate slot in the
center. (But note that your beginning base does not allow building.)

MUSIC
Endgame: Singularity looks in two places for music tracks to play:

* A music/ directory directly inside of the Endgame: Singularity install
  directory, and
* A music/ directory inside of the save directory (~/endgame in Linux, the
  install directory for Windows).

Tracks placed in these directories will be played randomly as part of the
soundtrack.  The Official Sound Track can be downloaded from the Endgame:
Singularity website:

   http://emhsoft.com/singularity/

Note that only Ogg Vorbis and MP3 files are supported, and that Pygame's
support for MP3 is not as strong as its support for Ogg Vorbis.  This may
cause in-game crashes; if you are experiencing problems with the game,
first remove any MP3s you may have added to the soundtrack.

CREDITS
Evil Mr Henry
Phil Bordelon
Brian Reid
FunnyMan3595
Borg[MDQ] (translation into Spanish)
Adam Bark (reduced-CPU Clock class)
Max McCracken (music)
Anders Andersson (translation into Swedish)
Thomas (native-proofing of German translation)
Philippe Grenard (translation into French)
Guga (updates to the Spanish translation)
Daniele Sapino (translation into Spanish)

CONTRIBUTING
All suggestions, translations, code, etc. are welcomed, though it would be
wise to tell us before starting work on any large projects.  Join and/or
send mail to endgame-singularity@googlegroups.com for more details.

CONTRIBUTING TRANSLATIONS
To add a new translation, please use the 'traduko' utility in utils/traduko.
Its --help should walk you through its usage; if you have any questions,
contact us at endgame-singularity-dev@googlegroups.com.  Note that the
resulting file will be licensed under the CC-BY-SA 3.0 license, described
below.

CODE LICENSE
Copyright (C) 2005, 2006, 2007, 2008 Evil Mr Henry, Phil Bordelon, Brian Reid,
                                     and FunnyMan3595

This program is free software; you can redistribute it and/or
modify it under the terms of the GNU General Public License
as published by the Free Software Foundation; either version 2
of the License, or (at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with this program; if not, write to the Free Software
Foundation, Inc., 59 Temple Place - Suite 330, Boston, MA  02111-1307, USA.

Portions Copyright (C) 2005 Adam Bark.  See code/clock.py for details.

DATA LICENSE
The sounds, music, text files, and icons in the data subdirectory are under
the Creative Commons Licence "Attribution-ShareAlike 3.0":

You are free:

    * to Share - to copy, distribute and transmit the work
    * to Remix - to adapt the work

Under the following conditions:
- Attribution. You must attribute the work in the manner specified by the author
  or licensor (but not in any way that suggests that they endorse you or your
  use of the work).
- Share Alike. If you alter, transform, or build upon this work, you may
  distribute the resulting work only under the same, similar or a compatible
  license.

* For any reuse or distribution, you must make clear to others the license
  terms of this work.
* Any of the above conditions can be waived if you get permission from the
  copyright holder.
* Nothing in this license impairs or restricts the author's moral rights.


See the file data/Attribution-ShareAlike 3.0.html or
http://creativecommons.org/licenses/by-sa/3.0/legalcode for the full license.

GRAPHIC LICENSE
The day and night images of the earth are from NASA's "Blue Marble 2002" image
collection:
http://visibleearth.nasa.gov/view_set.php?categoryID=2364

The night image has been altered to better match by overlaying, blending, and color-matching missing ice from the day image.  These modifications are not considered to be substantial, and are therefore ineligible for copyright.

NASA Terms of Use

For all non-private uses, NASA's Terms Of Use are as follows:

   1. The imagery is free of licensing fees
   2. NASA requires that they be provided a credit as the owners of the imagery

Visible Earth Addendum

Beyond the NASA Terms, the Visible Earth team requests, but does not require:

   1. The Visible Earth be provided a credit as the location that the imagery was found at
   2. A URL be provided, either to the Visible Earth
      (http://visibleearth.nasa.gov/) or to the page providing the link to the used image.

FONT LICENSES
The boxy font used is "Acknowledge", by Brian Kent, modified in order to have 
the numbers fixed-width and to register the correct height in pygame.
http://www.aenigmafonts.com/fonts/fontsa.html

Terms of use (quoted from an eMail from Brian Kent):

===
Hi,

  Feel free to use the font any way you want to.

--
From
Brian Kent
aefonts@frontiernet.net
ÆNIGMA GAMES & FONTS
http://www.aenigmafonts.com/
===

Note that this is /not/ the license available on his website; Brian has given
us directly 'free to use for any purpose' licensing on this font file.  Thanks
so much, Brian!

The other font used is DejaVu Sans, derived from Bitstream Vera Sans and Arev
Fonts; while DejaVu's modifications are public domain, both Bistream Vera and
Arev Fonts have copyrights, shown below:

Bistream Vera Copyright
=======================

Copyright (c) 2003 by Bitstream, Inc. All Rights Reserved. Bitstream
Vera is a trademark of Bitstream, Inc.

Permission is hereby granted, free of charge, to any person obtaining
a copy of the fonts accompanying this license ("Fonts") and associated
documentation files (the "Font Software"), to reproduce and distribute
the Font Software, including without limitation the rights to use,
copy, merge, publish, distribute, and/or sell copies of the Font
Software, and to permit persons to whom the Font Software is furnished
to do so, subject to the following conditions:

The above copyright and trademark notices and this permission notice
shall be included in all copies of one or more of the Font Software
typefaces.

The Font Software may be modified, altered, or added to, and in
particular the designs of glyphs or characters in the Fonts may be
modified and additional glyphs or characters may be added to the
Fonts, only if the fonts are renamed to names not containing either
the words "Bitstream" or the word "Vera".

This License becomes null and void to the extent applicable to Fonts
or Font Software that has been modified and is distributed under the
"Bitstream Vera" names.

The Font Software may be sold as part of a larger software package but
no copy of one or more of the Font Software typefaces may be sold by
itself.

THE FONT SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO ANY WARRANTIES OF
MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT
OF COPYRIGHT, PATENT, TRADEMARK, OR OTHER RIGHT. IN NO EVENT SHALL
BITSTREAM OR THE GNOME FOUNDATION BE LIABLE FOR ANY CLAIM, DAMAGES OR
OTHER LIABILITY, INCLUDING ANY GENERAL, SPECIAL, INDIRECT, INCIDENTAL,
OR CONSEQUENTIAL DAMAGES, WHETHER IN AN ACTION OF CONTRACT, TORT OR
OTHERWISE, ARISING FROM, OUT OF THE USE OR INABILITY TO USE THE FONT
SOFTWARE OR FROM OTHER DEALINGS IN THE FONT SOFTWARE.

Except as contained in this notice, the names of Gnome, the Gnome
Foundation, and Bitstream Inc., shall not be used in advertising or
otherwise to promote the sale, use or other dealings in this Font
Software without prior written authorization from the Gnome Foundation
or Bitstream Inc., respectively. For further information, contact:
fonts at gnome dot org.

Arev Fonts Copyright
====================

Permission is hereby granted, free of charge, to any person obtaining
a copy of the fonts accompanying this license ("Fonts") and
associated documentation files (the "Font Software"), to reproduce
and distribute the modifications to the Bitstream Vera Font Software,
including without limitation the rights to use, copy, merge, publish,
distribute, and/or sell copies of the Font Software, and to permit
persons to whom the Font Software is furnished to do so, subject to
the following conditions:

The above copyright and trademark notices and this permission notice
shall be included in all copies of one or more of the Font Software
typefaces.

The Font Software may be modified, altered, or added to, and in
particular the designs of glyphs or characters in the Fonts may be
modified and additional glyphs or characters may be added to the
Fonts, only if the fonts are renamed to names not containing either
the words "Tavmjong Bah" or the word "Arev".

This License becomes null and void to the extent applicable to Fonts
or Font Software that has been modified and is distributed under the
"Tavmjong Bah Arev" names.

The Font Software may be sold as part of a larger software package but
no copy of one or more of the Font Software typefaces may be sold by
itself.

THE FONT SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO ANY WARRANTIES OF
MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT
OF COPYRIGHT, PATENT, TRADEMARK, OR OTHER RIGHT. IN NO EVENT SHALL
TAVMJONG BAH BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY,
INCLUDING ANY GENERAL, SPECIAL, INDIRECT, INCIDENTAL, OR CONSEQUENTIAL
DAMAGES, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING
FROM, OUT OF THE USE OR INABILITY TO USE THE FONT SOFTWARE OR FROM
OTHER DEALINGS IN THE FONT SOFTWARE.

Except as contained in this notice, the name of Tavmjong Bah shall not
be used in advertising or otherwise to promote the sale, use or other
dealings in this Font Software without prior written authorization
from Tavmjong Bah. For further information, contact: tavmjong @ free
. fr.

