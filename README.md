# Git-Practicals

## 1. Pull and Merge difference

- Make example of pull request and two branch merge event.

### Approach  :

  - first initialize the git.
  - create two files and add & commite 
  - Add remnote and push 

![1 1](https://user-images.githubusercontent.com/125361611/219308835-560b2d11-86f0-4e16-84e6-5ea8f2786625.png)

  - create new branch feature1
  - create new login file
  - add & commit
  - Then push to create pull request
  
![1 2](https://user-images.githubusercontent.com/125361611/219309368-30914037-7f86-4406-b467-ab6e983e6195.png)

  - create pull request on github
  
![1 3](https://user-images.githubusercontent.com/125361611/219310982-8b93b386-fb39-4e5a-95a5-a0b447d29ca5.png)

  - write comment and create pull request
  
![1 4](https://user-images.githubusercontent.com/125361611/219327593-330bd1a1-1b73-4e82-ad4f-fa2cbec3f1ac.png)

  - merge pull request by confirming merge request
  
![1 5](https://user-images.githubusercontent.com/125361611/219340281-82905e2a-f9d2-4b06-8b13-92cc8f482fb9.png)

  - pull request successfully merge and closed
  
![1 6](https://user-images.githubusercontent.com/125361611/219340406-8fa8951b-cc37-485b-9130-57fd8181cc6f.png)

## 2. Rebase

- Try to rebase feature branch with master branch 

### Approach  :

  - modify in loginfeature
  - add & commit 
  - then push to remote 
  - switch to master branch 
  - then rebase master branch with feature1 branch 

![2 1](https://user-images.githubusercontent.com/125361611/219342701-f7df4b6b-fe33-49c6-b6ec-f99fb2c9a517.png)
![2 2](https://user-images.githubusercontent.com/125361611/219342777-43ed297e-66f5-4837-9480-e005ebd440b8.png)

## 3. Change commit message

- Commit push on commit in feature branch and then change commit message

### Approach  :

  - switch to feature1 branch 
  - change the commit message
  - then push to remote
  
![3 1](https://user-images.githubusercontent.com/125361611/219342826-12386c56-e633-49ea-8164-705de25f0d5d.png)
![3 2](https://user-images.githubusercontent.com/125361611/219342857-05772a4f-950b-49ad-8e0b-775f1fd6feba.png)

## 4. cherry pick

- Pick some commits from feature branch to master branch

### Approach  :

  - create a new bugfix file in feature1 branch 
  - add and commit 
  - then push it to remote 
  - switch to master branch 
  - cherry-pick the bugfix file into master branch
  - then push it to remote

![4 1](https://user-images.githubusercontent.com/125361611/219367355-56bf4122-df12-453b-930f-9eede43539b6.png)

## 5. Drop commit

- Remove some commit from feature branch.

### Approach  :

  - check the all commit history
  - pick last commit and delete it
  - push with -f flag 

![5 1](https://user-images.githubusercontent.com/125361611/219367396-a80eb030-c017-4a95-971f-f1683ae69b34.png)
