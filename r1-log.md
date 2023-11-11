# #100DaysOfCode Log - Round 1 - Glitchbyte

The log of my #100DaysOfCode challenge. Started on [October 26th, 2023].

## Log

### R1D1 
Setup repos for 100 days. Started a C codebase with context cracking.

### R1D2
Finished context cracking. Started defining basic types. Since Im using the C89 standard, I cant use stdint.h.
I'll have to define my own `int64` and `uint64`. Also may define `isize` and `usize` for the heck of it.

### R1D3
Did a lot of research into defining different types for C. Ended up defining a 64bit type for C89, in case I need it for other architectures. Also added booleans.

### R1D4
Wrote a stack data structure using a singly linked list. Added push, pop, print, and free functions.

### R1D5
Researched double linked lists and their uses. Decided to add it to the lib. Defined the DLL in the header file.

### R1D6
Implemented double linked list in library. Can insert a node at beginning, end, and print backward/forward, as well as free the memory used. Had compile errors, fixed them. Currently getting issues compiling C89 on arm64 architecture.

### R1D7
Wrote a single linked list queue and added it to the library. Queue can add elements to front, rear, print queue, and free queue.

### R1D8
Took a break from writing the gblib, looked into raylib as a possible candidate for game programming. Setup a small repo and geot a window to open. Still having issues compiling on M1 mac; need to sort those out.

### R1D9
Started up an NES emulator repo specifically for NES game development. Going to take a break from C for a bit to focus on getting my website migrated to Astro.

### R1D10
Chill day, mostly read docs on Astro and began migrating content from Hugo. No code written today, but learn a lot about Astro and some frontend dev in general to get familiar with the framework.

### R1D11
Migrated site to Astro. Picked a theme and setup the defaults. Tried getting a pipeline for gitlab pages going, but no dice. It bulds and tests without issue, but deploy doesnt work. I suspect it has something to do with the conflict between how Astro and Gitlab use the "public" dir. Will investigate tomorrow.

### R1D12
Frontend dev is definitely blackmagic. To think you can create SVGs from HTML styling. Took me a minute, but I figured out where the default logo was being originated from, ripped that out, and replaced it with my own. Somehow it looks good. I didnt get to investigate the ci/cd issue further. Spent most of today understanding the codebase and attempting to make my own minor changes before doing bigger ones.
