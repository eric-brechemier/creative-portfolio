# B4J: Binary for Java

## Jul 2004 – Feb 2005

### Project Description

Context: Video games need data files which include the definition of game levels, where objects are found, which events get triggered in which location. Because a new game is generally different from the last, the game studio needs to develop a different level editor for each game. In this custom editor, it is convenient to produce data files in XML format. They store information as a hierarchy which is easily interpreted by computer software, and they can be read in a text editor which is convenient for human developers. The hierarchy of XML files can be described in a formal grammar called XML Schema. This allows to validate the files produced by the custom level editors.

Problem: XML files are very verbose. Their structure is explicit but very redundant. And the data within, for example numbers, tend to take more space in this text format, compared with the same data in a binary format. Mobile phones had very limited resources at the time: little storage and weak computing power and the bandwidth of mobile data connections was also very limited. In order to reduce the duration of the game downloads and the time required to parse each level, the game data had to be sent in a binary format instead. And because each game uses a different binary format, new code had to be written to decode these binary files on the mobile phone for each game. Writing this code was error-prone and somewhat complex.

Question: Can we have the best of both worlds, the convenience of XML files and the small size of a binary format?

Answer: based on an original idea by Fabien Delpiano, head of the game studio, I developed a process to:

* define a custom schema for the game data files, using XML Schema
* compress XML files into small binary files, removing all the hierarchy of information
* generate source code to read the binary files, decoding data and restoring its hierarchy

This process has been used in several generations of video games of the studio.

### Other Creator

* [Fabien Delpiano](https://www.linkedin.com/in/fabiendelpiano/)

### See Project

* [B4J: Binary for Java See project](https://github.com/eric-brechemier/b4j)
