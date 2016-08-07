from: https://gist.github.com/jimbojsb/1630790

Step 0:
-------
Get [Homebrew](http://mxcl.github.com/homebrew/) installed on your mac if you don't already have it

Step 1:
-------
Install highlight. "brew install highlight". (This brings down Lua and Boost as well)

Step 2:
-------
Highlight your source. "highlight -O rtf -K 24 test.java | pbcopy". This will highlight the source code in RTF format and copy the result of that operation to your Mac's clipboard.

Step 3:
-------
Paste into your slide in Keynote. Keynote will create a new text box with your highlighted code. You can adjust the width as needed, and adjust the font size with cmd+ and cmd-
