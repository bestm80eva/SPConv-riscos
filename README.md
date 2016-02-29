# !SPConv

Very old source code for my basic port or wrapper GUI app of SPConv, a widely available cross platform ZX Spectrum snapshot converter tool, for RISC OS, way back in 1994.

From what I remember it's a GUI wrapper around the spconv cli application by Henk de Groot

I've extracted the old source from an ARC file to a hostfs format so the files have extensions with commas to indicate the RISC OS filetype. Source C and H files are in directories 'c' and 'h' with no extension, as they'd occur under RISC OS.

I'm unsure how to build it at present or what software is required, other than a RISC OS system. This would have been built on an A5000. I'm not sure what compiler.

Memory is very hazy of this and mostly I just knocked up a simple UI to wrap around the spconv application.

I've merged the final distributed ARC contents with the source as it seems the source is missed some distributable elements like the !Run, !Boot and other such files. The source should build !RunImage in theory.
