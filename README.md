# POV_WebGL_Shadows
In this activity, we need to modify the shadow projected on the ground by the pawn and the different objects that are placed within the scene.

For this, we first define all the different variables that will be needed.

![](/Img/variables.png)

Then we create the new fragment shader.

![](/Img/fsshadowsource.png)

Once this is done, we build the new program in the gameloop function using the new fragment shader, and later specify the locations in the getAttributeLocations task.

![](/Img/gameloop.png)

![](/Img/variables_assignation.png)

To render the shadows, we use the uniforms and the attributes of the locators within the draw task.

![](/Img/draw.png)

Obtaining this result

![](/Img/gif.gif)
