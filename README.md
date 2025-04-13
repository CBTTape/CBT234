# CBT234
Converted to GitHub via [cbt2git](https://github.com/wizardofzos/cbt2git)

This is still a work in progress. GitHub repos will be deleted and created during this period...

```
//***FILE 234 is from Dick Thornton, who is the author of the       *   FILE 234
//*           DISASSEMBLER program on File 217.  This is a rewrite  *   FILE 234
//*           of the disassembler to be able to handle load modules *   FILE 234
//*           which are in PDSE's as well as those in PDS'es, and   *   FILE 234
//*           it has been updated to use IBM's IEWBIND and IEWBUFF  *   FILE 234
//*           macros to do the load module access.                  *   FILE 234
//*                                                                 *   FILE 234
//*      Fixed by Joe Reichman to allow disassembly by              *   FILE 234
//*      entry point names, and also to fix a "bug",                *   FILE 234
//*      in disassembling "Halfword Immediate" instructions         *   FILE 234
//*      of the form xHI with negative number operands.             *   FILE 234
//*                                                                 *   FILE 234
//*      The disassembler will now also include ENTRY (entry        *   FILE 234
//*      point) assembler instructions in the disassembled code.    *   FILE 234
//*                                                                 *   FILE 234
//*         emails:  (check to see which are relevant):             *   FILE 234
//*                   sbgolob@cbttape.org                           *   FILE 234
//*                   reichmanjoe@gmail.com                         *   FILE 234
//*                                                                 *   FILE 234
//*      The following statements are from Dick Thornton:           *   FILE 234
//*                                                                 *   FILE 234
//*      This is a new disassembler that can be used to             *   FILE 234
//*      disassemble load modules in PDSE's as well as those in     *   FILE 234
//*      traditional PDS's.  It also can disassemble the more       *   FILE 234
//*      recent instructions that have been added to the IBM        *   FILE 234
//*      mainframe instruction set since my earlier disassembler    *   FILE 234
//*      that was written in 1977 and is now in File 217 of the     *   FILE 234
//*      CBT tape.                                                  *   FILE 234
//*                                                                 *   FILE 234
//*      I did not include DSECT statements in this version         *   FILE 234
//*      partly because I have not found them very useful, and      *   FILE 234
//*      partly due to time pressure, as I plan to retire June      *   FILE 234
//*      30, 2002.                                                  *   FILE 234
//*                                                                 *   FILE 234
//*      Installation and use notes:                                *   FILE 234
//*      1. This PDS contains the source code and JCL needed to     *   FILE 234
//*         install and test the RESOURCE/REBUILD/READLMOD          *   FILE 234
//*         disassembler.                                           *   FILE 234
//*      2. Details of coding for the control statements are        *   FILE 234
//*         given in comment statements at the beginning of the     *   FILE 234
//*         RESOURCE program.                                       *   FILE 234
//*      3. All the rest of the installation instructions may be    *   FILE 234
//*         found in the $README member of this pds.                *   FILE 234
//*                                                                 *   FILE 234
//*   Small fix to the RESOURCE program from John Kalinich, to fix  *   FILE 234
//*   the translate table of printables.                            *   FILE 234
//*                                                                 *   FILE 234
//*         email:  jkalinic@outlook.com                            *   FILE 234
//*                                                                 *   FILE 234
```
