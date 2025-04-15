# CBT665
Converted to GitHub via [cbt2git](https://github.com/wizardofzos/cbt2git)

This is still a work in progress. 
Due to amazing work by Alison Zhang and Jake Choi repos are no longer deleted.

```
//***FILE 665 is from Jay Moseley and contains a collection of      *   FILE 665
//*           routines written in Assembler to properly format      *   FILE 665
//*           fields that were entered into CICS programs.  Of      *   FILE 665
//*           course these routines can be used for other related   *   FILE 665
//*           types of field fixing.                                *   FILE 665
//*                                                                 *   FILE 665
//*           email:     jay@jaymoseley.com                         *   FILE 665
//*           web site:  www.jaymoseley.com                         *   FILE 665
//*                                                                 *   FILE 665
//*     Input/Output Field Editing Routines                         *   FILE 665
//*                                                                 *   FILE 665
//*         (Assembler)  I first started putting together this      *   FILE 665
//*         collection when I discovered BIF DEDIT didn't do        *   FILE 665
//*         much for fields entered into my CICS programs.  But     *   FILE 665
//*         the collection first became a set, and also became      *   FILE 665
//*         re-entrant, back in 1993 when I had some spare          *   FILE 665
//*         time.  The logic for the numbers to words routine       *   FILE 665
//*         (OFMTMONY) was originally in written in COBOL back      *   FILE 665
//*         in 1976 when another programmer told me I couldn't      *   FILE 665
//*         write the routine in COBOL efficiently enough to        *   FILE 665
//*         run in production.                                      *   FILE 665
//*                                                                 *   FILE 665
//*         I updated the installation procedure on September       *   FILE 665
//*         3, 2003.  So if you have an earlier version, and        *   FILE 665
//*         have checked back here and are worried that the         *   FILE 665
//*         version you got on an earlier date needs updating,      *   FILE 665
//*         relax.  There have been no significant changes to       *   FILE 665
//*         the routines themselves, just an update to the          *   FILE 665
//*         jobstreams that load them onto your system.  And I      *   FILE 665
//*         made a minor change to the Installation                 *   FILE 665
//*         Verification COBOL program's report (the output for     *   FILE 665
//*         IFMTLJST was not printing the field returned from       *   FILE 665
//*         the assembler routine).                                 *   FILE 665
//*                                                                 *   FILE 665
//*         The installation/verification jobstream is in           *   FILE 665
//*         fmt$load.tgz that was originally distributed from       *   FILE 665
//*         my web site.  That jobstream produced most of the       *   FILE 665
//*         members in this pds.  When the installation jobs        *   FILE 665
//*         run, they will create a PDS load library.  Again,       *   FILE 665
//*         on my system it is configured to reside on the same     *   FILE 665
//*         3330 as the source library and is named                 *   FILE 665
//*         JAY01.FORMAT.LOADLIB.  These two datasets are           *   FILE 665
//*         referenced in a number of DD cards in the               *   FILE 665
//*         jobstreams, so it would probably be easiest for you     *   FILE 665
//*         to use a text editor on your host OS                    *   FILE 665
//*         (Linux/Windows/???) or ISPF, and make all the           *   FILE 665
//*         changes in the "reload" jobstream before you submit     *   FILE 665
//*         it to MVS.                                              *   FILE 665
//*                                                                 *   FILE 665
```
