How to set up new Git repository and create development branch step-by-step:

1. Create a New Repository on GitHub
2. Create local dir "new-project"
   mkdir new-project
3. Create a New Local Repository
   cd new-project
   git init 
4. Create and switch to the development branch:
   git checkout -b development
5. Add your changes and commit:
   git add .
   git commit -m "Your commit message"
6. Push changes to GitHub:
   git push <remote repository name> development
7. Merge changes into the main branch:
   git checkout main
   git merge development
   git push <remote repository name> main
