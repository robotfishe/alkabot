# alkabot

<img src="images/alkabot_assembly.PNG" height=360/>

The Alkabot is an open-source alkalinity monitor for reef aquaria, designed for maximum accuracy using widely available electronics and 3D-printed hardware. It is significantly cheaper than commercially available alkalinity monitoring solutions, costing well under $200 (depending on part sourcing).

<a href="https://youtu.be/Ts23RznHFv8">Here's a video about the project</a>

<P><b>Major updates to version 1.1:</b></P>
<ul>
<li>Reagent reservoir is no longer incorporated into the device - use your own container. This improves flexibility in installation and allows for larger reservoirs and less frequent top-ups. It also means you don't need to worry about watertightness on any of the joints between the acrylic panels during assembly.</li>
<li>Size of the device is reduced by about 20%, mostly in height. The biggest benefit here is that the case can now be cut from a single 600x300mm sheet of acrylic.</li>
<li>The code is now designed to work with an analog pH sensor board, which are significantly cheaper than the digital board previously advised.</li>
<li>Reaction chamber volume increased by 85%, allowing more water to be used for more accurate tests.</li>
<li>DISPLAY SCREEN AND TEST BUTTON! The most requested feature - while automated testing still requires setup with an MQTT server, you can now press a button on the front of the device and get a test readout on an integrated 0.96" OLED screen.</li>
<li>There is now a water level sensor at the top of the reaction chamber to prevent overflows. This is optional but highly recommended.</li>
<li>Pump head design has been completely overhauled to improve accuracy, reliability, and installation process.</li>
<li>Cooling fan has been removed. I've been running my unit without one for a while now and it doesn't seem necessary with the passive ventilation introduced on version 0.9.1.</li>
<li>The Alkabot now has a logo! It's designed to be laser engraved on the front case panel - completely optional of course.</li>
<li>Various improvements to the code, including integrating pump and pH calibration directly into the main sketch.</li>
</ul>

<P><b>Parts:</b></P>
<p>The casing is designed to be assembled from laser-cut 4mm acrylic. The part files (in .dxf format) can be found in the /laser directory. Of course, there's nothing stopping you from 3D printing them instead, if you have a printer with a big enough build volume.</p>

<P>The pump components, mounting brackets, reaction chamber, and other mechanical parts are designed to be 3D printed. These part files (in .stl format) can be found in the /3Dprint directory.</p>

<P>A full .step file for the assembly and all parts is also available in the /step directory, in case you wish to make any modifications to the design.</p>

<P>For non-user-manufactured parts, you can find the bill of materials under /documents.</p>

<P><b>Purchasing laser-cut and 3D-printed parts:</b></p>
<p>I am planning to offer packages for sale containing all user-manufacturable parts. Details will be added soon.</p>

<p><b>Tools and supplies:</b></p>
<p>Once you have all the parts, you shouldn't need more than a screwdriver, a small hex key, and a soldering iron to complete the assembly. You'll also need graduated cylinders (ideally 10ml and 50ml) to calibrate your pumps.</p>

<p><b>Software:</b></p>
<p>The software to run the monitor as well as that needed to test and calibrate the pumps before operation can be found under /code.</p>
<p>While a standalone mode is now available that lets you run a test with the press of a button and get a result readout on the device screen, any sort of automation will require a working MQTT server to send the command to start the test and receive the result.</p>

<p><b>Assembly instructions:</b></p>
<p>See the instructions file under /documents.</p>

<p><b>Warnings:</b></p>
<p>This project involves using hydrochloric acid, and while the concentrations you'll be using in the Alkabot itself aren't strong enough to harm you, if you buy more concentrated acid and dilute it at home <b>you need to wear appropriate protective gear and take reasonable precautions</b>.</p>

<p><b>Donations:</b></p>
<p>You are free to use this design for any purpose covered by the Creative Commons Attribution-NonCommercial-ShareAlike license at no cost. However, if you'd like to contribute to the cost of ongoing development, you can donate via the PayPal and Ko-Fi buttons below. 50% of any profit I make from this project will be donated to marine conservation charities.</p>

<a href="https://www.paypal.com/donate?business=EAHE9VLZCMH2Y"><img src="https://www.paypalobjects.com/en_US/i/btn/btn_donateCC_LG.gif" border="0" name="submit" title="PayPal - The safer, easier way to pay online!" alt="Donate with PayPal button" /></a>
<a href="https://ko-fi.com/Z8Z1394WD"><img src ="https://ko-fi.com/img/githubbutton_sm.svg"></a>

<p><b>Attribution:</b></p>
<p>The pump design is based on pump designs by the iGEN-Aachen team and Gervasi Alain, available under Creative Commons licenses from https://www.thingiverse.com/thing:2619479 and https://www.thingiverse.com/thing:4490134.</p>

<p><b>Version history:</b></p>
<p>Version 1.1.0 (23 July 2021):</p>
<ul><li>Major version release, see readme for details.</li></ul>
<p>Version 0.9.1 (14 January 2021):</p>
<ul><li>Added a 40mm fan mount and ventilation holes to the case parts.</li>
  <li>Swapped tank and waste pumps for better resistance to gravity siphon effect.</li>
</ul>
<p>Version 0.9 (11 January 2021):</p>
<ul><li>First public release.</li></ul>
