# Maya-Texture-Viewer
MayaTextureViewer creates a new window where you can see the standard 2d Textures (file, grid, ramp, fractal checker, noise...).
It's just a new window with a new panel, a new hidden camera, a new plane visible only in the new window... nothing complicated but since Renderman doesn't let me see standard 2dTexture correctly on a plane in the Material viewer, it could be useful.

It's a WIP, I would like to see the texture in the new panel just when I select one of them... I think I should use a scriptJob, I'm studying that.
Helps and advices are always appreciate, thanks.

# Use
just click on the viewTX (viewerTextures.mel) button to create the new window.

select a 2dTexture in the Hypershade

click on the setTX (assignTexture.mel) button or press the custom hotkey button to view the texture in the new window.

![textureViewerGuide](https://user-images.githubusercontent.com/94127683/149243336-baabc8d4-8d01-4690-b435-513b9bf22b2e.jpg)




# Installation
1 drag/open the script files in the maya script editor

2 select all the code (ctrl+a), drag with MMB to custom shelf (you need to do this 2 times, once for each mel file)

3 rename and edit the new shelf buttons with nice icons

4 Optional/recommended - create a custom hotkey for the assignTexture.mel script
