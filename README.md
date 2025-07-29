# Github
Add multiple file to git using Cmd

If your files look like this , you better use cmd to put or else it will be a mess to add files one by one
![github look](https://github.com/user-attachments/assets/acd7ceca-92c2-43a3-b213-145b504bfe29)


## Steps to Upload a File Using CMD
1. Navigate to your project folder
   
Open CMD and use the cd command:
```
cd path\to\your\project
```


2. Initialize Git

```
git init
```


3. Add your remote repository
   
Replace <your-repo-url> with the actual GitHub repo link:

```
git remote add origin https://github.com/your-username/your-repo-name.git
```


4. Check Git status (optional)

```
git status
```


5. To add all files use . or if a particular file , use the file name instead

```
git add .
git add Github.pdf
```


6. Commit your changes

```
git commit -m "Initial commit"
```


7. Set the branch (if using main)

```
git branch -M main
```


8. Pull from remote if it has content (to avoid conflicts)

```
git pull origin main --allow-unrelated-histories
```


9. Push your files to GitHub

```
git push -u origin main
```


For any problem , feel free to contact
