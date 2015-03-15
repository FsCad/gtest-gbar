# Version 1.2.3 #
  * Tests run automatically when gtest-gbar is run passing the path to the test executable
# Version 1.2.2 #
  * Better handling of settings save & load
  * FIX: application would crash without settings
  * icon transparency

# Version 1.2.1 #
  1. Show/hide console
  1. Failures named by test name, not CPP file name
  1. splitter allows giving test names more space
  1. Clears dialog before next run
  1. Cleaner parsing of test output
  1. More efficient refresh of screen
  1. Tested and fixed Mono version
    1. Fix to problem in combo management which leads to crashes
    1. Work around for Mono/Ubuntu issue of closing stream before fully read - app does not crash but allows re-pressing "Go".

# Version 1.2 #
  * Support for "shuffle"
  * Support for "force disabled tests"
  * Support for test filtering
  * Support for additional command line parameters
  * History of previous runs allowing fast re-run
  * Number of tests based on --list option
  * Select executable dialog not limited to exe
  * Go button requires .exe/.bat on windows only
  * Removed uneeded System.Deployment reference (Was problematic in Mono)

Version should work on Mono, but this was not tested yet.

# Version 1.1 #
First public version