# XRay(ish) Minecraft Texture Pack
A simple texture pack that reshapes blocks into a scaffolding shape allowing the player to "see through" the blocks. Works in Survival Bedrock with acheivements!

## The Good, The Bad, and The Ugly
### Pros
* See through solid blocks! 
* pure texture pack; no special code!
* no mods
* expandable; add wanted blocks to the block.json file
* Change blocks to any "old-style" shapes *(See https://wiki.bedrock.dev/blocks/block-shapes.html for a full list)*
* "Scaffolding" shape allows player to see an outline of the full block. 

### Cons
* Rendering is resource heavy; May need to lessen video settings for better frame rate.
* Need to manually list block types in the blocks.json; currently only stone and dirt
* "Scaffolding" shape is limited to looking through (x&z axis); The top of the shape is solid, so looking up or down is blocked.

## Other Stuff
### Notes
* The scaffolding shape allows the player to see through the block, while still seeing the outline of the block. The shape can be changed 
to another that would be less resource intense, or totally "invisible". But changing this may be difficult to see the block outlines. 

### Future Ideas
* Create UI menu to choose block types
* Create UI menu to choose shape (other than scaffolding)
* Add a function for on-the-fly block-type change (ie. press "o", and the block in the crosshairs will change)
* Add "transparent" center on texture pack maybe will allow "Y" axis see through. 
