# FileMD5Utility
A Toxic_Obsidian's CFMD5HF Utility

Useage:
For CUIs:
```
$ CreateFileMD5HashFile.py -p [target] [options]...
e.g.:
    $ CreateFileMD5HashFile.py -p test.txt -m
    $ CreateFileMD5HashFile.py -p test.txt -nc
    $ CreateFileMD5HashFile.py -p test_folder -rf result.md5
    $ CreateFileMD5HashFile.py -p test_folder -v result.md5
Parameters:
    -p or --PATH            specify a target path, can be a file or a directory
    -v or --VERIFY          specify a .md5 file path, read values and verify files.
    -m or --MUTE            mute
    -nc or --NOT-CREATE     do not create the md5 file, this parameter will be ignored if '-v' is specified.
    -rf or --RESULT-FILE    specify a result file, this parameter will be ignored if '-v' is specified.
```
For GUIs:
Just double click the .py file or executable file, and follow the instruction.
Instructions are written in Simplified Chinese only.
