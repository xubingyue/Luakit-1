
Contents of the openssl\netware directory
==========================================

Regular files:

readme.txt     - this file
do_tests.pl    - perl script used to run the OpenSSL tests on NetWare
cpy_tests.bat  - batch to to copy test stuff to NetWare server
build.bat      - batch file to help with builds
set_env.bat    - batch file to help setup build environments
globals.txt    - results of initial code review to identify OpenSSL global variables


The following files are generated by the various scripts.  They are
recreated each time and it is okay to delete them.

*.def - command files used by Metrowerks linker
*.mak - make files generated by mk1mf.pl
