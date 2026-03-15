# Movement

> Adds 9 fresh progression based movements to Valheim.

## Ability Previews

| Dash | Overdrive |
|------|-----------|
| <img src="https://raw.githubusercontent.com/ThePIXPIX/Videos/main/Dash.webp" width="320"> | <img src="https://raw.githubusercontent.com/ThePIXPIX/Videos/main/OverDrive.webp" width="320"> |

| Double Jump | Wall Kick |
|-------------|------------|
| <img src="https://raw.githubusercontent.com/ThePIXPIX/Videos/main/DoubleJump.webp" width="320"> | <img src="https://raw.githubusercontent.com/ThePIXPIX/Videos/main/WallKick.webp" width="320"> |

| Blink | Landing Roll |
|-------|---------------|
| <img src="https://raw.githubusercontent.com/ThePIXPIX/Videos/main/Blink.webp" width="320"> | <img src="https://raw.githubusercontent.com/ThePIXPIX/Videos/main/Roll.webp" width="320"> |

| Slam | Dash & Slide To Hit |
|-------|---------------|
| <img src="https://raw.githubusercontent.com/ThePIXPIX/Videos/main/slam2.webp" width="320"> | <img src="https://raw.githubusercontent.com/ThePIXPIX/Videos/main/slide%26dash.webp" width="320"> |

| Slide | ShieldSurf |
|-------|---------------|
| <img src="https://raw.githubusercontent.com/ThePIXPIX/Videos/main/slide.webp" width="320"> | <img src="https://raw.githubusercontent.com/ThePIXPIX/Videos/main/surf.webp" width="320"> |

## Core

>- Dash, Overdrive, Double Jump, Wall Kick, Blink, Slam, Slide, SheildSurf, and Landing Roll  
>- Boss-gated progression system  
>- Stamina-balanced ability costs  
>- Designed for fluid and responsive traversal  
>- Multiplayer-safe and dedicated-server compatible  
>- Stable under high-mobility playstyles  

> **Default progression:**  
>- Eikthyr → Dash & Slide
>- The Elder → Overdrive & ShieldSurf
>- Bonemass → Double Jump  
>- Moder → Landing Roll & Slam 
>- Yagluth → Wall Kick
>- The Queen → Blink
>- Fader → Coming Soon

> **How to use:**  
> Abilities unlock through boss progression (configurable).  
> Use hotkeys and movement inputs to activate abilities during traversal or combat.


## Abilities

>- **Dash** | Short horizontal burst movement  
>- **Overdrive** | Temporary movement speed boost  
>- **Double Jump** | Mid-air upward jump  
>- **Wall Kick** | Leap off nearby walls while airborne  
>- **Blink** | Short-range teleport with obstacle awareness  
>- **Landing Roll** | Skill-timed fall damage mitigation with forward momentum  
>- **Slam** | Epic ground slam
>- **Slide** | Short horizontal slide-burst movement
>- **ShieldSurf** | Surf on your shield 

## Controls

>- Dash | `Shift + E`  
>- Blink | `Shift + Q`  
>- Overdrive | `Shift + R`
>- ShieldSurf | `Shift + C`
>- Slide | `Shift + LeftAlt` 
>- Slam | `G` while airborne
>- Double Jump | Press Jump `Space` again mid-air  
>- Wall Kick | `Space` while airborne
>- Landing Roll Arm | `Shift + Space` before hitting ground 

> Controller users can map modifier and ability keys as desired.

## Server Notes

> Movement is primarily client-driven for responsiveness and stability.  
> Cooldowns and roll safety checks use player ZDO tracking where applicable.  
> Designed to avoid desync and physics jitter in multiplayer environments.

## Requirements

> [BepInEx](https://thunderstore.io/c/valheim/p/denikson/BepInExPack_Valheim/)
>
> **Installation:**  
> Ensure you are running the latest version of BepInEx (linked above).  
>
> Put the mod DLL into `BepInEx/Plugins/`, including on dedicated servers if applicable.  
>
> Mod managers will usually handle installation automatically and are recommended.

## Incompatibility

> None known.

## Credits

> 3D Asset:
>["Magic Ring - Red"](https://skfb.ly/6SIoB) by Noob Model :D [Licensed under Creative Commons Attribution](http://creativecommons.org/licenses/by/4.0/).
>
> Sound Effects by:  
>- Neo Theone (Pixabay)  
>- Makoto-AE (Pixabay)  
>- Gabriel Robinson (Pixabay)  
>- freesound_community (Pixabay)  
>- Nicholas Panek (Pixabay)
>- Dvir Silverstone (Pixabay)
>- Alfarran Basalim (Pixabay)
>- OpenMindAudio (Pixabay)
>- Universfield (Pixabay)
>- LiteSaturation (Pixabay)
>- Kammerin Hunt (Pixabay)
>
> ### Technical
> <sub>Go Check Out Their Mods!</sub>
>
> [CookieMilk](https://thunderstore.io/c/valheim/p/CookieMilk/) | The world needs more people like CookieMilk! Thanks for the immense support on this recent update with Slide. From custom animation controllers, to Unity support, and much more. A truly selfless friend!
>
> [Shawesome](https://thunderstore.io/c/valheim/p/Shawesome/) | Got me pointed towards a much better animation for Slam, now the Slams are totally shawesome, really appreciate you!
>
> ### Inspiration
> Parker | Testing help, design inspiration, and an amazing friend, the support is highly appreciated as always!
>
> Mask | Design inspiration and motivation
>
> Agrivar | Controller compatability support
>
> Atlas | Design balance adjustment inspiration
>
> SpiderCVIII | UI cooldown inspiration 
>
> Sav | Design inspiration for landing roll balance adjustments

<details>
<summary><strong>Changelog</strong></summary>

### v0.7.x
- Added Slide
- Added Physics & Custom Animation Controller & FX to Slide
- Added ShieldSurf
- Added Physics & FX to ShieldSurf
- Added 11 ShieldSurf soundtracks to play while Surfing
- Added Custom OGG option for players who want to config custom music for SheildSurf soundtrack
- Sliding into enemy's engages combat
- Surfing past enemy's staggers them
- Remapped Landing roll default to `Shift + Space`
- Incorporated a airborne tracker, 1 click arms, 2 clicks arms, 3 + clicks no longer arms Landing Roll (configurable)
- Balanced Landing roll with a 9s cooldown (configurable)
- Almost every addition is configurable, abilities metrics, FX's, Sounds, etc
- Internal cleaning and optimizations prioritizing Mod performance

### v0.5.x
- Movement now not only get's you out of combat, but initiates combat in new addictively fun ways.
- Fixed Slam visual indicator
- Reworked Blink to use Eitr, fully configurable
- Added Slam ability
- Upgraded Blink, directionally aware and clamps to ground
- Upgraded Dash, dashing into enemies engages combat
- Cleaning prioritizing Mod performance

### v0.3.x
- Balance patch
- Finetuned stamina cost adjustments
- Dash in particular was nerfed to be less exploitable
- Added health gain on successful Landing Roll
- Added optional cooldown UI for Dash, OverDrive, and Blink

### v0.2.x
- Added controller compatibility
- Initial public release  
- Fixed Landing Roll on dedicated servers  
- Owner-only fall damage handling for safety  
- Blink fallback improvements  
- Stability and compatibility improvements  

</details>

## Connect · Feedback · Bugs

[![Discord](https://raw.githubusercontent.com/ThePIXPIX/PIX_Logo/main/discord.png)](https://discord.gg/DvErue4TDM)
&nbsp;&nbsp;&nbsp;
[![GitHub](https://raw.githubusercontent.com/ThePIXPIX/PIX_Logo/main/github.png)](https://github.com/ThePIXPIX)

## More Mods by PIX

[![More Pix Mods](https://raw.githubusercontent.com/ThePIXPIX/PIX_Logo/main/PIX-pfp2.png)](https://thunderstore.io/c/valheim/p/PIXPIX/)

**Thanks for using my mods and sharing the love of Valheim! ❤️**