# Subtle Bug in Tcl Procedure: Incorrect String Comparison

This repository demonstrates a subtle bug in a simple Tcl procedure that involves string comparison.  The procedure `badproc` uses the `==` operator, which performs numeric comparison, instead of the `eq` operator, which performs string comparison.  This leads to incorrect results when comparing strings.

The `bug.tcl` file contains the buggy procedure, and `bugSolution.tcl` provides a corrected version.  The README explains the issue and how to reproduce it.