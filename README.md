# Documentation for git

- Initialize the project

This should be done at the begining of the project only.


```bash
git init
```

-check the user name and email

if user name and email is not set, set them.

```bash
git config user.name "<github user name>"
git config user.email "<github email'>
```

This is the most use important command.
-checking the status of the project
```bash
git status
```

- Adding file to staging area
```bash
git add <file_or_folder_path>
```

- Commiting the changed files / folders
```bash
git commit -m "<your message>"
```

- Amend the last commit message
```bash
git commit --amend
```


Message should be in present tense. For e.g setup the initial git project

- See the logs

```bash
git log --oneline
```

-Adding rmote to our repository
```bash
git remote add origin <repository_url>
```

- Check current branch
```bash
git branch
```

- Rename current branch
```bash
git branch -M <new_brach_name>
```

- Push latest changes to the remote 
```bash
git push origin <branch_name>
```