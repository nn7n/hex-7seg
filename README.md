# ATF16V8B-based binary to 7-segment decoder/driver

- .eqn - boolean equations file, contains chip selection, pin assignment and a list of equations.
- .jed - JEDEC file used for programming with TL866 or other compatible device.

Equations are written for using with a common-anode 7-segment indicator.
For using with a common-cathode indicator all output inversions (slash symbols) need to be removed.

Input/output lines can be remapped by changing pin numbers in pin assignment section of .equ file. 
For exact pin numbers refer to ATF16V8B datasheet.

Customized versions are assembled with EQN2JED.EXE from OPALJR21 package using `eqn2jed.exe hex-7seg.eqn`
