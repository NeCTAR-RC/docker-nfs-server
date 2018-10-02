# docker-nfs-server

Simple NFS Server used by the [Kubernetes 101 lab](http://kubernetes-101.rc.nectar.org.au/).

This is built by running:
```
docker build -t andybotting/nfs-server:1.0 -t andybotting/nfs-server:latest .
```

Once built, it should be pushed to Docker Hub:
```
docker push andybotting/nfs-server
```
