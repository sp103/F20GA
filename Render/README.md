# F20GA_Coursework
# Modelling
## Lamp
![lamp reference](Appendices/references/lamp.jpg)
*reference image*

For the main stand part of the lamp I used a cylinder and added edge loops and moved the vertexes to add the details.

I then created the lampshade using a resized cylinder, I selected half the faces and deleted them. I then extruded the remaining faces to give the lampshade thickness. To give the lampshade the shape of the one in the reference I beveled the edges.

I positioned the lampshade to where it would be next to the stand and created cyinders to connect the stand and lampshade and added spheres at the joints.

For the lightbulb I created a cylinder and resized it then added edge loops and moved the vertexes to give it the shape.

I wanted the connecting part from the stand to the cylinder to be curved like the reference, but I couldn't get the curve and have it line up with the lampshade.

![lamp](Appendices/render_screenshots/lamp.PNG)

For the materials I used the arnold preset gold for the stand and changed the colour of the ceramic preset for the lampshade.

## Phone
![phone reference](Appendices/references/phone.jpg)
*reference image*

For the main body of the phone I created a cube and resized it, I then used edge loops and resized the vertexes to give it the curved look from the reference image. I gave the edges a slight bevel so the edges weren't hard.

I created a second cube and resized it for the base section and beveled the edges so it was curved like the reference.

I created a cylinder to use for the dial. To give it the holes for the numbers I created a smaller cylinder the went all the way through the main cylinder, I cloned this cylinder and positioned it for each of the holes. I selected all these cylineders and used the boolean difference tool to create holes where all the cylinder were. I used the same method for the indent in the middle by not moving the cylinder all the way through. I then rotated and positioned the cylinder to it's place on the phone body.

Next I made the handset, for this I created a cube and used edge loops to give it the curved handle. I then created a sphere and deleted half the faces, then bridged the gap. I then created a cylinder with a slighly bigger radius for the speaker. I positioned it with the rest of the handle and cloned it for the other side. I then moved the vertexes of the handle to connect with the speaker and used symmetry to make it the same for each side.

I positioned the handset and the main body next to each other and created a cube and resized it to hold the handset, I then beveled the top to make it rounded and cloned it 3 times to hold the handset.

![phone](Appendices/render_screenshots/phone.PNG)

For the dial I used the preset arnold plastic material with the base and subsurface colours changed to black and for the dial I used the chrome material.

## Coat Stand
![coat stand reference](Appendices/references/coat_stand.jpg)
*reference image*

For the main part I resized a cylinder and beveled to top to give it a bit of detail.

I then created a curve path for the bottom part and extruded a cylinder with the same radius as the main part along the curve. I cloned this and rotated it for the 4 feet parts. I used the same method for the top hook parts.

I created toruses and resized them for the parts connecting the feet.

![coat stand](Appendices/render_screenshots/coat_stand.PNG)

I used a matt material with a brown colour for the whole coat stand.

## Desk
![desk reference](Appendices/references/desk.jpg)
*reference image*

I created and resized 3 cubes for the main part, I beveled the corners for the shape. I then cloned this and made it slighly bigger and beveled that for the detail part. I then created another cube and resized and beveled it for the top part of the desk.

![desk](Appendices/render_screenshots/desk.PNG)

I used a darker verion of the coat stand material for the desk.

## Chair
![chair reference](Appendices/references/chair.jpg)
*reference image*

For the seat of the chair I resized a cube and beveled the corners. I then cloned the seat and put a scaled down seat into that seat and used boolean difference to give just the back curve of the chair. I resized the y of that part and deleted some of the faces to give the bars at the back and briged the gaps for the depth.

for the base I put 2 different sized cylinders on top of each other. For the legs I took a cube and used edge loops to cut some parts from it and beveled the edges to make it curved. I rotated a cylinder for the wheel and cloned the leg and wheel 4 times for the legs.

![chair](Appendices/render_screenshots/chair.PNG)

I used the same material as the coat stand for the legs and seat part and used the brushed metal with the colour changed to black for the wheels and support part.

## Filing Cabinet
![filing cabinet reference](Appendices/references/filing_cabinate.jpg)
*reference image*

For the main part I resized a cube.

I then resized a cube for the drawer, I cloned the cube 3 times and positioed them inside the main part. I then used the boolean difference tool to create holes where the drawers would go.

I then deleted the top face of the drawer cube and extruded the remaining faces to give it thickness. For the handle I created a sphere and deleted half of the faces so I had a semi circle, I extruded the remaining faces to give it thickness. I resized the handle and positioed it on the drawer based on the reference image. I created a cube and resized it on the front of the drawer and deleted the front and back faces and extruded the rest.

I cloned the finished drawer 3 times and positioed them in the holes in the main part of the filing cabinet.

![filing cabinet](Appendices/render_screenshots/filing_cabinate.PNG)

For handles I used the chrome material and for the rest of the filing cabinet I used the brushed metal material with a dark green colour

# Scene and Materials

I imported the desk and then imported the other objects and positioned them around it. I then used resized cubes for the walls and floor.
I then put a positional light where that lamp is on the desk and did a test render. The test render was too dark so I decided to add a window and put a positional light behind it, I decided to add blinds to the window so that it wasn't obvious there was nothig beyond it and so that it would create a shadow.
I originally had the filing cabinate facing away from the window but the details on the front weren't visible so I turned it 90 degrees.
I also made sure that the light from the window was more intense that the lamp so it was realistic.
Some of the parts were still dark so I created a surface to reflect the light as if there was a wall there.

I then added the materials to the objects and adjusted the lights.

I turned up camera and diffuse setting to remove the noise.

![finished render](Render/render.png)
