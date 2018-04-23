Raycaster Contains
=========

Checks if an object is in the current Three js raycaster.
This assumes Three.js Raycaster is already initialized and set up inside render loop, and given mesh has a name (i.e. mesh.name = "cookiemonster").

## Usage

  `raycontains(rayItems, meshName)`


  raycontains(Raycaster Intersects [Array], Mesh Name [String])

  where rayItems is the intersected objects, and meshName is the mesh object's name.

  `rayItems = raycaster.intersectObjects( scene.children );`

  `mesh.name = "cookiemonster"`

  Returns true if raycaster intersects with the give mesh object.
