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
[Please get the developer token of evernote](https://www.evernote.com/api/DeveloperToken.action)   
OSX have saved the token to keychain  

    $ snipe --config

Usage
-----
View the note list

    $ snipe
    Search tag --> '<tag>'
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
    
    snipe version 0.0.1
    
    positional arguments:
      number         number of snippet
    
    optional arguments:
      -h, --help     show this help message and exit
      --config       set user config
      -v, --version  show program's version number and exit
