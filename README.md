# Project04-Platformer

## Implementation
- Multiple levels - 1 pt(?)
  - This one might not count - I made a second "level," as in a second set of obstacles for the player to get through connected to the first, but it takes place in the same scene. You can only transfer between levels through door objects that teleport the player, so they are fully separate, but this might not count.
- Different sprites - 1 pt
  - I used sprites from OpenGameArt for everything new that I added! The enemy sprites are still Kenney ones, though. I made a few sprites myself, including some of the background, the key sprites, and the 1-up effect that plays when you regain a life.
- Pretty okay menus - 1pt(?)
  - My menus aren't particularly robust, but each one takes place somewhere IN the level (in a different scene), two of them have moving components, and the winning and dying screens display stats such as how many more keys you needed to finish or how many lives you lost in total.
- Life system - 1pt
  - By taking damage from enemies, spikes, or falling out of the level, the player will lose one of their three lives. They gain a life (if they're under the maximum of 3) with every tenth coin they collect. Losing a life makes the player invincible for a short period (signified by their sprite flickering) and plays a hurt animation on their sprite. Lives are reflected by sprites in the top-of-screen HUD, and a small 1-up icon appears when the player gains a life.
- Door and key system - 1pt
  - The player can pick up different-colored keys throughout the level. The quantity and colors of collected keys are shown in the top UI. When the player is close to the corresponding door (doors match the color of their keys, with the exception of a white door that needs every key to open) and have the correct keys, the door's sprite will change to be "open." If they gets far from the door, it will close again until they return. On contact with an open door, the player will change position (switching between levels) or scene (going to the win menu), depending on the door.
  - I'm listing this separately from the 2-point category "Terrain with which to interact" because I added OTHER terrain that the player interacts with more directly, and the door and key system is more complex. Spikes damage the player and teleport them back to the last non-hazardous point they were at when touching the ground, coins work as usual and raise score, and birds are animated moving platforms that repeatedly move horizontally between two points.
- Juicy features - 1pt
  - In case one of these other features don't count, I'm listing this, too.
  - The player makes particles when they jump, enemies explode into particles when they are defeated, gaining a life makes a "1-up" image appear before slowly rising and fading away, invincibility is indicated by a flickering sprite, the player has a separate animation for taking damage, charging enemies do a small hop when they see the player (I also used this to "hide" one of them behind a bush so you wouldn't see them until they saw you), scores display with "00" at the end to feel more impactful, and doors open to indicate when they can be used.
- Late project - -1pt


## References

Character Controller adapted from Sebastion Lague's Unity 5 Character Controller Tutorials
https://www.youtube.com/playlist?list=PLFt_AvWsXl0f0hqURlhyIoAabKPgRsqjz
https://github.com/SebLague/2DPlatformer-Tutorial

Pixel Platformer tiles provided by Kenney.nl
https://kenney.nl/assets/pixel-platformer

Pixelify Sans from Google Open Fonts
Copyright 2021 The Pixelify Sans Project Authors (https://github.com/eifetx/Pixelify-Sans) 

Simple NES-like Platformer Tiles provided by surt
https://opengameart.org/content/simple-nes-like-platformer-tiles

Arcade Platformer Assets and Platformer Baddis provided by GrafxKid
https://opengameart.org/content/arcade-platformer-assets
https://opengameart.org/content/platformer-baddies

Background, key, and 1-up sprites created in Piskel
https://www.piskelapp.com/


## Future Development

## Created by
Graham Baker
