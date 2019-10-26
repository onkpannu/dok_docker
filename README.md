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
```
> root@touting1:~# docker version
> Client: Docker Engine - Community
>  Version:           19.03.4
>  API version:       1.40
>  Go version:        go1.12.10
>  Git commit:        9013bf583a
>  Built:             Fri Oct 18 15:54:09 2019
>  OS/Arch:           linux/amd64
>  Experimental:      false
> 
> Server: Docker Engine - Community
>  Engine:
>   Version:          19.03.4
>   API version:      1.40 (minimum version 1.12)
>   Go version:       go1.12.10
>   Git commit:       9013bf583a
>   Built:            Fri Oct 18 15:52:40 2019
>   OS/Arch:          linux/amd64
>   Experimental:     false
>  containerd:
>   Version:          1.2.10
>   GitCommit:        b34a5c8af56e510852c35414db4c1f4fa6172339
>  runc:
>   Version:          1.0.0-rc8+dev
>   GitCommit:        3e425f80a8c931f88e6d94a8c831b9d5aa481657
>  docker-init:
>   Version:          0.18.0
>   GitCommit:        fec3683
> root@touting1:~#
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


