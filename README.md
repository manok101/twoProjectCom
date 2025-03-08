# twoProjectCom
Function level comparison between two projects
The main purpose of this project is to compare two C language and assembly language projects. The comparison rule is to remove blank lines and comment lines from the file, analyze changes, and reuse them. The change of statistical rules is to compare functions. If any information that makes up the function changes, it is considered a "change", otherwise it is a "reuse". For non function statements, count changes or reuse by line. Compared to the benchmark project, the added files and deleted files are stored in the output path of the execution path according to the unit of "change" function. When parsing the function, this project calls the open source project srcML for analysis.

This project is written using Python scripts.

This project was written by Manok.
