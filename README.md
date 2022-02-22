# Hi, GitHub!
Experiments with git:
- [x] Create a new repository 
- [x] Write this readme
- [x] Install git
- [x] Create SSH key and add SSH key to GitHub
  ```
  ssh-keygen -t ed25519 -C 'my@email'
  eval "$(ssh-agent -s)"
  ssh-add ~/.ssh/id_ed25519
  ```
- [x] Clone repository  
  ```
  git clone git@github.com:luridev/hi-github.git
  ```
- [x] Update README.md
- [x] Add this file to staging area  
  ```
  git add 'README.md'
  ```
- [x] Commit and push  
  ```
  git commit -m 'Update README.md from git'
  git push
  ```