#Power Set
<br />
Return an array that contains the power set of a given string. The power set is a set of all the possible subsets, including the empty set.
<br />
Make sure your code does the following:
<br />
All characters in a subset should be sorted alphabetically, and the array of subsets should be sorted alphabetically.
<br />
Sets of the same characters are considered duplicates regardless of order and count only once, e.g. ‘ab’ and ‘ba’ are the same.
<br />
Duplicate characters in strings should be ignored; for example, ‘obama’ should be evaluated as if it only contained one ‘a’. See the result below.
<br />
Examples
<br />
Input   Output
<br />
string:
<br />
"a" [ "", "a" ]
<br />
string:
<br />
"ab"    [ "", "a", "ab", "b" ]
<br />
string:
<br />
"horse" [ "", "e", "eh", "eho", "ehor", "ehors", "ehos", "ehr", "ehrs", "ehs", "eo", "eor", "eors", "eos", "er", "ers", "es", "h", "ho", "hor", "hors", "hos", "hr", "hrs", "hs", "o", "or", "ors", "os", "r", "rs", "s" ]