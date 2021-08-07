# Setting up a github repository 

## Initial setup

- Create an account on [Github](https://www.github.com)
- Click on the sign up button to sign up with details requested
- Create a new github repository with name `HORISEON-REFACTOR` [here](https://github.com/new)
- You can add a description if you want (optional).
- You can chose a private or public repository, I plan on using public
- Usally I check the box for "Add a README file" 
- Then click 'Create repository'

A good tutorial get started with git can be found on [atlassian](https://www.atlassian.com/git/tutorials/setting-up-a-repository)


## Contributing to this repository

- After cloning the repository, create a new branch 
   ```md
    git checkout -b <branch-name> 
   ```
- Make required changes to you the file and run following commands to apply
   ```
     git add -A (add file)
     git commit -m "Comment on changes"
     git push origin <brach-name> 
  ``` 
- The above command will give you a URL 
- Open a browser to point to the URL and request a pull request. 
