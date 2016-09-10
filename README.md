pyqt4topyqt5
============

pyqt4 -> pyqt5

Convert a source code written for PySide into a valid code for PySide2

Command line args:
	Path of a file or a directory. The file may be a source code python or a text file wich contains the names of the files to be converted separated by a new line.
	
	"--nosubdir", Don't process into sub-directories.
	"--followlinks", Visit directories pointed to by symlinks.
	"-o", The name of the generated file or directory if path is a directory.
	"--diff", Write a diff file. If there's more than one file converted, all the diff are written into one file. If no name is provided, the diff file will be named with the name of the source.
	"--diffs", Write a diff file for each file converted. The diff files will be created in the same destination dir as the converted files.
	"--nolog", Do not create a log file.
	"--nopyside2", "Only perform updates that are compatable with PySide.



For simple Maya-based PySide to PySide2,
import module and run:

topyside2.Main(infile, o=outfile)