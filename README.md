Command Line Tools
==================

A set of useful command line tools.

spaces2tabs
-----------

Replace every set of consecutive spaces with one tab on every line in every matching file in every sub-directory. An example use is when lines have been indented with spaces and you want them indented with tabs instead.

Use:

    spaces2tabs [directory] [file pattern] [number of spaces]

where:

- `directory` is the directory in which to start searching for files
- `file pattern` is how to match files. Example: *.java
- `number of spaces` is the number of consecutive spaces to replace with a tab

Example:

    spaces2tabs src *.java 4

