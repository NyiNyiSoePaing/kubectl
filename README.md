### Build Docker

- docker build . -t nnsp/kubectl

### Check kubectl version

- docker run -it nnsp/kubectl kubectl version --client

### Shell login

- docker run -it nnsp/kubectl sh