# Create a new repository on the command line
````commandline
echo "# jenkins-pipeline" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/sidde3/jenkins-pipeline.git
git push -u origin main
````
# Push an existing repository from the command line
````commandline
git remote add origin https://github.com/sidde3/jenkins-pipeline.git
git branch -M main
git push -u origin main
````