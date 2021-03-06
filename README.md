# QtDropbox

## In short
QtDropbox is an API for the well known cloud storage service [Dropbox](http://www.dropbox.com).

## A bit longer
Basically QtDropbox aims to provide an easy to use posibillity to access the REST API of
Dropbox. All HTTP calls are hidden behind the curtains of neat C++/Qt classes with nice 
method names and specific uses.


## Development
QtDropbox is currently under development and only provides limited features at the moment. If
you have some knowledge about C++ (with Qt framework and/or the Dropbox REST API you are welcome
to contribute to this project. For details take a look at the
[project webpage](http://lycis.github.com/QtDropbox/)

### Current status
Because QtDropbox is far from being ready for a release candidate I will list all already available
and somewhat tested features here:

Currently in progress:
* Fixing various todo and bug tasks

The next features to be implemented are:
* Complete documentation
* Examples

## Features
### General
* Connect to Dropbox
* Access user account information (quotas, user name, share links, ...)
* Parse JSON strings

### File Access
* Access files like a local QFile to read and write data
* Access file and directory metadata
* Access file revisions

Postponed to next version:
* Acessing the directory structure

## Documentation
You can generate a documentation of all classes by:
    
    qmake
    make documentation

This will generate a directory called doxy/ that contains a HTML documentation. Input files
to generate a LaTeX based configuration are supplied as well.

## Further information
There are some files apart this README that may provide some useful information:

* LICENSE
  It's LGPL v3 although that is currently not mentioned in the files
* INSTALL.md
  Installation and usage instructions
* doc/
  Generally everthing inside this directory is information.
* doc/DEVELOPMENT.md
  Development guidelines. Please read if you want to contribute!
