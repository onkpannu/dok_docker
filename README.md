# Install Docker on Ubuntu 18.04

Apt update:
```markdown
 # apt-get update
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

Apt update:
```markdown
 # apt-get update
```

Install docker-ce edition:
```markdown
 # apt-get install docker-ce -y
```

Enable docker service:
```markdown
 # systemctl enable docker
```

Restart docker service:
```markdown
 # systemctl restart docker
```

Check docker version:
```markdown
 # docker version
```

At this time docker is up and running, let's do some testing now to make sure everything is all good.

List locally availabe docker images (should be none for new install):
```markdown
 # docker images
```

List running and stopped containers (should be none for new install):
```markdown
 # docker ps --all
```


