# git-cheatsheet



#### First Config
```bash
git config --global user.name "<Your-Name>"
git config --global user.email "<Email>"
git config --global color.ui auto
```

#### Basic

```bash
git clone "<URL>"
	"<URL>" "<Custom Name>"
git status
git add .	     #Add all changes to staging index.
	"<File-Name>"	  #Add specific files to staging index.
git commit
           -m "<Message>" #Add commit message.
git diff                  #View unstaged changes.
```

#### Logging

```bash
git log        
	--oneline        
	--stat          #Gives summary of files modified and number of lines changed.        
	-p              #--patch, displays actual changes made.        
	-p "<SHA>"      #Starting from commit with given SHA.
git show "<SHA>"        #Same as --patch for single commit.
```

