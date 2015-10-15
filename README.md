# hydrogen-TD4-drumkit
A drum kit for the hydrogen drum machine that emulates the Roland TD4
module.

Intended for use on hydrogen 0.9.7, I can make no promises how it will 
function on other versions.

This kit is mainly intended to generate MIDI files that can be 
imported into the Roland DT1 application with the note values set 
correctly, using this kit with the TD4 as an input source to hydrogen
will almost certainly not work and isn't supported but may be later.

Installation
============

1. Launch hydrogen.
2. From the 'Instruments' menu select 'Import Library'.
3. From the 'Sound Library Import' dialog select the 'Local File' tab.
4. Click the 'Browse' button.
5. In the 'Import drumkit' dialog, navigate to the folder
   'hydrogen-TD4-drumkit', select the file 'hydrogen-TD4-drumkit' and
   click the 'Open' button.
6. Back in the 'Sound Library Import' dialog, click the 'Install' button.
7. Click on the 'OK' button to dismiss the confirmation dialog.
8. Back in the 'Sound Library Import' dialog, click the 'Close' button.

Usage
=====

1. In the 'Sound Library' pane (bottom left of the hydrogen window), right
   click on the 'TD4 Kit' and select 'Load' from the menu.
2. Create your patterns and songs as usual using the TD4 kit.
3. From the 'Project' menu select 'Show info'
4. Enter the required details, the 'Song name' & 'Author' values will be 
   embedded in the final MIDI file. Click 'OK' to close.
5. From the 'Project' menu select 'Export MIDI file'.
6. In the file dialog, navigate to the required output folder, name the 
   MIDI file and click 'Save'.

Your MIDI file should now be available for use.
