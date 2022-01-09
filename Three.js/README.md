# Three.js I - Lab

## Objective: 
In this lab, you will familiarize yourself with Three.js, You will write your first Three.js code and learn how to set up your scene, camera and renderer!  
Moreover, you will be able to add 3D shapes to your HTML page and start visualising it properly.





<img src="https://blog.logrocket.com/wp-content/uploads/2020/12/threejs-geometries-materials.png" width="400">




## Instructions:
> Before we start, make sure to create a new HTML file, it can be in any code editor of your choice, which we will use to place the three.js code in. (It can also be placed in a javascript file)

### Part 1 : Set-up your first Three.js application!
 - In the `<script>` tags OR your `.js` file, import the three.js library by using: `import * as THREE from 'https://cdn.skypack.dev/three';`.
 - Start by creating the `new Three.Scene();`, and save it into a new variable called `scene`.
 - Add a new "Perspective Camera" to your three.js code (Look in the slides for reference) and save it in a new variable called `camera`.
 - Let's add the renderer and save it in a variable called `renderer` - Check out the slides for how to create a new renderer.
 - Lastly, make sure the renderer is *added* to the HTML page using DOM, with the following line: `document.body.appendChild(renderer.domElement);`. 
 

### Part 2 : Make sure everything is working.  
At the moment, you will not be able to see anything yet in your webpage if you followed only the steps done so far... that's because we are missing some essential code, let's fix that:
 - In the <script> tag where you're placing three.js code - make sure you set the `type` to `module`, so your line should be: `<script type="module">`. And this tells HTML that this JS script is from a library. (Which in our case, three.js)
 - Also, the renderer (our screen) looks to be a small screen in the top-left corner of our page. To fix that we need to add this line below the `renderer` variable line: `renderer.setSize(window.innerWidth,window.innerHeight);` - which sets the size of our renderer (screen) to the size of the HTML page window.
 - Again, related to the renderer - let's set the background color to white, by adding this line: `renderer.setClearColor("#e5e5e5");` - this will help us visualise everything clearer.
 - Lastly, let's set the camera Z position to 5, that way, when we place 3D objects - they will be visible and not on the same position... below the `camera` variable line, add: `camera.position.z = 5;`. 


### Part 3 : Let's add some 3D!  
Now we're supposed to be done with set up, and ready to place some 3D into our HTML page!! Let's start with a basic cube:  
- To add a cube, we need to create the `geometry`, `material` (which is the color/texture), and lastly combine them together, and add it to the scene:
- Let's start with creating the geometry by adding this line: `var geometry = new THREE.BoxGeometry();`.
- Next, setting the material: `var material = new THREE.MeshBasicMaterial({color:0xFFCCEE})`. - You can change the color to whatever you want using HEX Color Codes.
- Let's combine them together: `var cube = new THREE.Mesh(geometry,material);`.
- Add it to the scene: `scene.add(cube);`.
- Last but not least, we want to tell the renderer to work! Add this line in the bottom: `renderer.render(scene, camera);`. Congratulations! You should be able to see your very first 3D cube in your scene!  
  - Note: In the slides you may notice the `render` line is placed in an `animate()` function - It is not necessary to have this function, unless you are planning on moving things around in your scene. (animation)



<img src="https://threejs-journey.com/assets/social/open-graph-image-1200x630.png" width="600"> 



#### Great job!
##### Call an Instructor/TA to check your completed tasks!


## Bonus:
#### 1) Animate your cube! Make it rotate, or move around, as you like!

#### 2) Add your own/custom 3D models! Research on the web how to download free 3D models, and learn how to integrate them within your Three.js app! 


<img src="https://res.cloudinary.com/practicaldev/image/fetch/s--ZUlcD2l---/c_imagga_scale,f_auto,fl_progressive,h_420,q_auto,w_1000/https://dev-to-uploads.s3.amazonaws.com/uploads/articles/0r3df51nc87rwhy7jwoq.png" width="350">
