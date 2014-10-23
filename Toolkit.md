<b>Toolkit challenges</b>

<b>UI for DU (moderate)</b>
<br>The free version of the Digital Universe is distributed with Partiview, a highly sophisticated, but technically challenging program. It was written in C (mostly) by a programming genius at the National Center for Supercomputing Applications at the U Illinois. While Partiview is lightweight (about 1 MB), multi-platform, and powerful, it suffers from a UI that is foreign to the uninitiated. This challenge aims to reduce the learning curve by designing a UI that is familiar to the masses, and includes the advanced features of data and graphics manipulation necessary to explore the universe.

<b>API for DU (moderate)</b>
<br>Build an API that understands the various data formats (in-house, VOTable, etc.) that we use for the DU. 

<b>UX to view DU on small screens (mobile / tablet) (difficult)</b>
<br>The comprehensive data sets that make up the DU are often large and complex. Initially, computer hardware was not capable of effectively displaying these data in realtime. Mobile technology has similar limitations, but the processing power in mobile devices is now capable of more complex graphics output. Building a mobile framework for the DU will involve advanced interface design and, perhaps more importantly, straightforward navigation capabilities. 

<b>Build a Working Solar System (very difficult)</b>
<br>One of the challenges with integrating data into open-source, expertly written software is the ability to change the initial focus of the software to something much larger in scope. For this reason, Partiview has never had a working solar system. A working solar system involves developing a reader for the ephemeris data of a given body (planet, moon, asteroid, etc.) as well as integrating NASA’s SPICE kernel so that mission data can be read and visualized.

<b>Wiki of resources (easy)</b>
<br>Create a wiki that catalogues the various databases, photos, apps, etc. of astronomy and astrophysics research 

<b>Scale transitioning (difficult)</b>
<br>One of the limitations in the free version of the DU, and specifically in the Partiview software, is the inability to transition to and from different scales. Our Milky Way data is in one system (parsecs) while our extragalactic data is expressed in millions of parsecs. In order to see these two scales in partiview, one must quit the program and load each scale independently. This means that once we leave the Milky Way, we hit a wall and we must quit, and load all the data outside the Milky Way to continue on. This challenge aims to sew these scales together by handling the scale transition automatically.

<b>Flight Status for Partiview (easy-moderate)</b>
<br>This challenge reveals flight data to the end user when they explore the DU. Of course, when tooling around the universe, one must violate the laws of physics, but how much faster than light speed do we travel? The goals here are to design an elegant display where the user can see their distance from Earth (or any targeted body), their flight speed in understandable units as well as units of c, and other position and nav information. 
