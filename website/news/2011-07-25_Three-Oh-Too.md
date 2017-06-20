And finally, SLADE v3.0.2 is released. The final version doesn't really have any new features over beta 3, but here's an overview of the major changes since 3.0.1:

- Many improvements to the texture editor:
  - Extended ZDoom TEXTURES support
  - Textures can be copied and pasted, including between different archives, patches and all
  - Added shortcut keys and context menu for the texture list
  - Added 'Texture' menu when a texture editor is open
- New 'Graphic' menu for gfx entries, with some basic gfx editing functions such as flip/mirror, rotate, colourise and colour translation
- Typing the first few characters of an item to jump to it in lists has been re-implemented
- Added the ability to open entries in separate tabs
- Dumped Audiere as the sound/midi library in windows, and swapped to SFML-audio. Upsides are much better/faster audio support and audio support in linux (and mac). Downsides are no mp3 or module format support (though I'll look into adding these back at a later date)
- Fluidsynth is now used to preview MIDI in both windows and linux
- Palettes can now be exported in various formats: raw, png image, csv and jasc palette
- Many other bugfixes and small improvements

With that out of the way, I now plan to focus on the map editor/3.1 for the most part, although I imagine there will be at least a version 3.0.3 before it is finished as there are still quite a few things I want to add to the general editor. Another thing that needs to be looked at is some proper documentation of editor features, but this is one of those things I'm not so good at, I wouldn't know where to start :P I may put up a few basic tutorials at some point, though, detailing how to perform some common editing activities such as importing, texture editing, etc etc. I imagine there are quite a few minor features many people don't know about :P