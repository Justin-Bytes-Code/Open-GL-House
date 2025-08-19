# Open-GL-House
This was a medium-to-high level assignment completed in C++ to recreate an entire house in OpenGL, featuring accurate texturing and custom lighting. It also includes a camera with custom Controls! 

---
**Preview Images**

![Preview Image](https://github.com/user-attachments/assets/6874f9ec-53fe-4dcc-bc22-c73fe60a6e13)

![Preview Image 2](https://github.com/user-attachments/assets/dadb2076-00ad-4b4d-afdf-082efef3d335)

---
**It Includes:**

- 3D Objects
- Moveable Camera
- Lighting
- Shading
- Textures
- Phong Shading
- Error Handling
- Perspective & Orthographic Viewing Settings
- Control Options

---
**Rubric Of Project 1 (Document Submission)**

After reviewing the Final Project Guidelines and Rubric, you should understand the goals you will work toward in this course. For your final project, you will show your cumulative knowledge and skills in graphics and visualization by creating a 3D scene that is based on a 2D image of your choice. There are many steps to creating a 3D scene. You will explore these steps throughout this course. 

Next week, you will select a 2D image to use as a base to develop your 3D scene later in this course. This week, you will look at example images and start thinking about the kinds of scenes you might choose to create. You will also practice breaking down the objects in these images into the shapes in the diagram below.

A CGI of a box, cone, cylinder, tapered cylinder, prism, pyramid, sphere, torus, and plane.

Start by looking at the following example image of items on a kitchen counter. This image and the instructions below will give you an idea of the types of thinking needed in this course.

Kitchen items on a counter. There are three brown eggs on the left with a small bowl behind them. The bowl is slightly flared at the top, with a narrow bottom and a blue geometric pattern around the outside. The bowl is filled with flour, which has also spilled onto the counter. Just to the right of the bowl is a cube of butter sitting on two pieces of wax paper. The wax paper is stacked one piece on top of the other, but the pieces are off-set at an angle from one another. Farthest to the right is a wooden spoon angled toward the bowl.

From this 2D scene, you might choose to construct each egg from an elongated sphere. You could use a box to create the butter. Or you could use a plane for both the paper and the table. The bowl is more complicated. You could use a cylinder to create the bottom of the bowl, a half-sphere for the middle, and a torus for the lip. The spoon is a good example of a complex object that requires more than one shape to represent it. In this case, you could use an elongated box for the handle and a flattened half-sphere for the head of the spoon.

Directions
Select one of the images below to practice breaking down the objects into basic shapes that you could replicate in 3D. There are many ways to determine which shapes to represent the 3D objects. Your selections should result in a scene that would make sense for the image.

Items on a desk. At the upper left and upper right edges, some greenery is displayed. A white keyboard and mouse are set at the very top of the picture. On the left is a coffee cup on a saucer. A pine cone lays on its side just below the cup. Farther to the right is a pair of thick, black, plastic-rimmed glasses. Two long, sharpened, black pencils are just below the glasses. One has its eraser facing up while the other has its eraser facing down. In the center of the page, two notebooks are piled on top of each other at slight angles. The top notebook has a spiral binding at the top and is flipped open to a blank page. To the right of these notebooks, a simple black pen is resting on the desk with its cap removed but placed next to it.

Topiary garden. A gravel path leads into the center of the garden and is flanked on both sides by conical bushes. Five bushes are lined up on the left. The same number of bushes is presumably lined up on the right, but the row of them is blocked by the first bush due to the angle of the image. These conical bushes are connected by shorter, rectangular hedges. Between the two rows of hedges, a low, circular hedge is placed in the center. This hedge wraps around a tall, conical hedge with a spiral cut into it, moving from the base all the way to the tip. In the far background, more trees and the sky are present.

A house with attached garage (to the left) and small porch (at center), both of which are composed of brick at the base and white clapboards above. The house is offset from the road, with a driveway leading to the single-door garage and a horizontal sidewalk cutting across the grass in front. The house is two stories tall, with chimneys at both the left and the right peaks of the gray-tiled roof. The front of the house has two windows on the upper floor and a set of three connected windows on the lower floor. A small tree is situated in the front yard and more trees are present in the background behind the house.

Items on a desk. At center is a large, gray, widescreen monitor with a blank white screen. A matching keyboard and mouse sit just in front of it. To the right, a simple square pencil cup holds six sharpened black pencils, all of which have their points facing upward. To the left, a stack of five thin, monochrome notebooks are stacked on top of each other. The thickest notebook is at the bottom with the smallest on top. Just beside this pile, closer to the monitor at center, is a simple black mug with a small, looped handle and a tapered base that angles upward to a wider rim.

Specifically, you must address the following rubric criteria:

Explain which 3D shapes could be used to replicate the selected 2D image. Identify three to five major objects from the image to translate into basic shapes. Explain how you would use as many different shapes as possible to create those objects. As you work, remember to reference the following shapes:
Box
Cone
Cylinder
Plane
Prism
Pyramid
Sphere
Tapered cylinder
Torus
Identify at least one object that would need multiple shapes to replicate. Consider the spoon in the example involving kitchen items and how two shapes, a sphere and a box, were used to construct the object. When you look at the image you are working with, where do you need to use this strategy to make a more accurate replication?
Discuss areas where the image could be simplified in a 3D replication. For example, what objects would you remove? Are there objects you would combine using a single shape?
What to Submit
Submit your completed analysis as a 100- to 200-word Microsoft Word document using New Times Roman, 12-point font, and one-inch margins. Any references should be noted in APA format.

---
**Rubric of Project 2 (Code Submission)**

Overview
This course has a final project. There are five milestones that will build on one another and that you will submit in Modules Two through Six. You will submit the final project in Module Seven.

Generate accurate representations of three-dimensional objects using application programming interface libraries and computer graphics development best practices
Create interactive graphics applications that respond to input devices
Develop a fully formed three-dimensional project that meets project requirements
Scenario
You work as a C++ and OpenGL 3D graphics developer for Triangle and Cube Studios. This company designs 3D worlds for clients and customizes them based on the varied needs presented by each particular client.

In this professional landscape, the demand for computational graphics and visualizations is continually growing. Your clients may come from the game industry looking for graphics and animations, the healthcare industry for medical visualizations, the entertainment industry for computer-generated imagery (CGI) and visual effects, business industries for 3D printing to create physical objects for applied real-world problem solving, and much more. When you are assigned one of these types of projects, you become responsible for writing code in OpenGL to create objects, apply texture, apply light, render, and control virtual environments relative to a virtual camera.

Your current project with Triangle and Cube Studios is to replicate a 3D version of a 2D image that you have been given by a client. Your client will later be 3D printing this to use as a preliminary concept for their business, so they only need you to create a simple approximation using a few basic shapes.

Directions
Using the image you selected in Milestone One, you will create 3D objects that represent the components and layout of that image. Although you have already begun to complete some of this work in your other milestones, during this stage of your final project, you will be refining and adding to your earlier submissions before bringing everything together. Note: You will be working on your 3D scene in Visual Studio but will also submit a written design decisions document discussing your approach throughout the process.

Specifically, you must address the following rubric criteria:

3D Objects

Create low-polygon 3D representations of real-world objects. Make sure you have at least four completed objects in your 3D scene. At least one of the objects you create should be made using two or more primitive shapes. Note that the object you completed in an earlier milestone can count as one of your four. Use organized geometry and make sure that the polygons (triangles) on each 3D model are well spaced and connected. Minimize complexity and save 3D modeling time by setting the polygon count for your objects under 1,000 triangles. Remember to think in terms of simple shapes and ask yourself what basic 3D shapes go into making up each object in your scene. Four of the following basic shapes must appear at least once in your creation:
Box
Cone
Cylinder
Plane
Prism
Pyramid
Sphere
Tapered cylinder
Torus
Apply accurately projected textures to a 3D model. You must select at least two objects to texture. Note that you should have already textured one object in a previous milestone. If you use that object here, it will count as one of your two. The textures you select should be royalty-free images with resolutions of 1024 by 1024 pixels or higher. Please refer to the Sourcing Textures Tutorial linked in the Supporting Materials section for help finding images that you can use for textures.
Apply lighting to create a polished visualization of 3D models. You must include a minimum of two light sources, and at least one of them should be colored. Note that the light you worked on in a previous milestone counts as one of your two lights. The light sources you create will need to capture all of the objects in the 3D world you are building. They should be positioned at locations that do not cause parts of the objects to appear dark when moving the camera around them. Include a point light for one of your two lights. You may use a directional light or spotlight. Make sure that you design lights in a way that helps create a final polished presentation. Use all components of the Phong shading model, including the following components:
Ambient
Diffuse
Specular
Place objects appropriately, using the X, Y, and Z coordinates, relative to one another in the 3D world. Match the photograph you selected as closely as possible by placing the objects in their proper locations. Note: The objects may overlap because all of the objects were likely initially placed at 0, 0, 0.
Navigation

Apply horizontal, vertical, and depth camera navigation around the 3D scene. The camera will be traversing the X, Y, and Z axes. Make sure it captures all of the objects in your 3D scene. Use the code you created in an earlier milestone and then increase the radius of the camera’s orbit so it will project light on all of the objects. Add each object separately and then adjust the orbit radius or position of the camera each time. Use the following input devices:
WASD keys should be used to control the forward, backward, left, and right motion.
QE keys should be used to control the upward and downward movement.
Apply nuanced camera controls to effectively view the 3D objects in the application. Changing the camera controls should allow the orientation of the camera to change even though its location has not moved. Focus first on pitch and yaw, but careful changes can be made to roll. Code for adjustments in the speed of the movement. This way, a user will have more control over how they explore the objects in the scene. Use the following input devices:
Mouse cursor should be used to change the orientation of the camera so it can look up and down or right and left.
Mouse scroll should be used to adjust the speed of the movement or the speed at which camera travels around the scene.
Create perspective and orthographic displays of the 3D world. Use the tap of a keyboard key to allow a user to change the viewport display of all objects in the scene between orthographic (2D) and perspective (3D) views. Switch the function call to retrieve either the perspective or orthographic projection matrix. Keep the camera in the same orientation.
Best Practices

Apply coding best practices in formatting, commenting, and functional logic. Complete the following items:
Employ formatting best practices by providing program code that is easy to read and follows industry standard code formatting practices, such as indentation and spacing.
Employ commenting best practices to ensure project source code is briefly and clearly explained using descriptive comments.
Employ functional coding logic best practices to ensure the program runs as expected. You do not have to include Note that not everything should be written in a single function. Your work should be well modularized.
Reflection

Justify development choices for your 3D scene. Think about why you chose your selected objects. Also consider how you were able to program for the required functionality.
Explain how a user can navigate your 3D scene. Explain how you set up to control the virtual camera for your 3D scene using different input devices.
Explain the custom functions in your program that you are using to make your code more modular and organized. Ask yourself, what does the function you developed do and how is it reusable?
Milestones
Milestone One: Project Proposal
In Module Two, you will submit your completed proposal that describes the 2D image you have selected to replicate and explains the basic shapes you will use to replicate the object in 3D. This milestone will be graded with the Milestone One Rubric.

Milestone Two: Beginning a 3D Scene
In Module Three, you will transform two of the basic shapes you selected in Milestone One. This milestone will be graded with the Milestone Two Rubric.

Milestone Three: Interactivity in a 3D Scene
In Module Four, you will incorporate input devices and camera movement into the 3D scene you created in Milestone Two. This milestone will be graded with the Milestone Three Rubric.

Milestone Four: Texturing Objects in a 3D Scene
In Module Five, you will apply texture to the 3D scene you previously created. This milestone will be graded with the Milestone Four Rubric.

Milestone Five: Lighting Complex Objects
In Module Six, you will apply lighting to the 3D scene you previously created. This milestone will be graded with the Milestone Five Rubric.

Final Project: Submission
In Module Seven, you will submit your completed 3D scene and a document explaining your design decisions. Your project should bring together and refine the elements of your other milestones. Your submission should reflect the incorporation of feedback gained throughout the course. This submission will be graded with the Final Project Rubric.

What to Submit
To complete this project, you must submit the following items:

3D Scene
Submit a completed ZIP folder with all of your code. Your ZIP folder will include one or multiple CPP files and the Visual Studio project files. Also, the ZIP folder must include an EXE file so that the assignment can still be verified if the submitted source code does not build successfully. Check for the EXE as a quick reference on your code’s functionality before you submit it. Review the Visual Studio Export Tutorial linked in the Supporting Materials section below for instructions on how to download the necessary ZIP folder.

Design Decisions
Your written explanation should be submitted as a 2-page Microsoft Word document with 12-point Times New Roman font, double spacing, and one-inch margins. Any sources should be cited according to APA style.

---
**Questions**

(You don't have to read this. This is only for a homework assignment with this repository) 

How do I approach designing software?

- First I try to verify what they want. While It may seem like time waste understanding exactly what a client wants will always benfit everyone in the long run as it stops reduduency or unnessary features from being added which will lengthen development. After verifying wtih the client I will then break it down into modular components allow it to be easier to work with before I begin coding. For this project I did that with the camera, Textures, and lighting

What new design skills has your work on the project helped you to craft?

- This project really showed how important modular code is as well as good documentation/commenting. Unlike most projects I have been given from school this assignment actually gave you almost a month to create it. You are suppose to use 1 week to implement a full feature into the code which caused me to finish on the first few days then be forced to stop then come back next week to keep implementing. This really showed me how much I needed to document my code so I can easily being work after a couple of days without seeing the project. While it took longer initally the new design skills this project taught me really helped me with coming back to my code when I left for days at a time from the project. 

What design process did you follow for your project work?

- I used a milestone approach. I focused on adding 1 feature to total completition before working on another one. 

How could tactics from your design approach be applied in future work?

- Planning modular code early helps any project scale better almost instantly as well as be more simple to work with. Breaking down complex systems into small milestones makes managing projects a lot more managable especially when by yourself. 

How do I approach developing programs?

- Implementing a strong core is the first stepping stone in any major project. I try to aim for a good proof of concept before doing anything complex as it slows down time needed extreamly. 

What new development strategies did you use while working on your 3D scene?

- A new development stratgey I used in this scene was the object placement. I would use objeccts that had a tip like the code to figure out which side of the plane is the "front". This allowed me to easily debug my code in the future and know where to rotate the shape. 

How did iteration factor into your development?

- Each iteration allowed me to catch any bugs almost instantly. Anytime a bug would show up before I did the next interation I would instantly see it like a sore thumb. One I remember vividly was the textures not showing up on the windows causing it too be invisable. I was able to use standard trouble shooting techinques to fix the bug before it was even submited for grading. 

How has your approach to developing code evolved throughout the milestones, which led you to the project’s completion?

- My approached to code was deeped though this milestone as it helped me learn the importance of planning ahead with good documentation even if it takes longer initially. This allowed me to keep working on the project to compleition a lot quicker as well as being a lot less work to get started after taking a break. 

How can computer science help me in reaching my goals?

- Computer Science gives me the skills and theory behind making games and simulations from scatch. While I already understood how to use popular engines, understanding OpenGL gives me a much deeper understanding in how each engine functions on a root level. 

How do computational graphics and visualizations give you new knowledge and skills that can be applied in your future educational pathway?

- Computational graphics and visualization gave me a deeper understanding in spatial reasoning. 

How do computational graphics and visualizations give you new knowledge and skills that can be applied in your future professional pathway?

- In the future my main goal is to become a game programmer or a designer. Computational graphics and visualizations was able to help me achieve that goal with giving me a deeper understanding of a core part of all games which is the graphics. While most game enginges are switching to vulkan, OpenGL is still a fundmental building block in how to make visuals on a computer using math. 

