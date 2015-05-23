This small project is basically born because I had a huge quantity of DTS files made for Torque 1.5 that I wanted to import in another game engine but didn't want to reexport from Maya. I search on the Net, found no free tool to export my DTS into any other usable format. Being quite familiar with the inner workings of FBX, I made that DTS to FBX converter.

# What it support #
  * Mesh
  * Texture (embeds them inside the FBX)
  * Skeleton
  * Skeleton-based animation. There is no support for vertex or UV based animation.

## What it doesn't support ##
  * Scale. If you try to specify on any DTS object a scale different of "1 1 1", you will get hazardous results.
  * Collision. Currently, any node or mesh having a name starting with "Col" is completely discarded.