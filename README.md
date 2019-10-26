# Install Docker on Ubuntu 18.04

Apt update:
```markdown
 # sapt-get update
```

Remove the old version of docker:
```markdown
 # apt-get remove docker docker-engine docker.io -y
```

Add the key:
```markdown
 # curl -fsSL https://download.docker.com/linux/ubuntu/gpg | sudo apt-key add -
```

Add the repo:
```markdown
 # sudo add-apt-repository "deb [arch=amd64] https://download.docker.com/linux/ubuntu $(lsb_release -cs) stable"
```
