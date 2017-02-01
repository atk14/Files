Files
=====

[![Build Status](https://travis-ci.org/atk14/Files.svg?branch=master)](https://travis-ci.org/atk14/Files)

A PHP class for basic file manipulation.

Basic usage
-----------

Files is just a bunch of static functions.

    $content = Files::GetFileContent("/path/to/a/file");

To recursively delete a directory

    $items_deleted = Files::RecursiveUnlinkDir("/path/to/a/dir");

To determine a file type

    $mime_type = Files::DetermineFileType("/path/to/a/file"); // "image/jpg"

To write a content to a temporary file

    $temp_filename = Files::WriteToTemp($some_content);

And so on.

TODO: The functions list needs to be completed.

Installation
------------

Use the Composer to install the panel.

    cd path/to/your/project/
    composer require atk14/files dev-master

Licence
-------

Files is free software distributed [under the terms of the MIT license](http://www.opensource.org/licenses/mit-license)
