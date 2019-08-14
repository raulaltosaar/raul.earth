---
layout: default
title: A Very Real Looper
permalink: /a-very-real-looper
---

<article class="project">

<div style="padding:56.25% 0 0 0;position:relative;" class="iframe"><iframe src="https://player.vimeo.com/video/288778622?title=0&byline=0&portrait=0" style="position:absolute;top:0;left:0;width:100%;height:100%;" frameborder="0" webkitallowfullscreen mozallowfullscreen allowfullscreen></iframe></div><script src="https://player.vimeo.com/api/player.js"></script>

### A Very Real Looper ### 

#### A large, non-visual virtual reality instrument that is controlled using gesture and bodily movement. ####

A blog post describing the process behind the creation of this instrument can be read [here](/a-very-real-looper-post). In March I will be performing with this instrument at [the ACM International Conference on Tangible, Embedded, and Embodied Interactions](http://www.tei-conf.org/) in Tempe, Arizona (preprint available [here](/assets/pdf/physically_colliding_with_music_TEI.pdf)).

---

Contrary to how virtual reality (VR) is normally utilized, a performer playing A Very Real Looper *(AVRL)* is not disconnected from their surrounding environment through visual immersion, nor is their body restrained by a head-mounted display.

Rather, *AVRL* uses VR sensors in conjunction with a game engine to map musical sounds and sequences onto physical objects and spaces. These sounds are then by triggered by a performer wielding two controllers.

*AVRL* thus combines the affordances of the physical world with the modularity of a game engine. This integration results in a large, highly reconfigurable, and musically augmented performance environment.

<html>
<figure class="caption-object"><img src="assets/img/projects/a-very-real-looper/spheres_controllers_final_1.jpg">
<figcaption>A virtual view of <i>AVRL</i> captured in the Unity game engine which depicts the musical sounds (in red) and Vive controllers (in black).</figcaption>
</figure>
</html>

The current iteration of *AVRL* has been built inside of the Unity game engine for the HTC Vive system. The size of this instrument is determined by the distance between the Vive base stations. This instrument is extra-large in the sense that it usually comprises a medium-sized room but can be set up to have a maximum tracking volume of roughly 3600 cubic feet (19ft x 19fxt x 9ft).


First, Unity and the Vive base stations are used in conjunction to overlay virtual, three-dimensional (3D) models onto physical objects in the real world. These physical objects visually represent the locations of the 3D models to the performer. These 3D models have been programmed to detect collisions between themselves and the Vive controllers which are being animated in real-time using motion tracking data. 

<html>
<figure class="caption-object"><img src="assets/img/projects/a-very-real-looper/jumping_spheres.jpg">
<figcaption>A diagram depicting a performer colliding into musical sounds and sequences which have been overlaid as 3D models onto physical objects and locations inside the performance space. The objects act as visual markers that represent the location of the musical sounds or sequences to the performer.</figcaption>
</figure>
</html>

After detecting a collision, the 3D models trigger a musical sample, a MIDI sequence, or a specific MIDI note or chord at very low latency. Thus, inside of *AVRL* the performer is physically colliding with music. These musical sounds and sequences are triggered only once by default, but can be looped by pressing a button on the controllers. To further assist the performer with non-visually pinpointing the location of the 3D models, strong haptic feedback is provided by the controllers whenever a collision is detected.

Each 3D model contained by *AVRL* can be repositioned at any time to a new location within the performance space. This allows the performer to create novel sets of bodily interactions by mapping the 3D models into different locations before performing.

The Vive controllers also provide a wide range of easily accessible motion tracking data that includes movement speed, rotation, and position. Inside of *AVRL*, these data are used to control audio parameters in real-time. For example, a MIDI sequence is first looped and the intensity of an audio effect affecting that sequence is altered by moving the controller either higher or lower in space.

<div style="padding:56.25% 0 0 0;position:relative;" class="iframe"><iframe src="https://player.vimeo.com/video/303631624?title=0&byline=0&portrait=0" style="position:absolute;top:0;left:0;width:100%;height:100%;" frameborder="0" webkitallowfullscreen mozallowfullscreen allowfullscreen></iframe></div><script src="https://player.vimeo.com/api/player.js"></script>

<div style="padding:56.25% 0 0 0;position:relative;" class="iframe"><iframe src="https://player.vimeo.com/video/294810067?title=0&byline=0&portrait=0" style="position:absolute;top:0;left:0;width:100%;height:100%;" frameborder="0" webkitallowfullscreen mozallowfullscreen allowfullscreen></iframe></div><script src="https://player.vimeo.com/api/player.js"></script>



---

In November 2018 I was invited to present and perform with this project at the [Music In New Technologies](http://mintconference.ca/) conference in Halifax, Nova Scotia. This work was also featured in [a group exhibition](https://belindakwan.com/files/multiplecontingencies_catalogue.pdf) at the Society for Literature, Science, and the Arts conference in Toronto, Ontario.

</article>