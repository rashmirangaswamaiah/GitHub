**GITHUB for complete beginners**

This document is for the beginners who would like to use the Github for the first time.
1. Firstly, the SSH key need to be generated if the user is using git for the first time.
      - The command used to generate SSH key is "**ssh-keygen**"
2. Copy the generated key into Github. Got to **settings-> SSH Key -> add the generated key**
3. After the key is generated, now it's time to create a repository in Github.
4. Next step is to clone the repository, copy the newly created repository address from the Github.
      - "**git clone https://github.com/githubusername/repositoryname.git**"
5. Create a new directory (mkdir Newdirectory).
6. Copy your project folder into this Newdirectory.
7. Change the present working directory to the Newdirectory.
8. Then run these commands
      - git init
      - git add ProjectFolderName
      - git commit - m "any message"
      - git remote add https://github.com/githubusername/repositoryname.git
      - git push -u origin master
