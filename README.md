## Inverted Search Project

The Inverted Search project is a file indexing system implemented in C language that allows fast searching of words across multiple text files. It stores words and the files they appear in using a hash table data structure, enabling quick lookups similar to how search engines work.


## Features

Reads multiple .txt files from the user.

Builds an inverted index (word → file list).

Displays all files containing a given word.

Supports dynamic insertion of new files.

Provides options to:

-> Create database

-> Display database

-> Search for a word

-> Update database

-> Save database to a file

## Concept Overview

In a normal index, you map files → words.
In an inverted index, you reverse the mapping:
words → list of files where they occur.

| Word  | Files Found In       |
| ----- | -------------------- |
| hello | file1.txt, file2.txt |
| world | file2.txt            |
| C     | file1.txt, file3.txt |
