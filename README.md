### Bashmarks is a shell script that allows you to save and jump to commonly used directories. Now supports tab completion.

## Install

1. Download bashmarks.sh
2. Source bashmarks.sh from your .bashrc file


## Commands

    s <bookmark_name> - Saves the current directory as "bookmark_name"
    g <bookmark_name> - Goes (cd) to the directory associated with "bookmark_name"
    l                 - Lists all available bookmarks
    
## Example Usage

    cd /var/www/
    s webfolder
    cd /usr/local/lib/
    s locallib
    l
    g web<tab>
    g webfolder

## Deleting Bashmarks
    
All of your directory bookmarks are saved in a file called ".sdirs" in your HOME directory. Anytime you want to delete a bookmark, just open it up and delete the corresponding lines.

