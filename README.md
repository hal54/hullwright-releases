<p align="center">
<img src="docs/icon.png" width="112" alt="Hullwright icon">
</p>
<h1 align="center">Hullwright</h1>
<p align="center">
<strong>Procedural sci-fi texture generator for Windows</strong><br>
Seamless PBR maps from 1K to 8K, 16-bit, ready for Octane, Redshift, Arnold, Cycles, V-Ray, Unreal and Unity.
</p>
<p align="center">
<a href="https://YOUR-GUMROAD-LINK"><strong>Buy on Gumroad</strong></a> ·
<a href="https://github.com/YOUR-GITHUB-USERNAME/hullwright-releases/releases/latest">Download the free trial</a> ·
<a href="#support">Support</a>
</p>
Hullwright builds hull plating, armor, circuitry, building facades and vehicle panels from code. Pick a look, change the seed, adjust the settings, and export a full set of maps that tiles on both axes. Every panel, greeble, label and light is generated: there are no stock photos or scanned textures inside, so every seed gives you something new.
This repository hosts the Windows installer and the update files the app downloads. The source code is not public.
Download and install
Download Hullwright-Setup-<version>.exe from the latest release. If you bought a license, the same installer is linked from your Gumroad download page.
Run it. If Windows SmartScreen says "Windows protected your PC", click More info → Run anyway. The installer is not code-signed yet, so Windows shows this the first time.
Accept the license agreement. A short tour follows; replay it any time from About → Quick Tour.
Free trial and activation
Hullwright runs as a 7-day trial from first launch. Everything works, exports go up to 2K, and texture packs are disabled. After the trial, previews keep working but exporting needs a license.
To activate:
Buy Hullwright on Gumroad. Your license key is on the receipt and your download page.
In Hullwright, choose File → License…, paste the key and click Activate.
Activation checks the key with Gumroad once, so it needs the internet. After that Hullwright works offline. Each key activates up to 3 computers. The badge in the top bar shows your status.
What it makes
Six layout engines
Engine
What it makes
Panel Split
Recursive hull plating with chamfers, notches, insets and nested plates. Mirror symmetry makes vehicle and ship panels.
Modular Grid
Framed, corridor-style modules.
Cell Armor
Hex, diamond or irregular plating with optional glowing seams.
Conduit
Circuit traces, pads and chips with optional illumination.
Micro Overlay
Fine surface detail with an opacity map for layering over other materials.
Facade Lights
Emissive building facades: office interiors, window panes, office floors, ceiling tubes, perspective slivers, night scatter, LED matrix and outline glow.
28 starting looks in three groups: Hard surface, Building lights and Cyberpunk.
Detail on top: 12 greeble types, LED strips and screens, neon trim, labels and hazard stripes, alien graffiti, edge wear, scratches and grime.
Building light packs
Emissive maps for city shots and background buildings, in one hue or mixed, with an optional baked glow. Use the Emissive light pack target and plug the map into an emission shader.
Cyberpunk and vehicles
Neon signs in alien script, neon trim, alien graffiti, and mirrored panel layouts for vehicles.
Preview in 3D
Check the maps on a plane, sphere, cube or cylinder with displacement, or tile the texture 2×2 in 2D to check the seams.
Export
Presets
Octane, Redshift, Arnold, Blender Cycles, V-Ray / Corona, Unreal Engine (packed ORM), Unity HDRP (mask map), Emissive light pack, Everything
Maps
Base color, roughness, metallic, normal, height, AO, emissive, ORM, mask map, glossiness, curvature, panel ID
Resolution
1K, 2K, 4K, 8K
Bit depth
8- or 16-bit PNG; height as 32-bit float EXR
Normal maps
OpenGL or DirectX
Texture packs
Up to 32 seed variations, one folder each
Every set includes a MaterialX file that wires up the maps, a look.json that reopens the exact settings, and a README.txt with the displacement mid-level and settings for your renderer.
What's new in 1.1
Building light packs: the new Facade Lights engine and the Emissive light pack export target.
Cyberpunk looks: neon signs, neon trim and alien graffiti.
Vehicle panels: mirror symmetry for Panel Split.
28 starting looks in three groups.
MaterialX export with every set.
Undo and redo for every settings change.
Menus, themes and layouts: File, Edit, View and About menus; Dark, Light or Match System; Studio or Stacked layout.
Automatic updates and a first-run tour.
Free trial and license keys through Gumroad.
Requirements
Windows 10 or 11, 64-bit
A graphics card with WebGL support for the 3D preview
About 0.4 GB of free memory for 4K exports and 1.5 GB for 8K (the export panel shows the estimate)
An internet connection once, to activate
Updates
Hullwright checks this repository for a new version at launch and downloads it in the background. You choose when to restart and install. About → Check for Updates… checks right away. Hullwright sends no telemetry.
Support
In the app: About → How to Use Hullwright (F1) and About → Keyboard Shortcuts.
Email: YOUR-SUPPORT-EMAIL
Moving to a new computer and out of activations? Email your license key and I'll free one up.
Please use email rather than GitHub issues for license questions, so your key stays private.
License
Hullwright is commercial software, licensed under the End User License Agreement shown at install (About → License Agreement in the app). In short: textures you make with a licensed copy can go in any personal or commercial project, but cannot be resold or redistributed as textures or texture packs.
 2026 Carlo Diego. All rights reserved. Hullwright is a Dilated Perspective pro
