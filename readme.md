# What is this Tarmak-dh
Tarmak-dh is a way to learn the Colemak-DH(m) keyboard layout in steps which make the transition easier. Colemak-dh(m) is a variation of the classic Colemak keyboard layout which moves the D & H keys to better positions [Explanation by stevep99](https://colemakmods.github.io/mod-dh/). The Colemak-DH(m) standard ergo mod is a variant upon Colemak-dh which was agreed upon to be jointly promoted by the community as it works well for row staggered and matrix keyboards.

## Specific keyboard layout being used
Tarmak-DH(E-T-R-O-I) for the Colemak-DH(m) standard ergo mod [read more on history here](https://forum.colemak.com/post/14803/#p14803)
aka [Tarmak-dh by DreymaR](https://forum.colemak.com/post/14801/#p14801) for SteveP's original mod of Colemak-dh. 

### ISO
Tarmak-DH(E-T-R-O-I) for the Colemak-DH(m) standard ergo mod 2020 (meant for those learning 2020 version of Colemak-DH(m) which is the latest version Colemak-DH on forums) [Tarmak-dh layout for ISO keyboards by DreymaR](https://forum.colemak.com/post/14801/#p14801)

![Tarmak-DH ISO keyboard](https://github.com/Caffa/Tarmak-DH-Mac/blob/main/Reference%20Images/Tarmak-DH%20Variant%20ISO.png)

Image by DreymaR, I drew on it to show which keys are changed for each layout.

### ANSI

![Diagram of how I changed ISO](https://github.com/Caffa/Tarmak-DH-Mac/blob/main/Reference%20Images/My%20Config%20TARMAK%20DH%20ANSI.jpg?raw=true "ISO vs ANSI Tarmakdh")
Diagram of how I changed ISO (left) to ANSI (right) (Added angle z mod).

# Instructions

Based on whether you have an ANSI keyboard (there is no key between shift and your z key) or ISO keyboard (there is a key between shift and your z key), go the either ANSI or ISO folders to find the keyboard layouts that you need.

- [ ] TODO insert keyboard layout comparison pics

ANSI has the angle z mod while ISO is just the [layout by DreymaR](https://forum.colemak.com/topic/1858-learn-colemak-in-steps-with-the-tarmak-layouts/#p14801)

## Installation
Put the bundle you need into either directories:
- /Library/Keyboard Layouts aka Macintosh HD > Library > Keyboard Layouts if you want to install system-wide for all users (recommended). It should ask for your password to move it.
- ~/Library/Keyboard Layouts aka Macintosh HD > Users > USERNAME > Library > Keyboard Layouts if you want to install for only yourself, so the keyboards won't be used for sensitive inputs like password entry.

Go to system preferences, keyboard > input sources and use the + button in the bottom left corner to add the keyboards listed below:
- TarmakDH 1a.keylayout
- TarmakDH 1b.keylayout
- TarmakDH 2a.keylayout
- TarmakDH 2b.keylayout
- TarmakDH 3.keylayout
- TarmakDH 4.keylayout
- Colemak DH ANSI.keylayout

You can select multiple to add at once.


## Usage

Order of progression - I think you can skip past (a) to (b) layouts if you want
- TarmakDH 1a.keylayout
- TarmakDH 1b.keylayout
- TarmakDH 2a.keylayout
- TarmakDH 2b.keylayout
- TarmakDH 3.keylayout
- TarmakDH 4.keylayout
- Colemak DH ANSI.keylayout

Also if you are on a mac, you can actually turn on the keyboard viewer in keyboard preferences so you have the keyboard up for reference.

Additionally I have wallpapers you can use for each keyboard in the Wallpaper folder, you can make your own with the images in the Wallpaper/DIY folder or go to the top right corner (...), Customise "..." and add your own panes (I color each change to make it easier to find the swapped keys)

## End keyboard 
You should end with Colemak DH + Z angle mod. This is the same as  https://github.com/ColemakMods/mod-dh/tree/master/macOS

# Useful 
Added a Wallpaper of this keyboard config (it's just modified slightly from ISO config Tarmak-DH) credit to 
https://forum.colemak.com/topic/1858-learn-colemak-in-steps-with-the-tarmak-layouts/#p14801
for original images


# Future work
Different implementations of ANSI Colemak DH https://colemakmods.github.io/mod-dh/keyboards.html#ansi-keyboards - Might want to do the wide mod.

## Tips
- Make sure you do the lower and uppercase when you customize in https://software.sil.org/ukelele/
- You can drag the keys in the app (speed up workflow)
- If you are duplicating a keyboard, remember to change the name
- Make a collection and export to get a .dmg, the bundle is inside.
- try to make your colored keyboard panels (checkout wallpaper folder to see example for each stage)

#FAQ
- It hasn't appeared in my system preferences: Log in and out. If that doesn't work check you have the TarmakDH ANSI Zmod.bundle in Macintosh HD > Library > Keyboard Layouts then restart.

- Clicking on it gives an error for Keyboard_Installer.KIErrorCode error 1. : Yes, have not figured out how to fix this. So only manual installation works now.

#TODO
- [X] ANSI keyboard
- [X] Wallpaper for ANSI
- [X] ISO keyboard
- [ ] Wallpaper for ISO ?
- [ ] Key fingering diagram
- [ ] Video on how I make the layouts
- [ ] Video on how to install layouts
- [ ] Videos on learning Colemak-DHm using Tarmak-dh (ANSI keyboard)

