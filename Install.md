# Docker installation commands

This is to install Docker in AWS EC2 Linux machines

1. Run update command

```
sudo yum update -y
```

2. Install docker

```
sudo amazon-linux-extras install docker -y
```

3. Start Docker

```
systemctl start docker
```

4. Enable Docker

```
systemctl enable docker
```

5. Add ec2-user to docker group

```
sudo usermod -a -G docker ec2-user
```

Log out of machine and login again