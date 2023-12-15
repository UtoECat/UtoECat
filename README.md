## about
Hi, it's me, UtoECat :)    
I love system programming, interpreters and game development.
I'm trying to speak english... but... as you can see... 💀
## languages i use
I'm Very good at C99-C11, OK at C++, insanely good at Lua, very bad at python, can write SQL for sqlite3 with manuals in chrome tab. Could write javascript, but don't really want to.
## libraries/frameworks I use(d) (with small personal review)
- Databases :
  - Sqlite3. I love it so much. Good as database for generic cases, but can be tweaked with pragmas for specific ones.
- Game development:
  - Raylib. Used it very deeply. Good for prototyping and simple games, but the lack of multithreading support makes it difficult to scale in the future...
  - SDL2. Good as SDL, but needs a lot of work to get things started. (so only used it a couple of times on a small scale)
  - Love2D. In simple terms - SDL2, but optionally simple. It's easy to start doing things, potentially scalable, but lacking api for C, C++. Love it.
- Audio :
  - SDL_Mixer. Not the best thing in the universe. 
  - miniaudio - the best thing in the universe for what it does, change my mind.
  - Jack(Jack 2) - good. Good API for clients, good docs, good project.
  - LADSPA - simple to get started, has potencial problems as plugin API(lack of MIDI, etc.)... But... Good.
  - ~~rayaudio. Uses miniaudio, but makes it much worse. Okay for simple background soumd in game, simple effects, but nothing more. Why i'm even included it here?~~
- STB :
  - stb_image. Good.
  - stb_vorbis (was not easy, but thanks god i found miniaudio)
  - stb_XXX - very likely to be good.
- Unit testing and automatic testing
  - Doctest [link](https://github.com/doctest/doctest). Just the best. (I tried using catch at first, and was frustrated by catch's slow compilation speed and bloat.)
  - Github Actions. I'am still don't really understand what i'm doing in it, but... It just works...
- Sanitizers, checksrs
  - Adress sanitizer, Leak suitizer, UB Sanitizer - your best friends in C and C++. Can be ever better to debug your custom allocators :)
- Embeddable interpreters
  - Luajit, Lua 5.1-5.4, Luau. Good. 
- OPENGL
  - Legacy or 1.0, with old and warm in memories but horrible in perfomance glBegin() glEnd()...
  - Fancy 3.0 with horribly picky VAO's, VBO's, EBO's... But there is no any other better way around.
  - Galogen. Github repo archived. Rest in peace, kinda? huh?
  - Other opengl loaders whose names confuse me. Because they are so similar, what the hell?
- Network
  - Enet (new and fancy packed version). Good.
  - Asyncio/http(s) requests. Only using it, not implementing... thank god... 💀
## tools i use(d)
- Debugging
  - x86dbg. Don't ask. 
  - GDB. I can sit and think in it for a while, read help and do simple things, but nothing more. I can't live in debugger without GUI, i'm lost person 💀
- Asan, leak sanitizer, leakcheck, cppcheck, `-fanalyze`... 
- Gnu Make. Not bad.
- CMake. I have bad relationships with it at this moment, but it should be good.... Hopefully...
- Cygwin. Wine.
- c/c++ compilers GCC, CLANG, MINGW.
- VIM. :e review.txt\nihello, this is my vim review\ni love it.ESCyy333p:wq. 
# linux stuff
DE: sway, xfce, Lxde. Terminal : kitty. Distro : Manjaro, Aritx. Hate zsh and swap, love bash and zram. Hate systemd but forced to use it.
