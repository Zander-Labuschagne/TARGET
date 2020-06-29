# TARGET - Thrustmaster Advanced pRogramming Graphical EdiTor

Thrustmaster T.A.R.G.E.T. for Sublime Text 3 and 4.

## Features:
* Syntax highlighting that is in my opinion an improvement over the proprietary editor, let me know if you don't agree.
* Code completion using snippets that includes hints to help non-programmers their way around the language. Let me know if the hints/completions are a little too much.

*PS: This is my first editor plugin/addon/package*

### Things I'd like to work on:
* Improve syntax highlighting for user defined functions and variables. <-- Might try and copy from C syntax file.
* USB keycode autocompletion? Maybe? What do you think?
* Comments autocompletion e.g.: `MapKey(&Joystick, TG1, SPC); // First Stage Trigger : Engage PAC`
  The above statement's comment needs to autocomplete the button/switch name based on its identifier as `TG1`, followed by shifting the cursor to the description part to the far right as the final autocomplete parameter (which is the easy part).
* Linter to show errors as irritating red squiggly lines, or should I just make the word red if unidentified??
* Investigate the possibility of building/compiling and running from within Sublime Text, also running the event tester from within Sublime Text.