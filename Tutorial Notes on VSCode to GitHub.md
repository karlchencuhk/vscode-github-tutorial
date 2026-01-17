Before start:
Install vs-code
https://code.visualstudio.com/download
Install git
https://git-scm.com/install/mac

### Exercises1 
1. Initial a git repo in a folder in vs-code
	Create a new folder
	**mkdir my-first-repo**
	(or use an existing one)
	
	Change the current directory (folder) in your terminal to a folder named `my-first-repo`
	**cd my-first-repo**
	
	Initialize it as a git repository
	**git init**

2. Create an md file called `hello.md`, and write "Hello World!" in it.
	
	**Nano hello.md**
	Write inside Markdown         
	**Hello World!**
	Then press Ctrl + O → Enter → Ctrl + X to save & exit.

3. Commit the changes.
	
	**git commit -m "Add hello.md with Hello World!"**
	it should show 1 file changed, 1 insertion(+)

4. Register a github account (if you haven't done so).
	
	Create your own Github
	https://github.com/
	
	Create repo in Github (means repositories, a github folder where you want the data pull to)
	Create Depository name
	Do NOT check "Add a README file", ".gitignore" or license
	Click Create repository, now you have a empty repo in Github.
	
	Connect your local repo and push (from terminal)
	
	Add the remote (replace with YOUR url)
	**git remote add origin https://github.com/your-username/my-first-repo.git**
	
	 (Optional) Check it was added
	**git remote -v**

5. Push the latest commit to github.
	**git push -u origin main**
	vs-code will ask your permission to login github, agree, then done.

6. Pull a repo from github
	**git pull**
	done
