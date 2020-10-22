# git-squash
> Git squash easy way

This small script mimics what GitHub's [Squash portion](https://docs.github.com/en/free-pro-team@latest/github/collaborating-with-issues-and-pull-requests/about-pull-request-merges#squash-and-merge-your-pull-request-commits) does for their _Squash and merge_ option on a Pull Request. It basically means you can easily squash all your commits into a single commit with this script without having to deal with finding out the first commit on your current branch that does not exist on the target branch.

## Installation

- Download [git-squash](git-squash) and place it in a path that is in `$PATH`

### Global installation

```shell
sudo curl https://raw.githubusercontent.com/techgaun/git-squash/main/git-squash -o /usr/local/bin/git-squash && sudo chmod +x /usr/local/bin/git-squash
```

### Local installation

Assuming the local path ($HOME/.bin in this example) is in `$PATH`:

```shell
curl https://raw.githubusercontent.com/techgaun/git-squash/main/git-squash -o "${HOME}"/.bin/git-squash && chmod u+x "${HOME}"/.bin/git-squash
```

## Usage

- Make sure your current branch does not have merge conflicts with target branch

```shell
git merge main
git squash main
```

## Authors

- [techgaun](https://github.com/techgaun)
