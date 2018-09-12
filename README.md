# Base file for lualatex and latex

## How to install?

Suppose you want the `lualatex.tex` file:

```bash
curl -LO https://github.com/Bertbk/latex_basefiles/lualatex.tex
```
Then rename it and add a [prepared tex .gitignore file](https://raw.githubusercontent.com/github/gitignore/master/TeX.gitignore):
```bash
curl -LO https://raw.githubusercontent.com/github/gitignore/master/TeX.gitignore --output .gitignore
```
If you want to use git to control your work (which I recommend):
```bash
git init
```
and eventually add a remote (github or whatever)
```bash
git add remote origin myremoterepo -u
git push
```

## Forking the repo?

Ok but then **do not forget to delete the fork relationship!**
