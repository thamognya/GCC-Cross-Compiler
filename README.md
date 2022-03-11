<hr>

### GCC cross compiler tools

This repo contains elf (i386 to i686 and sparc) and riscv tools used to make own kernels as used by <a href="https://wiki.osdev.org/Main_Page">osdev.org</a> usually. Install script template written by <a href="https://github.com/lordmilko/i686-elf-tools">lordmilko (repo: i686-elf-tools)</a> for elf i686 but edited to add support for c, c++, (original) and go (the new addition) and also i386, i486, i586, and sparc. Also new install scripts written for riscv tools. 

<hr>

### Run the script

#### i386 to i686 elf tools

To run the script you can do

`chmod +x gcc-cross-compiler____.sh`

Choose the script instead of putting in `gcc-cross-compiler___`.

then

`./gcc-cross-compiler.sh____ linux`

where it will install in your home directory (unless you did it as root)


#### riscv tools

`chmod +x gcc-cross-compiler-riscv-____.sh`

and then 

`./gcc-cross-compiler-riscv-____.sh`

where it will install in your home directory (unless you did it as root)

<hr>

### Other distros

The script currently only works in debian based distros. But not to worry, I have made a pre-compiled binaries for linux so check the Releases page and then `unzip` the zip file in `/usr/local/` directory. Only for linux.

I have confirmed that the binaries work in Gentoo, Arch, Debian, but you can make an issue or PR to tell me that it works in other distros.

<hr>

### More information

### For elf tools

Read the readme of <a href="https://github.com/lordmilko/i686-elf-tools" target="_blank">lordmilko's repo i686-elf-tools</a> for more information. My repo is based mostly on his repo. Also checkout <a href="https://wiki.osdev.org/Main_Page" target="_blank">osdev.org wiki</a> to see how to make kernels which inspired this project overall.

#### For riscv

This is a just a simple installation script that installs the package from the <a href="https://mirrors.edge.kernel.org/pub/tools/crosstool/files/bin/x86_64/"> kernel.org website</a>. I choose v10.1.0 since that was what was given in the <a href="https://wiki.osdev.org/RISC-V_Bare_Bones">osdev.org RISC-V barebones</a> but I will be making scripts for more.

<hr>

### Why?

I made this for osdev.org making kernels and hope that this will make it easier for beginners to start.

<hr>

### Todo

- [ ] Make an install script for binaries
- [ ] Make binaries for more versions of the gcc and binutils (1 extra version before feb 8)
- [ ] docker file

if anyone can help please do make an pr

<hr>

If you found it useful, then you could consider liking the repo and you can always change your mind. 

<hr>

Thamognya Kodi <br>
<a href="https://www.thamognya.com" target="_blank">www.thamognya.com</a><br>

<hr>
