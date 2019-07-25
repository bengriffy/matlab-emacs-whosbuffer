# matlab-emacs-whosbuffer
#### This program allows a persistent Whos buffer when in Matlab-Mode in emacs.
#### When matlab-shell is launched, a "*Matlab Whos*" buffer launches split-vertically from the "*MATLAB*" buffer.
#### Whenever a program is executed and runs using "C-c C-s" in an m-file, the Whos buffer updates to give information on the variables local to Matlab.
#### At any time, the Whos buffer can be updated using M-x matlab-shell-get-whos
