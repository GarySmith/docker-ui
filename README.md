To check out all of the source locally including submodules, use:

```
git clone --recurse-submodules https://github.com/GarySmith/docker-ui.git
```

or, if the repo has already been cloned, then get the submodule sources with:
```
git submodule update --init
```

Build all of the containers with:
```
docker-compose build
```

Run all containers with:
```
docker-compose up
```
and wait for all 3 containers to become available; keystone will typically
be the slowest one to become available.

