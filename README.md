# My VS Code Extensions 
(I use Neovim normally btw...)
### Set up
Firstly, make sure the default branch name is `main`
```bash
git config --global init.defaultBranch main
```
Or, to change the name of the branch,
```bash
git branch -M main
```
Run the following command in the root to get the list of extensions
```bash
mkdir .vscode
cd .vscode
git init
git add remote origin https://github.com/rikuyaosawa/my-vscode-extensions.git
git pull origin main
```
Done.