===========
py-docstore
===========

Supersimple python document storage with default plain text file backend and configurable "keys".

Alternative projects
====================

If you are here you are looking for a lightweight solution for storing data without a big fat databare (or you are looking in the wrong place).

So well, of course you can simply use sqlite and (python native sqlite support)[https://docs.python.org/3/library/sqlite3.html]

If you are too lazy to deal with creating table and all that SQLNONS[1] you might like (dataset)[https://github.com/pudo/dataset] 

If you want something even simpler give (tinydb)[https://github.com/msiemens/tinydb] a chance.

py-docstore is actually inspired by them, but with a different focus: you can chose which properties make up a key (or should be unique) for your data. This simplifies searching, insert and updates obviously, with the drawback (or advantage?) of making those properties mandatory.

Warnings
========

This code is so untested it does not even yet exists.

Notes
=====

[1] SQLNONS stands for SQL NONSense, so there's NOSQL and there's SQLNONS.
Don't get this wrong. I really like SQL and I'm just trying to be fun and create an acronym that will survive me.
