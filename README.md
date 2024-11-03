**Useful GitHub CLI Commands:**

- Clone a Repository:

		git clone <repository-url> 

- Add a Remote to a Repository:

		git remote add origin <new-repo-url> 

- Push Changes to a Remote Repository:

		git push -u origin main

- Authenticate

 		gh auth login

- Rename a Branch:

		git branch -M main 

- Delete a Local Branch:

		git branch -d <branch-name>

- For Force Deletion:

 		git branch -D <branch-name> 

- Delete a Remote Branch:

 		git push origin --delete <branch-name> 

- Merge Branches:

 		git merge <branch-name> 

- Allow Unrelated Histories:

 		git merge <branch-name> --allow-unrelated-histories 

- Fetch Updates from a Remote Repository:

 		git fetch <remote-name> 

- Check Current Branch:

 		git branch 

- Add Files to Staging:

 		git add . 

- Commit Changes:

		git commit -m "Commit message" 

- Run a Command from Shell History by Number:

 		!<command-number> 

- Set a New Remote URL:

 		git remote set-url origin <new-repo-url> 

- Remove a Remote (Detach a local repo from its master:

 		git remote remove origin 

- Ensure the Remote has been Removed, check the remotes:

 		git remote -v 

- Add the New Repository as a Remote:

 		git remote add origin <new-repo-url> 

- Push to the New Remote:

 		git push -u origin main 
 
**Useful Google Cloud CLI Commands:**

- Autenticate with username/password on CLI (will open a browser to perform the authentication)

		gcloud auth application-default login
