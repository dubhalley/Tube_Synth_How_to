# Tube Synth - How to

The first one !! Whoooooohooooo :)
I'll describe all my journey of tube's noob :)

You'll find here my work in progress like a prototype :)


Maquette V 0.1
My partner wanted to get an idea of what it would look like.
I made a mock-up front panel and decided on a position for the tube. Wood, hot glue...

Quick and dirty :)

<img src='Pictures/maquetteA 0.1.jpg' width='400px'/>

<img src='Pictures/maquetteB 0.1.jpg' width='400px'/>



We agreed that it was a feasible project.
So I made a prototype using Dibond.

Paper stuck on the dibond

<img src='Pictures/ProtoA 0.2.jpg' width='400px'/>

A reliable/strong support for the tubes is needed, they don't have to move. I used another dibond for the tube sockets.

<img src='Pictures/ProtoB 0.2.jpg' width='400px'/>

I thought that perhaps with a second support I would have more space to put the components.

Even with a lot of otimism i realized that there wouldn't be enough space to make a clean assembly, 

<img src='Pictures/Proto 0.3.jpg' width='400px'/>


Ok, I'll opted for a rear panel to have enough space to put everything in neatly.
It will hold the tube holders, all the components, and the connection strips.

Side view

<img src='Pictures/Rear panel.jpg' width='400px'/>

Empty rear panel

<img src='Pictures/Empty rear panel.jpg' width='400px'/>

Full rear panel

<img src='Pictures/Full Rear Panel.jpg' width='400px'/>



## 1 - Choices : 

Tube modules take up space because everything is bulkier. In addition to the tubes, best practice dictates that you use 1W resistors, 400V capacitors, and thick wires :)

Very often, tube amplifiers do not use PCBs, but rather a direct connection between the components and the tube holder.

Some people are very particular about the wiring :D
With well-designed wiring, you can read the diagram live, making troubleshooting much easier.

To have a well done wiring we'll be using terminal strips for the tubes, making direct connections between tubes and components, not PCBs, but wire on the fly from component to component.

<img src='Pictures/Barrette de connexion.png' width='200px'/>

Some holes placed just above the potentiometers, jacks, and switches will allow the wires from these elements to be routed to the back panel.



## 2 - Front et Back panel : 

Want to make your own front panel ? : https://github.com/dubhalley/Front_Panel



Front panel : 

<img src='Files/FA VCO Dual.svg' width='400px'/>

Rear panel : 

<img src='Files/FR VCO Dual.svg' width='400px'/>



Define the position of your jacks, pots, switches, tubes, etc.

Try to keep in mind what each component is connected to in order to optimize the wiring.

There will be visible screws on the front panel to secure the rear panel in parallel with spacers.

I used the .svg file from the front panel to make the rear panel, so I have all my hole positions exactly right ;) 



## 3 - Schéma : 

I used this diagram :

<img src='Pictures/Cgs_ts23schematic.gif' width='400px'/>


I redid it with Kicad, trying to anticipate the wiring.

Kicad diagram :

<img src='Pictures/Kicad_VCO_Dual.png' width='400px'/>

With the symbols for kicad :


But, looking back, I think I could have done better...
I followed the original diagram too closely.
It's the first one ... beginner errors :)
Next time ... ;)


I created an .svg file with the component footprints to anticipate the wiring.

Rear panel wiring in theory :

<img src='Pictures/FR VCO Dual 3U Wiring V2.png' width='400px'/>

Full wired rear panel

<img src='Pictures/Full Rear Panel.jpg' width='400px'/>






## 4 - Knob : 

Want to make your own knob ? : https://github.com/dubhalley/Knob


For the knobs, I made a small improvement by digging a small recess on the top, so I can put a colored washer in it to get a position slider.

<img src='Pictures/knob.jpg' width='400px'/>

Files :

Knob : Bouton Tube V5.FCStd

<img src='Pictures/Potar.png' width='400px'/>

Hat : Rond de bouton.FCStd

<img src='Pictures/Rond de potar.png' width='400px'/>

## 5 - Case : 

Want to make your own case ? : https://github.com/dubhalley/Case


## 6 - Power supply : 

The master piece that makes the whole system work is the power supply. The one we're going to use comes from an old tube oscilloscope.


<img src='Pictures/Alim1.jpg' width='200px'/>

<img src='Pictures/Alim2.jpg' width='200px'/>

There will be 3 differents voltage at least :
* 150V DC
* 6.3V AC
* +/-15V

I'll be sure to make a documentation to find the right voltages with this kind of material. :)


