# FileMD5Utility
A Toxic_Obsidian's CFMD5HF Utility

Useage:
```bash
$ CreateFileMD5HashFile.py -p [target] [options]...
e.g.:
    $ CreateFileMD5HashFile.py -p test.txt -m
    $ CreateFileMD5HashFile.py -p test.txt -nc
    $ CreateFileMD5HashFile.py -p test_folder -rf result.md5
Parameters:
    -p or --PATH            target path, can be a file or a directory
    -m or --MUTE            mute
    -nc or --NOT-CREATE     do not create the md5 file
    -rf or --RESULT-FILE    specify a result file
```
