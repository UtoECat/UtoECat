## about
Hi, it's me, UtoECat :)    
I love system programming, interpreters and game development.
I'm trying to speak english... but... as you can see... 💀
## languages i work with
I'm Very good at C99-C11, OK at C++, insanely good at Lua, very bad at python, can write SQL for sqlite3 with manuals in chrome tab. Could write javascript, but don't really want to.
## libraries/frameworks I work(ed) with (with small personal review)
- Databases :
  - Sqlite3, love it so much. Good as database for generic cases, but can be tweaked with pragmas for specific cases.
- Game development:
  - Raylib. Used it very deeply. Good for prototyping and simple games, but the lack of multithreading support makes it difficult to scale in the future...
  - SDL2. Good as SDL, but needs a lot of work to get things started. (so only used it a couple of times on a small scale)
  - Love2D. In simple terms - SDL2, but optionally simple. It's easy to start doing things, potentially scalable, but lacking api for C, C++. Love it.
- Audio :
  - SDL_Mixer, but it's not the best thing in the universe. 
  - miniaudio - the best thing in the universe for what it does, change my mind.
  - Jack(Jack 2) - good. Good API for clients, good docs, good project.
  - LADSPA - simple to get started, has potencial problems as plugin API(lack of MIDI, etc.)... But... Good.
  - ~~rayaudio. Uses miniaudio, but makes it much worse. Okay for simple background soumd in game, simple effects, but nothing more. Why i'm even included it here?~~
- STB :
  - stb_image. Good.
  - stb_vorbis (was not easy, but thanks god i found miniaudio)
  - stb_XXX - very likely to be good.
- Unit testing and automatic testing
  - Doctest [link](https://github.com/doctest/doctest). Just the best. (I tried using catch at first, and was frustrated by catch's slow compilation speed and overload.)
  - Github Actions. I'am still don't really understand what i'm doing in it, but... It just works...
- Sanitizers, checksrs
  - Adress sanitizer, Leak suitizer, UB Sanitizer - your best friends in C and C++.
