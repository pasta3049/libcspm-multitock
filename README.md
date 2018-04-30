# libcspm-multitock
Versions of Haskell files that need to be modified to create a modified version of libcspm which uses 5 timing events for Timed CSP processes

This is a university project; the project supervisor is Bill Roscoe, University of Oxford.

This modified version of libcspm uses five different events (_tock_.1, _tock_.2, _tock_.4, _tock_.8 and _tock_.16) on a _tock_ channel to represent these numbers of time units in translated Timed CSP processes, rather than the standard use of a single _tock_ event.

To compile the modified version of libcspm, replace the relevant files from the libcspm repository of the University of Oxford (maintained by Thomas Gibson-Robinson) at https://github.com/tomgr/libcspm with these files and compile with Cabal in the normal way.
