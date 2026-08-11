https://youtube.com/playlist?list=PLdK5Dsuv__Uc&si=IHlVTmNFxQ0dnD4U

# HP15C-style-HTML-Calculator-Milan-Greenman
This is an HP15C style calculator.  Its about 97% complete.  All of the functions work mostly as the real HP15C calculator.
The calculator has not been tested or verified and I am not responsible for any incorrect results provided by the calculator.

To Do List:
- Verify and/or implement matrix operations in programming mode.
- Last line of last program should auto rtn if there aren't any more program lines after.

Subtle Differences:
- ENTER key is recorded as 46(Emulator) instead of 36(HP15C)
- There is no RAND(random) seed.
- There is no f DIM i.  I am not using the memory registers for SOLVE, INTEGRATE, MATRIX.  They are simply storage registers for values.  SOLVE & INTEGRATE do consume program lines.  MATRIX uses computer memory.
- I did not put a limitation on matrix dimension size.  Its limited by computer resources.
- There are 999 usable lines of program code.  000-999.  Yea, that's 1,000 but line 000- does not accept program bytes.
