# algo-comp

This composer lets you add multiple streams of notes, which can be 
produced by different instruments, provided by the Tone.js library. 
This is done by creating a stream of balls that bounce off a base. 
There are controls for the instrument, the size of the balls in the 
visualization, and the speed and bounce of the balls, that affect 
the sound generated.

<b>Instructions:</b> <br>
&ensp;♪ Press the [Setup] button to activate the environment - you will see a base appear. The following three steps are optional but enable customization of the sound and of the visualization. <br> 
&ensp;♪ Choose a desired radius for each shape in px and click [Submit] (suggested range: 1-20) 
(default: 10) <br> 
&ensp;♪ Select an instrument (default: Synth) <br>
&ensp;♪ Set controls for the speed and bounce of the shapes 
(speed range: 0.001-0.008, default speed: 0.005, bounce range: 0.001-0.01, 
default bounce: 0.005) <br>
&ensp;♪ Press [Add!] to add a new sound with your chosen controls! <br>
There is also a way to remove streams of balls after creating them, for more flexibility in customization of the composition. A button for each list will be shown each time a new stream of balls is added. Clicking on a button will remove the corresponding stream of balls. 

I wanted to make a kind of instrument that can be controlled, but also has an algorithmic aspect in the composition generation process. With this, one can control to a degree what kind of sound they want, and once controls are selected, the algorithm continues the process. The balls move in a sine wave, which is the bulk of the algorithmic aspect of this tool. The shape of the sine function is influenced by the 'speed' and 'bounce' controls. The control for the radius of the balls is for the visualization and does not influence sound. I include four options for the instrument from the Tone.js library, based on which ones I thought would work well together. The notes are fixed and each of the 21 balls in a stream plays a different note.


------------------------------------------------------------------------------
Shayna Kaushal for Online Algorithmic Music | UChicago | Spring 2023
