<h1><b>Cayley Numbers</b></h1>

A simple GAP function, based on existing literature, that determines whether a given number n is a Cayley number. The output The output is a list [true/false/fail, MRxxxxxxx]. The first element is true, false, or fail if n is a Cayley number, a non-Cayley number, or a number that is not yet determined to be Cayley or non-Cayley. In case the first element is true or false the second element is the 
Mathematical Review of a paper in which the number n is proved (or cited properly) to be Cyaley or non-Cayley.

<b>Definition</b>. A graph G is vertex-transitive if its grou of automorphisms acts transitively on its vertex sets.<br>

<b>Definition</b>. A number n is called a Cayley number if all vertex-tranitive graphs of order n are Cayley graphs.

## Folders
| Folder                   | Explanation                                                              |
|:-------------------------|:-------------------------------------------------------------------------|
| [Data](Data)             | List of all known Cayley, non-Cayley, and undetermined numbers by 10 ^ 6 |
| [GAPCodes](GAPCodes)     | A GAP function to test whether a given number is a Cayley number         |
| [References](References) | References on Cayley numbers                                             |
