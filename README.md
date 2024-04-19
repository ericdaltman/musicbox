# musicbox
A Linux Bash Script to play and compose 'beep' based music.

Currently a single BASH script file that contains the note list, single-note player, and multi-note composer.

Notes are entered in the notation of <Letter><option S=Sharp or B=Flat><Octave>
  Ex: F8 (for the F note of the 8th Octave) or EB5 (For an E flat in the 5th Octave)

When you enter Composer ('c') Mode, you enter the notes in order. When you hit enter it will play what you've written and allow you to add more to the end. Using a "-" in Composer Mode deletes the last note entered. When you type 'done' it will write out and perform a very simple 'beep' line with all the notes entered. Currently there are no length or repetition options, each note is composed with the default 200ms length added for easy manipulation after finishing the script.
