# git-squash
> Git squash easy way

## Installation

- Download [git-squash](git-squash) and place it in a path that is in `$PATH`

### Global installation

```shell
curl https://raw.githubusercontent.com/techgaun/git-squash/main/git-squash -O /usr/local/bin/git-squash && chmod +x /usr/local/bin/git-squash
```

### Local installation

Assuming the local path ($HOME/.bin in this example) is in `$PATH`:

```shell
curl https://raw.githubusercontent.com/techgaun/git-squash/main/git-squash -O "${HOME}"/.bin/git-squash && chmod u+x "${HOME}"/.bin/git-squash
```

## Usage

- Make sure your current branch does not have merge conflicts with target branch

```shell
git merge main
git squash main
```

## Authors

- [techgaun](https://github.com/techgaun)
