# VIPSoft\Unzip

A wrapper around ZipArchive to extract .zip files.

This is a refactoring of my Piwik_Unzip_ZipArchive class.  It now requires
php 5.3.6+, uses namespaces, adheres to object calisthenics, and is re-licensed
as MIT.

*All the work belongs to Anthon Pang; dvlpp contribution was only to be less restrictive regarding the names og the files in the ZIP when unzipping. It's probably less secure, but was mandatory in some projects*

## Features

* Simple to use!

    ```php
    use VIPSoft\Unzip\Unzip;

    $unzipper  = new Unzip();
    $filenames = $unzipper->extract($zipFilePath, $extractToThisDir);
    ```

* Guards against malicious filenames in the archive

## Copyright

Copyright (c) 2010-2012 Anthon Pang. See LICENSE for details.

## Contributors

* Anthon Pang [robocoder](http://github.com/robocoder)
