# draft-irtf-icnrg-archives

An ICN extension to FLIC to support archives.  Archives are collections of multiple files with optional subdirectories, similar to a TAR file.

Archive-Like Extendable Collections (ALEC) are a new type of manifest to enumerate directories, essentially, so they can reconstruct
a collection of files.  In spirit, it is like a tar or zip archive, but supports data deduplication, versioning, and diff/patch
updates.
