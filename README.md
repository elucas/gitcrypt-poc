# gitcrypt-poc
Proof of concept test repo for working with git-crypt

```
    sudo apt-get install git-crypt
    cd <REPO_NAME>
    git-crypt init
    git-crypt export-key /path/to/new/crypt.key
    
    echo "Secrets!" > secrets.txt
    echo "secrets.txt filter=git-crypt diff=git-crypt" > .gitaccess
    
```