# Reviews Checker
Script to help with the organization of code reviews of the ICP blockchain

## How to use:

1. git clone or just straight out copy the script into the root of the folder you are working on
2. in case permissions are needed to execute the script, use the following command: `chmod +x check_reviews`
3. to execute the script use the following command:
`./check_reviews "git log --format='%C(auto) %h %s' <HASH>..<HASH> ./<FOLDER>"`
4. When executing the script for the first time a file called `reviewed_commits.txt` will be created. This is the file where the reviewed commits will be stored alongside their review like so:  
`<HASH> <REVIEW>`  
`<HASH> <REVIEW>`  
...  
`<HASH> <REVIEW>`

As of now the processs to place the reviews in the `reviewed_commits.txt` file is still manual

## Example
![image](https://github.com/user-attachments/assets/6539aa7d-c6f6-49bf-8ab8-89d4d4a8dbac)
