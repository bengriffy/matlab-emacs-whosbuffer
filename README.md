# matlab-emacs-whosbuffer

This program allows a persistent "Whos" buffer when in Matlab-Mode in emacs for viewing variables in the current MATLAB process. When matlab-shell is launched, a "*Matlab Whos*" buffer launches split-vertically from the "*MATLAB*" buffer. Each time a MATLAB command is executed using "C-c C-s", the "*Matlab Whos*" buffer updates once output finishes. At any time, the "*Matlab Whos*" buffer can be updated using M-x matlab-shell-get-whos.

## Getting Started

To install on your local computer, simply download the .el file and place in your packages directory.

