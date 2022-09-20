# Dockerfiles
Instead of build, you can pull the images directly from my DockerHub

### Stress-ng
```bash
docker image pull maurifc/stress-ng
```

# Useful commands

### Run using docker interactively
```bash
docker container run -ti maurifc/IMAGE
```

### Run on a K8s cluster interactively
```bash
kubectl run -ti --rm stress-ng --image maurifc/stress-ng -- stress-ng --vm 2 --vm-bytes 1G
```