srezic-cpan-distroprefs
=======================

A collection of distribution preferences for CPAN.pm

This directory contains a number of files for the
[CPAN.pm distroprefs system](https://metacpan.org/pod/CPAN#Configuration-for-individual-distributions-Distroprefs).

In a nutshell, use these files if you encounter problems when installing or testing CPAN modules — maybe the solution
for the problem is already contained here.

*How to use it*: you can checkout the whole directory into ~/.cpan/prefs or ~/.local/share/.cpan/prefs
(depending on your CPAN.pm distribution). However, it's recommended to pick only the distropref files
you really need, so just copy or symlink these files only. Most files are named after the CPAN
distribution (e.g. X11-Xlib.yml for the CPAN distribution X11-Xlib). While CPAN.pm is building a module,
and a matching distropref file is found, you'll see something like
```
______________________ D i s t r o P r e f s ______________________
                           X11-Xlib.dd[0]                           
```
in the log output.
