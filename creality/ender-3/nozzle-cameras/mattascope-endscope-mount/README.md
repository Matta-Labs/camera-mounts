<!-- WHEN SHARING MOUNTS, FILL OUT THIS TEMPLATE AND ADD AS 'README.md' IN MOUNT FOLDER-->

<!-- HEADER -->
<br />
<div align="center">
  <a href="https://github.com/Matta-Labs/camera-mounts">
    <img src="images/mattascope.png" alt="Logo" width="400" height="300">
  </a>

<h3 align="center">Mount: MattaScope Endoscope Mount </h3>

  <p align="center">
    This is a simple, one-piece mount to allow a cheap, off-the-shelf endoscope to work as a nozzle camera for a range of Creality Printers (Ender 3 for sure - need to test on others)
    <br />
    <br />
    <a href="https://github.com/Matta-Labs/camera-mounts/issues">Report Problems</a>

  </p>
</div>


<!-- ABOUT THE PROJECT -->
## Mount Details

<b>Compatible Printer:</b> Creality Ender 3
<br />
<br />
<b>Compatible Camera:</b> Pancellent Auto Focus Endoscope 1944P HD Borescope Camera - https://shorturl.at/osMPY, https://shorturl.at/nquC0 
<br />

### Built With 🛠️

* [![Fusion360][Fusion.360]][Fusion-url]


<!-- INSTALLATION -->
## Installation ⚡️

Mount installation is simple - requiring no other components or tools! We recommend printing in ASA, to give better thermal resistance, but PLA also works.

<p>
  <b>Slicing/Printing</b>

  1. Slice with normal or tree supports, with the cable holder flat against the bed.
  <div><img src="images/slice.png" alt="Slicing orientation" width="400"></div>
  2. We usually recommend a layer height of 0.2mm, and a brim for bed adhesion.
  <br>
  3. Print in ASA for longevity, but PLA works fine also.
  <br />
  <br />
</p>
<p>
  <b>Installation</b>

  1. Clip the endoscope into the mount, and secure the cable by pushing it into the clasp.
  <div><img src="images/clip.png" alt="Clipping endoscope into mount" width="400" height="300"></div>
  2. Locate the right-hand belt holder behind the extruder head
  <div><img src="images/belt-holder.png" alt="Belt holder" width="400" height="300"></div>
  3. Carefully push the mount onto the belt holder - until the back wall of the mounting clip is fully underneath the X-axis extrusion.
  <div><img src="images/in-place.png" alt="Mount in place" width="400" height="350"></div>
  <br />
</p>

If used with the recommended endoscope, we have found the optimum focus value to be 530.

Set this with ```sudo v4l2-ctl --set-ctrl focus_automatic_continuous=0``` & 
```sudo v4l2-ctl --set-ctrl focus_absolute=530```

<br/>

If using a Raspberry Pi, you can ensure these commands run on boot, and therefore are saved by adding these two lines to ```/etc/rc.local``` with ```sudo nano /etc/rc.local``` from root.

<br/>

📸 Print, install and enjoy! Please leave feedback for this mount in the appropriate FEEDBACK.md file.


<!-- LICENSE -->
## License 📄

Distributed under the MIT License. See `LICENSE.txt` for more information.


<!-- CONTACT -->
## Contact 📞

Tom Walker - [tomwalkr](https://github.com/tom-walkr) - tom@matta.ai


<!-- ACKNOWLEDGMENTS -->
## Acknowledgments

Credit to Douglas Brion for original ideation/design and to Christos Margadji for revision and printability improvements.

* [Douglas Brion](https://github.com/dougbrion)
* [Christos Margadji](https://github.com/cemag1)



<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[Fusion.360]: https://img.shields.io/badge/Autodesk-Fusion%20360-FC6E26?style=for-the-badge&logo=autodesk&logoColor=white
[Fusion-url]: https://autodesk.com/products/fusion360/overview
