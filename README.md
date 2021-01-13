# alkabot

<img src="images/alkabot_assembly.png" height=360/>

The Alkabot is an open-source alkalinity monitor for reef aquaria, designed for maximum accuracy using widely available electronics and 3D-printed hardware. It is significantly cheaper than commercially available alkalinity monitoring solutions, costing well under $200 (depending on part sourcing).
<P><b>Parts:</b></P>
<p>Both the main casing and the reagent reservoir are designed to be assembled from laser-cut 4mm acrylic. The part files for these (in .dxf format) can be found in the /laser directory.</p>

<P>The pump components, mounting brackets, reaction chamber, and other mechanical parts are designed to be 3D printed. These part files (in .stl format) can be found in the /3Dprint directory.</p>

<P>A full .step file for the assembly and all parts is also available in the /step directory, in case you wish to make any modifications to the design.</p>

<P>For non-user-manufactured parts, you can find the bill of materials under /documents.</p>

<P><b>Purchasing laser-cut and 3D-printed parts:</b></p>
<p>I am planning to offer packages for sale containing all user-manufacturable parts. Details will be added with the next version release.</p>

<p><b>Tools and supplies:</b></p>
<p>Once you have all the parts, you shouldn't need more than a screwdriver, a small hex key, and a soldering iron to complete the assembly. You'll also need graduated cylinders (ideally 10ml and 50ml) to calibrate your pumps.</p>

<p><b>Software:</b></p>
<p>The software to run the monitor as well as that needed to test and calibrate the pumps before operation can be found under /code.</p>
<p>The code assumes you have (or can set up) a working MQTT server to send the command to start the test and receive the result.</p>

<p><b>Assembly instructions:</b></p>
<p>See the instructions file under /documents.</p>

<p><b>Attribution:</b></p>
<p>The pump design is based on the work of the iGEN-Aachen team, available under a Creative Commons Attribution license from https://www.thingiverse.com/thing:2619479.</p>

<p><b>Version notes:</b></p>
<p>Version 0.9 (published week of 11 January 2021):</p>
<ul><li>First public release</li></ul>
