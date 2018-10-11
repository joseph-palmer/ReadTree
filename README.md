# ReadTree

## Creates a readme using the Tree function in bash. This code requires you do some things before you can run it.

1) Make sure you have Tree installed (type Tree into terminal to check, if not do sudo apt install Tree)
2) Copy the file ReadTree to your local bin which should be in your path. This is to make sure it is executable from anywhere.
3) The code is only to be used where you have the directory structure used in the CMEE course. i.e. Week1/[Code, Data, Results, etc]
4) Navigate to the directory containing these directories. e.g. Week1. Then in the terminal type 'ReadTree'. This will create a file called README.md in the current working directory containg the tree as well as some into stuff you should fill in.
5) The code files (at least python and bash ones) will show the docstrings providing you have recorded them in the original file. For bash, you must have a line that says 'Description: (Desc: will also work)' for it to extract the files description. Python requires you have made a docstring for the script.
6) The code here uses your .gitignore file in the main directory (CMEECourseWork) to decide what to represent in tree. All pychache folders are also excluded, as is the results directory as the code contained should results.

Have a look at the example README file bellow I created for my week1. If you have any ideas to improve this feel free to contribute.

---

__Example README.md__

# README Document for CMEECourseWork Week1
## Author: Joseph Palmer - _joseph.palmer18@imperial.ac.uk_
## Date: _Oct - 2018_

### Description
This directory contains all the files for Week1 of the CMEE course at Imperial College.
This weeks focus was on scripting in bash.

### Tree map
```


.
├── Code
│   ├── boilerplate.sh : simple boilerplate for shell scripts '
│   ├── CompileLatex.sh : Compiles .tex document to pdf and cleans up files '
│   ├── ConcatonateTwoFiles.sh : Concatonates two files '
│   ├── CountLines.sh : Counts the number of lines in a file '
│   ├── csvtospace.sh : Converts commas in a csv file to spaces '
│   ├── FirstBiblio.bib
│   ├── FirstExample.tex
│   ├── MyExampleScript.sh : a further example of variables for the current user '
│   ├── tabtocsv.sh : converts tabs in given file to commas '
│   ├── tiff2png.sh : Convert tiff to png. '
│   ├── UnixPrac1.txt
│   └── variables.sh : Shows the use of variables '
├── Data
│   ├── fasta
│   │   ├── 407228326.fasta
│   │   ├── 407228412.fasta
│   │   └── E.coli.fasta
│   ├── spawannxs.txt
│   └── Temperatures
│       ├── 1800.csv
│       ├── 1801.csv
│       ├── 1802.csv
│       └── 1803.csv
├── README
├── README.md
└── Sandbox
    ├── ConcatFile.txt
    ├── ListRootDir.txt
    ├── spaceseperatedtest.txt
    ├── TestFind
    │   ├── Dir1
    │   │   ├── Dir11
    │   │   │   └── Dir111
    │   │   │       └── File111.txt
    │   │   ├── File1.csv
    │   │   ├── File1.tex
    │   │   └── File1.txt
    │   ├── Dir2
    │   │   ├── File2.csv
    │   │   ├── File2.tex
    │   │   └── File2.txt
    │   └── Dir3
    │       └── File3.txt
    ├── test.txt
    ├── test.txt.csv
    └── TestWild
        ├── anotherfile.csv
        ├── anotherfile.txt
        ├── file1.csv
        ├── File1.txt
        ├── file2.csv
        ├── File2.txt
        ├── file3.csv
        ├── file3.txt
        └── file4.txt

12 directories, 44 files

```
