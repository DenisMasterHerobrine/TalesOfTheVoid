*Entities born at the intersection of corrupted matter and forgotten mechanisms. What was once a functional system slowly decayed, leaving behind echoes: autonomous constructs, warped lifeforms, and unstable space that no longer follow the original design.
Void ~~C̶r̶e̶a̶t̶u̶r̶a~~ Creatures are not just monsters - they are remnants of a machine that kept running long after its purpose was lost.*

Implemented Content:
- Custom music, sound effects (thanks to https://freesound.org and https://itch.io)
- Custom mobs
- Custom animations
- Custom dimension
- Custom structures
- Custom biomes
- Custom blocks
- Custom block textures with layered blending
- Custom loot
- Custom items
- Custom decorative elements
- Custom dungeon mechanics

Development Notes:
Hytale is still in an early alpha stage, which introduced a significant number of limitations and unexpected challenges 🥀

Some examples:
- Attack animations are partially hardcoded
(or at least that's how we understood it - figuring it out would have taken a lot of time, so we decided to work around it and adapt the custom mob models to the existing attacks of some mobs that are already in the game)

- Structure generation caused numerous edge cases and instability
Portal logic required multiple experimental implementations before working reliably, several core systems were simply unavailable
(Huge thanks to joshieman for the opportunity to use [Shared Structures](https://www.curseforge.com/hytale/mods/shared-structures)! However, in the final version we decided to drop the library due to other complications, after which we changed our approach overall)

During this 4-day sprint, of course, we couldn't avoid abandoned ideas, assets, animations, and all that - here are a few insights:

- Abandoned assets, animations, models and ideas
<img width="59" height="59" alt="PortalCursebreakerLogo_00000" src="https://github.com/user-attachments/assets/6d8cc6b3-5ee1-4642-a133-62418dd17bef" />
<img width="345" height="629" alt="DefaultArtwork" src="https://github.com/user-attachments/assets/7c5587e3-7d9e-4143-b5a7-2b68cbb601c9" />
<img width="1594" height="916" alt="image" src="https://github.com/user-attachments/assets/b647eba5-410f-45a0-9d6f-caef9aae852b" />

- Early versions of alternative Void Creatures variants
- Unused structures and biome concepts
- Lore fragments

Abandoned elements still reflect the amount of work done behind the scenes and show that the final result is only a part of a much larger exploration process.
