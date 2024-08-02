# candyshop
This is another dependency for libLUCID. This repo contains a bunch of tools for Dreamcast development. So far, it's only CDI tools and file encoders. Below are the Source links and a brief description of the tools.<br/>

## cdi4dc
converts ISO files to CDI Roms, isn't used as much because of its replacement, mkdcdisc. Compiles for Windows, provided executable is for Linux, untested for MacOS. <br/>
Source (with license): [CDI4DC by sizious](https://github.com/sizious/img4dc/tree/master)<br/>

## gdisofs
used to extract GDI/CDI to a mounting point/folder. Untested for Windows, Linux executable provided, Untested on MacOS.<br/> Source (with license): [GDISOFS by snickerbockers](https://gitlab.com/snickerbockers/gdisofs/-/tree/master)<br/>

## makeip
Used to make IP.BIN files, can implement logos into the bootstrap. You can make your own IP template called `ip.txt` for custom names, game titles, etc. Works on Windows, provided executable for Linux, and MacOS.<br/>
Source (with license): [MAKEIp by sizious, BBHoodsta](https://github.com/Dreamcast-Projects/makeip?tab=readme-ov-file)<br/>

## mkdcdisc
The All-In-One tool for making CDI Roms. Provides CDDA support, portable and used in the Simulant Engine. Provided executable is Linux, works on MacOS, no Windows support.<br/>
Source (with license): [MKDCDISC by the Simulant Team](https://gitlab.com/simulant/mkdcdisc)<br/>

## pvrtex
Used to encode textures to .pvr, dt, and .tex files, is faster than texconv and has no QT dependency. the provided executable is Linux, and possibly working for Windows and MacOS.<br/>
Source(license in README)[PVRTEX by tapamN](https://dcemulation.org/phpBB/viewtopic.php?p=1060286#p1060286)<br/>

## radx
Encodes WAV audio files to ADX audio files. coded in Rust. Provided excutable is Windows, only tested with Wine on Linux, MacOS with wine will work too.<br/>
Source(with license):[RADX by issac lozano](https://github.com/Isaac-Lozano/radx)<br/>

## scramble
Scrambles a .bin file to 1ST_READ.BIN. used in the cdi4dc-making process. Not needed for mkdcdisc. Anything with a standard GCC toolchain will run it<br/>
Source(pubic domain):[SCRAMBLE by Marcus Comstedt](https://dreamcast.wiki/Scrambling)<br/>


Welp, that's all the tools i included. You can use this for anything to be honest. Other than that. Happy baremetal coding :)<br/>

~LUCiDViUSALS

