+++
date = '2026-04-10T15:00:04+01:00'
draft = true
title = 'Unity UI VFXs w/ Render Textures'
ShowReadingTime = true
+++

Hi everyone! Hope you are all doing well.
Amidst one of my classmates's projects, I had to create relatively simple UI VFXs on mouse presses and whatnot.
Curiously this has always been somewhat of a constraint due to Unity's RT architecture, depending on the needs of your project.

I'm going to break down a few quirks that may aid in your own projects, mostly if you're just now getting started with these features!

# Wait... what's a Render Texture?

**Render Textures** are incredibly useful components of the rendering system in Unity.
You can create a new Camera in your scene, and change its *output* mode to send the image it makes into a **Render Texture** asset.
