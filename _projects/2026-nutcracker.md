---
layout: project
title: Macadamia Nutcracker Design
description: Designing a nutcracker
image: /assets/images/nutcracker-design.jpg
---

<h2>Find</h2>
<p>A design for a macadamia nutcracker with dimensions.</p>

<h2>Given</h2>
<p><b>Grip strength:</b> 30 kg<br>
<b>Macadamia nut size:</b> 2 cm<br>
<b>Load to crack nut:</b> 228.18 kg</p>
<p>(averages taken from internet)</p>

<h2>Plan</h2>
<p>First I decided to draw the FBD. I knew that it must be able to have a moment about the end joint, so two rods connected by a pin seemed like a logical and simple idea.</p>

<img src="/sp26-portfolio-ShahriarHabib1/assets/images/fbd1.png">

<p>The rods would have to be long enough to translate the grip force into enough torque to break the nut. The length of that rod is what we would need to solve for. In the FBD there is a pin at A, and Fb and Fc are the grip forces. Fb is one half of 228.18 which is 114.09 kg.</p>

<img src="/sp26-portfolio-ShahriarHabib1/assets/images/fbd3.png">

<p>If we take the moment about pin A, which is zero, we get that r*Fnut - l*Fb = 0. My first assumption was that Fnut and Fb would be proportional: greater the grip force applied, the greater the normal force of the nut on the nutcracker would have to be, and that l would also be accordingly proportional to r. We get that Fnut/Fb equals 7.606 which equals l/r. We know that the height of the nut is 2 cm, and so the distance between the handles must be 7.606*2 or 15.612 cm.</p>

<p>Second assumption is that the distance between A and where the nut touches rid AC can be anything: it wouldn't matter how far they were as long as the rod was accordingly longer. I said that the first distance could be 3 cm, and by the proportion of sides we set up, the length of the rod must be 3*7.606 or 22.818 cm.</p>

<img src="/sp26-portfolio-ShahriarHabib1/assets/images/fbd4.png">

<h2>Usability</h2>
<p>This seems pretty usable at almost 23 cm or 9 inches. We need some way to keep the nut from slipping. But the dimensions are usable.</p>

<p><i>Credit: Do capuchin monkeys use weight to select hammer tools?</i></p>

</body>
</html>
