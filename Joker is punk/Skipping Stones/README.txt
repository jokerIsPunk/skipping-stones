Thank you for using my Skipping Stones prefab!

WARNINGS:
- Do not spawn the stones on the surface of a collider in your world!
	They automatically respawn when they collide with anything that isn't water, and spawning them on a surface will cause them to respawn every frame. When placing them in Editor, place them at least a few centimeters above the ground. They should hover in the air until picked up.
- You must update the VRChat SDK to the newest version as of the release date of this prefab, which is viewable in the version document.

GETTING STARTED:
- Drag and drop the "Skipping Stones" prefab into your scene hierarchy. Recommend putting it at the root of the scene (moving objects).
- Place, duplicate, and resize the water triggers to match the surface of your water. You may disable the mesh on my object and use the trigger only.
- Place the stones at least a few centimeters above the ground where you want them to spawn.

INSTRUCTIONS:
- The stones will skip on any object with a collider where the GameObject's name contains the string "water" (case insensitive). I've provided a prefab that should work great in all situations, and is safe to overlap with your existing water and triggers.
 - You can freely change or delete the mesh on the water prefab. If you make your own water object, just add "water" to the name and make sure it collides with the Default layer in the physics matrix.
- The prefab "stone" is the base functional unit. Duplicate, drag and drop, or delete these freely.
- If you don't want the idle highlighting effect, you should disable the sprite renderer component of that object. You can also delete that object.
- If you don't want the info text, you should disable that GameObject. You can also delete the GameObject.
- If you want to change the mesh of the stone, you should modify the renderer on the "mesh" gameobject, but be mindful not to break the script's reference to that GameObject.
- If you want to change the particle effects or audio of the skip or sploosh effects, you should similarly only modify those components and be careful not to break the script's reference to those GameObjects.
