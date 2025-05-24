# Git Tutorial

## Create ssh key

```sh
ssh-keygen
eval $(ssh-agent -s)
ssh-add <directory to private SSH key>
ssh -T git@github.com
```