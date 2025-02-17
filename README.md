# In Class Problem Set 3
## Patrick Liszewski and Freya Downey

I used ComboBoxDemo.java a few years ago.  It used to compile cleanly.  Even though the code has not changed, it now  will not compile without throwing warnings.

Doing everything from a command prompt or Git Bash (no IDEs allowed), your mission is to debug the code and find out why it stopped compiling cleanly.  When you have figured it out,  note what you changed and why it stopped working in the README.md file.


**Changes to code**
Moved import statements to first in the file and javadoc now following.
We transformed JComboBox into a generic class using <String>.

**What caused it to stop working?**
Imports not being read first.
JComboBox was not a generic class and thus was using raw datatypes.
