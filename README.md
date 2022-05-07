This fork has some changes that i find very useful to improve speed. 
Given that they are broad changes and not bug fixes, this comes as a fork and not commit to main dltdv
Changed its name to DltDv8alberto so that calling this version is explicit.

Alberto B. 2022-05-07

Changes:
- Renamed main gui file to avoid confusion while calling the app.
- Changed keyboard commands to increase user performance and minimize
  use of mouse
- Updated help menu for keyboard commands
- On main file:
  - Reduce verbose text to save space
  - Arranged gui elements to give ample space to zoom window
  - Implemented "silent update" mode which prevents graphics update
    and supresses graphical element creation during automatic tracking
    to significantly improve speed.
  - Allowed multi-track mode to behave more like automatic mode


------------------------------------------------------------------------
This is the development repository for DLTdv and friends. 

See https://biomech.web.unc.edu/dltdv/ for stable versions, sample data and so on.

Current development by Ty Hedrick is focused on DLTdv8 in MATLAB 2019b. DLTdv8 moves to MATLAB's new App framework and
adds Deep Learning based automatic image tracking for 2D and 3D data.


Ty Hedrick, 2020-08-20
