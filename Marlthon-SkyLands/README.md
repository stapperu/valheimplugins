<p align="center"><img src="https://i.ibb.co/DHrysB2S/Banner-Skylands.jpg"></p>
<a href="https://dathost.net/r/marlthon/valheim-server-hosting" target="_blank"><img src="https://i.ibb.co/gQvx05M/dathostlogothunder.png" align="right" alt="Marlthon"></a>

<img src="https://img.shields.io/badge/SkyLands-8A2BE2"> ![Version Badge](https://img.shields.io/badge/Version-0.0.5-6aa84f.svg) <img src="https://img.shields.io/badge/Created by: Marlthon-1d629f">
## SkyLands Description
Tired of the same old lands? With **SkyLands**, gravity is just a suggestion! This innovative mod allows you to elevate your Valheim</br>
experience, giving you the power to **create and customize your very own floating island in the sky**.</br>
Prepare for a vertical adventure like never before. **SkyLands** isn't just a mod; it's an invitation to redefine your Valheim journey. What will you build in the skies?</br>

<details>
<summary><b>YOUR ISLAND, YOUR RULES:</b> (<i>click to expand</i>)</summary>
</br>
Unleash your creativity and build the fortress of your dreams on your own slice of the sky. Each island is a blank canvas, awaiting your vision.</br>
</br>
• <b>Total Control:</b> Build your island from scratch and enjoy the peace of mind knowing that only you can deconstruct it, ensuring the safety of your floating base.</br>
</br>
• <b>The Heart of the Island:</b> To manifest your celestial haven, you will need the mystical Floating Crystal – an essential resource to anchor your home in the skies.</br>
</br>
• <b>Limitless Customization:</b> Go beyond the structure! Customize your island's terrain with various textures to give it the look you desire. Add ornaments and decorations to create a truly unique and inviting space.</br>
</br>
• <b>Life on High:</b> Raise and manage your animals on your suspended island. A boar farm in the clouds? A herd of lox grazing among the mists? The sky's the limit for your ambitions!</br>
</br>
• <b>Limitless Building:</b> All your favorite structures and buildings from Valheim can be erected on your island. Create houses, forges, portals, and whatever else your imagination can conjure.</br>
</br>
• <b>Attention, Vikings:</b> While you can create a complete ecosystem in the sky, <b>farming is not supported</b> on your floating islands. The secrets of fertile soil still belong to the mainland, for now...</br>
</br>
</details>

<details>
<summary><b>PREFAB LIST</b> (<i>click to expand</i>)</summary>
</br>

| Prefab Name | In-Game Name | Description | Crafting Recipe |
| :--- | :--- | :--- | :--- |
| `SL_Isle01` | Skylands 01 | Floating Isle (radius 25m) | `FloatingCrystal` x1, `SurtlingCore` x10, `Stone` x250 |
| `SL_Isle02` | Skylands 02 | Floating Isle (radius 48m) | `FloatingCrystal` x1, `SurtlingCore` x10, `Stone` x350 |
| `SL_Isle03` | Skylands 03 | Floating Isle (radius 58m) | `FloatingCrystal` x1, `SurtlingCore` x10, `Stone` x400 |
| `SL_Isle04` | Skylands 04 | Floating Isle (radius 64m) | `FloatingCrystal` x1, `SurtlingCore` x10, `Stone` x500 |
| `SL_Isle05` | Skylands 05 | Floating Island (radius 80m) | `FloatingCrystal` x1, `SurtlingCore` x10, `Stone` x600 |
| `SL_Isle06` | Skylands 06 | Floating Archipelago (radius 75m) | `FloatingCrystal` x1, `SurtlingCore` x10, `Stone` x500, `Wood` x150 |
| `FloatingCrystal` | Floating Crystal | Crystal used to create floating islands | `Drops from vanilla bosses. 5% drop chance.` |

</details>

<details>
<summary><b>HOW TO REACH YOUR ISLAND?</b> (<i>click to expand</i>)</summary>
</br>
The <b>SkyLands</b> mod focuses on the <b>creation</b> and <b>customization</b> of floating islands, but it <b>does not include</b> a method of transportation to reach them. To travel to the skies and access your new base, you will need an aerial transport mod.</br>
For a thematic and fully compatible experience, the official recommendation is <a href="https://marlthon.com/loja.php"><b>AirShipPlus!</b></a> This mod adds fantastic airships that perfectly match the theme of SkyLands, allowing you to explore the skies and dock at your island in style.</br>

</details>

<details>
<summary><b>HOW TO DISABLE THE FLOATING CRYSTAL DROP</b> (<i>click to expand</i>)</summary>
</br>

You can customize which creatures drop the Floating Crystal and the chance of this happening directly in the `marlthon.Skylands.cfg` configuration file.</BR>
</BR>
If you don't want the Floating Crystal to drop from any creatures, follow these steps:</BR>

1.  Open the `.cfg` file in your `BepInEx/config` folder.</BR>
2.  Find the section for the item you wish to change (e.g., `[Floating Crystal]`).</BR>
3.  Locate the line that starts with `Drops from =`.</BR>
4.  **Important:** Delete all the text after the equals sign (`=`), leaving the value completely empty.</BR>

**Example:**</BR>

```ini
## Floating Crystal drops from this creature.
# Setting type: String
# Default value: Eikthyr:0.05:1:,gd_king:0.05:1:,Bonemass:0.05:1:,Dragon:0.05:1:,SeekerQueen:0.05:1:,Fader:0.05:1:
Drops from = 
```
</details>

<details>
<summary><b>MANUAL INSTALL</b> (<i>click to expand</i>)</summary>
</br>
• Mod is required on Server for Config Sync (this is still in development).</br>
• Download the latest copy of Bepinex per author's instructions.</br>
• Place the SkyLands.dll inside of the "Bepinex\plugins\" folder.</br>
</details>

---

### ❤️ Support the Development

By supporting me on **Patreon**, you help ensure continued support, regular updates, and the creation of new mods.  
Your support is completely optional, but **greatly appreciated**.

<p align="left">
  <a href="https://patreon.com/u76220721?utm_medium=unknown&utm_source=join_link&utm_campaign=creatorshare_creator&utm_content=copyLink">
    <img src="https://i.ibb.co/zTyg5d6d/Patreon-Button.png" />
  </a>
  &nbsp;&nbsp;
  <a href="https://www.paypal.com/donate/?hosted_button_id=NU6HKJ8ZD9NU8">
    <img src="https://i.ibb.co/84bSC13P/Paypal-Button.png" />
  </a>
  &nbsp;&nbsp;
  <a href="https://discord.gg/B9TFJBnvzk">
    <img src="https://i.ibb.co/pjwkZ35P/Discord-Button.png" />
  </a>
  &nbsp;&nbsp;
  <a href="https://marlthon.com/">
    <img src="https://i.ibb.co/6R6Crj4d/Marlthon-Button.png" />
  </a>
</p>

---

### SkyLands Photo Gallery

<details>
<summary><b>Skylands 01</b> (<i>click to expand</i>)</summary>
<br/>
<p align="center"><img src="https://i.ibb.co/Sw7mzV9z/Skylands-1.jpg"></p>
</details>

<details>
<summary><b>Skylands 02</b> (<i>click to expand</i>)</summary>
<br/>
<p align="center"><img src="https://i.ibb.co/4RJ2DZgq/Skylands-2.jpg"></p>
</details>

<details>
<summary><b>Skylands 03</b> (<i>click to expand</i>)</summary>
<br/>
<p align="center"><img src="https://i.ibb.co/spzJhLh9/Skylands-3.jpg"></p>
</details>

<details>
<summary><b>Skylands 04</b> (<i>click to expand</i>)</summary>
<br/>
<p align="center"><img src="https://i.ibb.co/yB7tTP9k/Skylands-4.jpg"></p>
</details>

<details>
<summary><b>Skylands 05</b> (<i>click to expand</i>)</summary>
<br/>
<p align="center"><img src="https://i.ibb.co/8LqC9L19/Skylands-5.jpg"></p>
</details>

<details>
<summary><b>Skylands 06</b> (<i>click to expand</i>)</summary>
<br/>
<p align="center"><img src="https://i.ibb.co/JwDVZxXb/Skylands-6.jpg"></p>
</details>

<details>
<summary><b>Skylands 07</b> (<i>click to expand</i>)</summary>
<br/>
<p align="center"><img src="https://i.ibb.co/zWh4XrgN/Skylands-7.jpg"></p>
</details>

<p align="center"><a href="https://marlthon.com/custom.php"><img src="https://i.ibb.co/YTJ91SF/Banner-Custom-Mods.png" /></a></p>
