# Pd-Vanilla-MONO-MIDI-KEYBOARD
![mmk](https://user-images.githubusercontent.com/63967684/235366111-8b2f1cc2-f752-4f52-83d1-e2dba6ad2592.jpg)

This is an abstraction made for live performance, patch testing, and quick demos. 
You can switch from MIDI mode to FREQUENCY mode using the gray toggle. ù
Notes can be transposed two octaves above and below middle C (full 5-octave range).

Each key is a canvas placed on top of three bangs. This walkaround used to recreate the piano keyboard is very delicate. 
If you open the abstraction and click on a key (when in Edit-Mode), Pd will select the bang object underneath and not the canvas. 
Arranging each key is a very time demanding process so if you ever want to do that make shure to save a backup patch.
