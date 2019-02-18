# ProcPlanets

ProcPlanets is a JavaScript web application for procedurally generating planets with exaggerated terrain.
It uses LOD to retain detail when zoomed in close and to save processing power when zoomed out.

**Author: Erik Martin Vetemaa**

## Running procplanets

- Clone the repo
- Uncomment online referances of external libraries and comment local references

Before:

```html
<!-- External libraries from the web -->
<!-- 
<script src="https://cdnjs.cloudflare.com/ajax/libs/stats.js/r16/Stats.min.js"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/three.js/r83/three.js"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/dat-gui/0.7.5/dat.gui.min.js"></script>
<script type="text/javascript" src="js/external/uuid_v1@latest.js"></script>
<script src="http://threejs.org/examples/js/controls/TrackballControls.js"></script>
 -->

<!-- External libraries from local machine -->
<script type="text/javascript" src="js/external/three.r96.js"></script>
<script type="text/javascript" src="js/external/stats.min.js"></script>
<script type="text/javascript" src="js/external/dat.gui.min.js"></script>
<script type="text/javascript" src="js/external/uuid_v1@latest.js"></script>
<script type="text/javascript" src="js/external/TrackballControls.js"></script>
```

After:

```html
<!-- External libraries from the web -->
<script src="https://cdnjs.cloudflare.com/ajax/libs/stats.js/r16/Stats.min.js"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/three.js/r83/three.js"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/dat-gui/0.7.5/dat.gui.min.js"></script>
<script src="http://wzrd.in/standalone/uuid%2Fv1@latest"></script>
<script src="http://threejs.org/examples/js/controls/TrackballControls.js"></script>

<!-- External libraries from local machine -->
<!-- 
<script type="text/javascript" src="js/external/three.r96.js"></script>
<script type="text/javascript" src="js/external/stats.min.js"></script>
<script type="text/javascript" src="js/external/dat.gui.min.js"></script>
<script type="text/javascript" src="js/external/uuid_v1@latest.js"></script>
<script type="text/javascript" src="js/external/TrackballControls.js"></script>
 -->
```

-

Open `procplanets.html` in a browser

## Tech

- [WebGL](https://www.khronos.org/webgl/) - a JavaScript API for rendering interactive 2D and 3D graphics within any compatible web browser without the use of plug-ins.

## Used libraries

- [Three.js](https://threejs.org/) - a cross-browser JavaScript library and Application Programming Interface used to create and display \* \* animated 3D computer graphics in a web browser.
- dat.gui.js
- perlin.js
- stats.js
- TrackballControls.js
- [node-uuid](https://github.com/kelektiv/node-uuid)

[threejsBoilerplate.html](https://gist.github.com/HalfdanJ/5ef9a6e22a017c6dd9caa0ec687dd5d4) was used as a boilerplate.
