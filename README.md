# Git and GitHub: Branches
The goal is show how create a new branch, merge, delete etc

![image](https://github.com/user-attachments/assets/9f19ffe4-6598-4a1a-ac26-d1e625afc0ea)

- Why?
  * When it has many people working in the same project
  * Create a version to test

- Document:

https://docs.github.com/en/repositories/configuring-branches-and-merges-in-your-repository

### Create new branch

1 - Use command: ``` git checkout -b "New name Branch" ```:

![image](https://github.com/user-attachments/assets/2f2ce8af-5c57-42df-a428-fc0c59e19c56)

Look image above, After execute command the return is in the new branch. So, Everything that  make to will be directioned for it.

### How set Branch I want to use?

2 - Use command: ``` git checkout "Branch's name" ```:

![image](https://github.com/user-attachments/assets/116ac667-a9f8-4cea-9fe9-b88277cdd7ec)

### Validate what "commit" each branch is it? 

3 - Use command: ``` git branch -v ```

![image](https://github.com/user-attachments/assets/07754f48-f002-4ce0-b2cc-3a697cd36f4f)

### Merge Branch

Imagine you created a test branch because you would want test a new feature. So, You accomplish the tests and okay. Now, you want include this feature in the main branch.  

4 - Use command: ``` git merge "Branch Name" ```

![image](https://github.com/user-attachments/assets/93d606b6-7c65-400d-b651-6277277dc71a)

But after of the merge the branch Test continue there, in the repository. Use command ``` git branch ``` to show the branch existent.

![image](https://github.com/user-attachments/assets/4d71ba87-226f-4c42-a5ac-1b0890d0d271)

5 - Lest's exclude because not necessary more. Use command: ``` git branch -d "Branch name" ```.

![image](https://github.com/user-attachments/assets/6864152c-f494-432b-a7c9-64c7e9920811)

Consult again Use command ``` git branch ```:
![image](https://github.com/user-attachments/assets/b7c36592-6b7e-4f9d-bce3-2889a2912597)

### Possible conflict of merge

Your coworker made a commit and send to portal GitHub and you try to send a new  commit to portal GitHub. And your version is diferent with portal.

1 - Modification made for coworker directly portal GiHub:

![image](https://github.com/user-attachments/assets/d764d95d-1c10-44af-bcc3-889ffd34ba8c)

your Local project without modification made for coworker:
![image](https://github.com/user-attachments/assets/0a7b90dd-9f24-47cc-8078-3e9fefe750d9)

2 - Use command: ``` git pull ```. So, command screen will show message:

![image](https://github.com/user-attachments/assets/c8d4bb08-25da-4779-b3a2-2a56fa966355)

Next step, you need evaluate changes and exclude, change, maintain the necessary. After check, Use commands:

- ``` git add . ```
- ``` git commit -m"Description of the change" ```

![image](https://github.com/user-attachments/assets/c4a0b46b-f6ac-4657-a515-40ed406b25ec)

3 - Upload this new change to portal.

https://github.com/WanderBernardo/Git_Github_DownloadUpload
  


