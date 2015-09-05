# esh-toggle

Provides the command eshell-toggle which toggles between the
*eshell* buffer and whatever buffer you are editing.

This is done in an "intelligent" way.  Features are:

 - Starts a eshell if non is existing.

 - Minimum distortion of your window configuration.

 - When done in the eshell-buffer you are returned to the same
   window configuration you had before you toggled to the eshell.

 - If you desire, you automagically get a "cd" command in the
   eshell to the directory where your current buffers file exists;
   just call eshell-toggle-cd instead of eshell-toggle.

 - You can conveniently choose if you want to have the eshell in
   another window or in the whole frame.  Just invoke eshell-toggle
   again to get the eshell in the whole frame.

This file has been tested under Emacs 20.2.

To use, call the functions `eshell-toggle` or `eshell-toggle-cd`.
It's most helpful to bind these to a key.
