- Databases :
  - Sqlite3. 
    I love it so much. Good as one-file database for generic cases, but can be tweaked with pragmas for specific ones.
- User Interface:
  - Dear ImGui. Immediate mode. Easy to use, somewhat easy to embed in existing project, does not depend on specific rendering api.
    Has only two downsides :
    - Assertions on misuse.
    - C++. Although no c++ features like inheritance/stdlibc++/templates are used, may still make it less portable.
- Game development/Cross platfrom frameworks:
  - SDL2. Good as crossplatform library to make things work, but needs a lot of work to get things started.
  - Raylib. Used it very deeply. Good for prototyping and simple games, but the lack of multithreading support makes it difficult to scale in the future...
  - Love2D. You can think of it as SDL2, but simpler, and on Lua. (LuaJIT)
    It's easy to start doing things, potentially scalable, but lacks api for C, C++. Love it.
  - Godot. Good engine, but it's an engine. GDScript is inda questionable, not tried using C++ yet. A lot of things are required to learn to use it properly and somewhat efficiently.
- Audio :
  - SDL_Mixer. Not the best thing in the universe. 
  - miniaudio - the best thing in the universe for what it does.
  - Jack(Jack 2) - good. Good API for clients, good docs, good project.
  - LADSPA - simple to get started, has potencial problems as plugin API(lack of MIDI, etc.)... But... Good.
- STB :
  - stb_image. Good.
  - stb_vorbis (was not easy, but thanks god i found miniaudio)
  - stb_XXX - very likely to be good.
- Unit testing and automatic testing
  - Doctest [link](https://github.com/doctest/doctest). Just the best. (I tried using catch at first, and was frustrated by catch's slow compilation speed and bloat.)
- Sanitizers, checkers
  - Adress sanitizer, Leak suitizer, UB Sanitizer - your best friends in C and C++. Can be ever better to debug your custom allocators :)
  - I forgot name of one tool i used many years ago for checking c/c++ code on UB and bad behaviour.
- Intetpreted languages
  - Lua 5.1-5.4. Good. Embeddable. Simple. Extandable. 
  - LuaJIT. Same as Lua 5.1, but with FFI, Dynamic libraries loading, JIT compilation. Very Good.
  - Luau. Lua 5.1, but safe out of the box to run code from remote. Bytecode is **NOT** safe, compiler is **NOT** safe, but i guess it somehow works eventually.
    - I don't like minimal documentation of changed things from Lua. In terms of C API. 
    - Not compatable with anything in Lua world, many libs need tweaks in order to work.
    - No dynamic loading of extensions ('cause no stable ABI).
    - May still be useful, has many optimisations that are not present in vanilla Lua. You may like my Luau source packer to embed it easier in your project if it really looks better than vanilla lua for you. 
- Graphics
  - SDL redering api. It's strange, but has support for software rendering and portable. Useful for someone, who works with devices with no hardware acceleration for 2D graphics.
  - Legacy or 1.0. Old. Warm in memories but somewhat horrible in perfomance.
  - Fancy 3.0 with horribly picky VAO's, VBO's, EBO's... But there is no any other better way around.
  - Galogen. Github repo archived. Rest in peace, kinda? huh?
  - Other opengl loaders whose names confuse me. Because they are so similar, what the hell? 
    - I guess they has some usefulness, but i don't find them appealing.
- Network
  - Enet (new and fancy packed version). Good.
- Security/SSL/Cryptography
  - MbedTLS. Seems like they don't provide full safety against timing attacks. 
  - BearSSL. Good, used in microcontrollers like ESP32, but can be used on x86/arm with no problems (except perfomace? i'm not sure). Has less documentation, but don't uses any mamory allocations by routines in the library, and that's good.
