Requirements
===================
 - [theos](https://github.com/theos/theos)
 - readline (use this build https://github.com/sterling0x1/libreadline-arm)

Before building
-------------

Clone/download readline and copy paste content from libs and include to theos/libs and theos/include

Make & Install
-------------

    $ cd rxmemscan
    $ make package or make package install


Usage
-------------
	$ rxmemscan <pid>
    
| Command | Short | Args          | Desc                                                        |
|---------|-------|---------------|-------------------------------------------------------------|
| list    | l     | [pageNo]      | List search results.                                        |
| search  | s     | [searchVal]   | First search & Search again with [searchVal].               |
| fuzy    | f     | [compareType] | First fuzzy search & Fuzzy search again with [compareType]. |
| reset   | r     | -             | Reset the search state.                                     |
| retype  | -     | -             | Re-select the search value type.                            |
| exit    | -     | -             | Exit the program.                                           |


Screenshots
-------------
![alt tag](https://raw.githubusercontent.com/rainyx/rxmemscan/master/screenshots/screenshot1.jpg)


----------


![alt tag](https://raw.githubusercontent.com/rainyx/rxmemscan/master/screenshots/screenshot2.jpg)

