# gh-blazing-fast

gh: https://cli.github.com/manual/installation

```shell
brew install gh
```

## create repo, blazing fast

```zsh
ghrc() {
  if [ $# -eq 1 ]; then
    gh repo create $1 --public --add-readme --gitignore Node --license MIT -c
  else
    echo "Usage: ghrc <repository_name>"
  fi
}
```

## delete repo, blazing fast

```shell
npm install -g ghpew
```

```zsh
alias ghrd='ghpew repos'
```
