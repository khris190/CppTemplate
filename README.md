### to start in cmake-tools nvim use :CMakeBuild

# Clone the repository
git clone https://github.com/khris190/CppTemplate.git {newName}

# Change directory to the new repository
cd {newName}

# Remove the remote origin
git remote remove origin

#unified command
```bash
TMP_NEW_DIR_NAME="MyProject" && git clone https://github.com/khris190/CppTemplate.git "$TMP_NEW_DIR_NAME" && cd "$TMP_NEW_DIR_NAME" && git remote remove origin
```
