snipe
=======
snipe is snippet command-line tool in cooperation with evernote.  


Install
-----
    $ sudo pip install snipe

Install mac osx
-----
    $ brew install ngc224/snipe/snipe

Setup
-----
Setup user config 

    $ snipe --config
    Get Evernote DeveloperToken URL --> https://www.evernote.com/api/DeveloperToken.action
    DeveloperToken: <developer token>
    Set search tag / Default is 'snipe'
    Search tag: <tag>
    Set search max limit / Default is 50
    Search limit: <limit>

Usage
-----
View the note list

    $ snipe
    search --> tag:'<tag>' limit:<limit>
    No 1 : <title>
    No 2 : <title>
    No 3 : <title>
    ...
    
Enter a Number to output a note content

    $ snipe 2
    <content>
    ...

Help
-----
    usage: snipe [-h] [--config] [-v] [number]
    
    positional arguments:
      number         number of snippet
    
    optional arguments:
      -h, --help     show this help message and exit
      --config       set user config
      -v, --version  show program's version number and exit
