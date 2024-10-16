**Development Tools**

### Debugging
- **x86dbg**: A solid choice for Windows debugging.
- **GDB**: Initially, I found the command-line interface challenging, but I've come to appreciate its power and reliability. While GUI debuggers can be helpful for visualizations, I recommend giving GDB's CLI a dedicated try for a week; and you will practically never need GUI debuggers again.

### Static Analysis and Sanitizers
- **AddressSanitizer (Asan)** and **LeakSanitizer**, **Cppcheck**, and **-fanalyze**: They are essential for any C/C++ developer. 
  *I do wish that undefined behavior was detected more effectively by default though.*
### Build Systems
- **GNU Make**: A straightforward option that works well for many projects.
- **CMake**: While it aims to simplify cross-platform builds, I’ve had a complicated relationship with it. My experience in various companies has shown me that overly complex build processes can be a burden. I now lean towards minimalistic solutions, such as simple bash or Python scripts, or even Makefiles. CMake can sometimes be overwhelming.

### Development Environment
- **Cygwin**: An excellent tool for achieving a consistent experience between Windows and Linux, with minimal performance overhead compared to WSL. Binaries built with Cygwin are highly portable, when compiled with `-static` `-static-libgcc`.
- **Wine**: well enough solution for running Windows applications on Linux. Older apps supported better though.

### Compilers
- **GCC**, **Clang**, and **MinGW**: good and widespread compilers. 
- **Tiny C**: just for fun :) compiling C code and running it directly inside an application is interesting too.

### Text Editors/IDEs
- **Vim**: My preferred text editor.
- **Neovim**: It has potential, but I find it slower with commonly used plugin packs. As an IDE, it falls short due to community-maintained plugins/pluginpacks that often have bugs. While Iit can be configured for your specific needs, less plugins and performance, that requires a significant time investment.
- **VSCode**: it's okay.
- **Pycharm**: it's better suited specifically for python than "Ms extension for python" in vscode.
