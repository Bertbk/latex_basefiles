# Base file for lualatex

## How to install?

### Fork the project on GitHub

**Do not forget to delete the fork relationship!**

### Clone

For new project named `project` :

```bash
git clone git@github.com:Bertbk/latex_basefiles.git project
cd project
git remote remove origin
```
If you want to set a remote repository again:

```bash
git remote add origin url_of_the_git_repo -u
```

## What next ?

- Keep only the basefile you want (lualatex or latex)
- Rename it to whatever you want
```
git mv basefile.tex myfile.tex
git commit -m "changed my file!"
```

## Gitignore

[list of up-to-date gitignore files](https://github.com/github/gitignore). Download [the tex .gitignore file](https://raw.githubusercontent.com/github/gitignore/master/TeX.gitignore):
```bash
curl -LO https://raw.githubusercontent.com/github/gitignore/master/TeX.gitignore .gitignore
```