

    $ meteor --port $IP:$PORT
    
#Readme!

##Create a new project from scratch, with a new repository 

1. Create a public repository on Github. Don't initialize with with anything. 
2. Create a new project in Cloud9. Give it the same name. Be sure you're logged into Cloud9 with your Github credentials. 
3. In a Cloud9 terminal:
        


        git init 
        git remote add orgin github.com/carypotter/Art742b.git
        git add -A 
        git commit -m "Initial commit" 
        git push
        
Change the remote URL based on what it says in your Github repo.

'git init': Initializes the local repository

'git remote add orgin': connect your local repository to a remote repository called 'orgin'. 
Copy the remote URL from your Github repository

'git status': see what the changed files are. 

'git add -A': Add all changed files to the commit 