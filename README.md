# Unix-Commands

1.**ls**

**ls** --- lists your files.

**ls -l** --- lists your files in 'long format', which contains lots of useful information, e.g. the exact size of the file, who owns the file and who has the right to    look at it, and when it was last modified.

**ls -a** --- lists all files, including the ones whose filenames begin in a dot, which you do not always want to see. 

2.**mv filename1 filename2 ** --- moves a file (i.e. gives it a different name, or moves it into a different directory (see below).

3.**cp filename1 filename2** --- copies a file.

4.**rm filename** --- removes a file. It is wise to use the option rm -i, which will ask you for confirmation before actually deleting anything.
You can make this your default by making an alias in your .cshrc file.

5.**diff filename1 filename2** --- compares files, and shows where they differ.

6**wc filename ** --- tells you how many lines, words, and characters there are in a file.

7.**chmod options filename** --- lets you change the read, write, and execute permissions on your files. 
The default is that only you can look at them and change them, but you may sometimes want to change these permissions.

