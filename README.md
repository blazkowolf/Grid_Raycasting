# Grid_Raycasting
This is my attempt at a pseudo-3D world using the once popular graphics technique, raycasting.
#### About the project:
- For me, this project was a proof of concept. I am a huge fan of games such as Wolfenstein 3D and Blake Stone, and I have always found the raycasting graphics in these games fascinating, so I wanted to try it for myself.

- Being that I only wanted to see these graphics come to fruition, rather than create a full-fledged game engine, I chose to use Ken Silverman's Evaldraw program (a fast and simple route to prototyping graphics algorithms).

- Unfortunately, this iteration does not allow for texture mapping. I went for a simpler implementation and made all the walls solid colors.

#### About raycasting:
- As mentioned above, raycasting is a pseudo 3D graphics technique, commonly used in the nineties.

- Simply put, raycasting is when you create a 2D map, using a 2D array, from a top-down perspective, and you approximate a 3D image by giving the aforementioned map depth, and draw it to the screen from a first-person perspective.

- However, this is where raycasting differs from programmer to programmer. There are many notable implementations of raycasting that can allow for more diverse and realistic environments when implemented with Sectors, as opposed to a 2D array.
