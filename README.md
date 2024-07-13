It is project intended to show that Defold is sensitive for quality of model.
In folder "Photogrammetry" you can find 2 ".glb" models. They look very similar.
One of them works in HTML5, other one doesn't.
The reason: normals setting and shading settings before exporting from Blender.
However more low quality model can cause an error.
Automatic retopology, photogrammetry and similar tools cause high risk of low quality mesh,
like as the edge connected to 3 faces.
Defold doesn't support low quality mesh.

https://github.com/defold/defold/issues/9183



# Welcome to Defold

This project was created from the "basic 3D" project template.

The settings in ["game.project"](defold://open?path=/game.project) are mostly set to the default values. The render script is a modified version of the default render script with the addition that models are rendered in a separate pass before 2D components such as sprites and tilemaps. The physics type is set to 3D and not 2D.

The project contains a bootstrap ["main.collection"](defold://open?path=/main/main.collection) that includes a game object with a camera component and a game object with three different models.

Check out [the documentation pages](https://defold.com/learn) for examples, tutorials, manuals and API docs.

If you run into trouble, help is available in [our forum](https://forum.defold.com).

Happy Defolding!

## Credits

* Textures by Kenney (https://www.kenney.nl)
