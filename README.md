# ReleaseZip

Simple utility to generate a datestamped archive from the git repository
and tag the commit from which the archive is generated. 

On the first run in a particular directory it will generate a
configuration file. On the next run it will use the (probably modified)
configuration to generate the archive file name with current date
inserted as a version string. If there was an release already, the
datestamp will be prefixed with 'b', 'c', 'd' etc. 

## TODO

Provide the means to find and use last released version string before
the datestamp, so the archive name becomes something like:

BaseName-1.2.20110906.zip

The version string can come from some file in the repository or from
branch name.


