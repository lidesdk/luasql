luasql
======

.. code-block::

 author   : Pedro Miller Rabinovitch, Roberto Ierusalimschy, Diego Nehab (ODBC), Carlos Cassino, Tomás Guisasola and Eduardo Quintão (PostgreSQL).
 version  : 
 website  : http://keplerproject.github.io/luasql
 arch     : x64, x86
 binaries : windows, linux
 license  : MIT/X11 

LuaSQL is a simple interface from Lua to a DBMS. 

====================================================================================  ======================================================================================
 Linux                                                                                  https://circleci.com/gh/lidesdk/lanes/tree/package.lide
====================================================================================  ======================================================================================
 .. image:: https://circleci.com/gh/lidesdk/lanes/tree/package.lide.svg?style=svg        Tests currently executed in Ubuntu 14.04 (Trusty) x64 machine
====================================================================================  ======================================================================================  

==================  ================================================================================
  Documentation:     http://keplerproject.github.io/luasql
==================  ================================================================================

----------------------------------------------------------------------------------------------------

LuaSQL is a simple interface from Lua to a DBMS. It enables a Lua program to:

    * Connect to ODBC, ADO, Oracle, MySQL, SQLite, Firebird and PostgreSQL databases; 
    * Execute arbitrary SQL statements;
    * Retrieve results in a row-by-row cursor fashion.

LuaSQL is free software and uses the same license as Lua 5.1.