This is a Windows form user interface program (aka small graphical app)
which can be used to sign-in delegates and alternates at the LD (Legislative District)
Caucus to be help on April 17th 2016.

This program should work on any Windows computer and should not require any special
already installed software.  Please let me know if it doesn't.

To use it, simply start the .EXE.
Then, do File > Open and select the .csv data file.

The functionality is to basically enter a search criteria and press Find.
This will search all records which match the criteria and display them.
Finally, pick the row of the person in front of you (aka you are a sign-in
clerk at the LD Caucus), double-click the row and check their information.
When you are satisfied that things are OK, press the 'Check-in' button.

Once someone has checked-in, their row will go from light red (aka pink) to
light green.

You can also re-double-click the row (aka any row which became green) and
un-do what you just did: e.g. you mistakenly checked-in the wrong person.
The row will go back to light red and the row will return to light red.

All actions are log into the event log: file LDSignin_eventLog.log

Each of the people who check-in are printed into a separate CSV type log - known
as the LDSignin_changeLog.csv file


